# pwa-sistemi
PWA ios ve android için web sitenizi telefonlara uygulama şeklinde kaydetmesini sağlar.

1)Sistemi sitenize uygulayabilmek için index.html de bulunan:
        <link rel="stylesheet" href="src/master.css">
        <link rel="manifest" href="manifest.json">
        <link rel="apple-touch-icon" href="images/logo192.png">
        <!--PWA FOR İOS Support Kodlar-->
        <link rel="apple-touch-icon" href="images/logo96.png">
        <meta name="apple-mobile-web-app-status-bar" content="#aa7700">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <meta name="apple-mobile-web-app-title" content="Osman Gültekin"> 
bu kodları  kendi sitenizin head kısmına  ekleyin content content="Osman Gültekin" kısmını kendi başlığınıza göre değiştirin. Logo kısımlarınıda kendi logolarınız ile değiştiriniz.


2)Aşağıdaki script koduna kendi sitenizin body kısmına ekleyin.
        <script src="src/index.js"></script>
        
        
3)İstediğiniz logoları images dosyası altında belirtilen boyutlarda hazırladığınız logolar ile değiştirin bunun için canva kullanabilirsiniz.

4) manifest.json dosyasını projenize import edin ve içeriğini istekleriniz doğrultusunda değiştirin.

5) sw.js dosyasını import edin.

6) SRC klasörünü import edin.

HEPSİ BU KADAR BASİT VE KULLANIŞLI 

