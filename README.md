# pwa-sistemi
PWA ios ve android için web sitenizi telefonlara uygulama şeklinde kaydetmesini sağlar.

Progressive Web App (PWA) eklemek için aşağıdaki adımları izleyebilirsiniz:

HTTPS desteği: PWA'lar sadece HTTPS destekli sitelerde çalışır. Sitenizi HTTPS'ye geçirmeniz gerekir.

manifest.json dosyası oluşturun: Bu dosya PWA'nın nasıl görüneceği ve nasıl çalışacağı hakkında bilgi içerir. Örnek bir manifest dosyası şu şekildedir:

Copy code
{
  "name": "My PWA",
  "short_name": "My PWA",
  "start_url": "/index.html",
  "display": "standalone",
  "background_color": "#ffffff",
  "theme_color": "#000000",
  "icons": [
    {
      "src": "/images/icon-192x192.png",
      "sizes": "192x192",
      "type": "image/png"
    }
  ]
}
service worker oluşturun: Bu, PWA'nın çalışması için gerekli olan bir JavaScript dosyasıdır. Service worker, PWA'nın offline çalışmasını, bildirimleri ve diğer özellikleri sağlar.

manifest.json ve service worker dosyasını sitenize ekleyin: Bu dosyaları sitenizin kök dizinine yükleyin ve HTML dosyalarınızda referans olarak ekleyin. Örnek olarak :

Copy code
  <link rel="manifest" href="/manifest.json">
  <script src="service-worker.js"></script>
PWA test etmek için Lighthouse veya diğer araçları kullanabilirsiniz. Bu araçlar, PWA'nızın ne kadar iyi çalıştığını ve nasıl optimize edebileceğinizi gösterir.
Not: Bu yukarıdaki işlemler sadece PWA'nın temel özelliklerini eklemenizi sağlar. PWA'nın tüm özelliklerini kullanmak için daha fazla özelleştirme yapmanız gerekebilir.

