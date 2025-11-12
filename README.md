🕷️  Insıze Web Scraper

Bu proje, Insize.com üzerindeki ürün liste sayfalarından ürün görsellerini ve PDF dokümanlarını otomatik olarak indirip ZIP arşivine kaydeden bir tarayıcı tabanlı scraper’dır.
Kullanıcı girişi gerektiren veya herkese açık liste sayfalarında kullanılabilir.

🚀 Özellikler

🔍 Ürün kartlarını “Code:” satırına göre algılar

📷 Karttaki görselleri (/upfiles/) otomatik olarak indirir

📄 Detay sayfalarındaki iframe, embed, object veya a[href=.pdf]* etiketlerinden PDF bağlantılarını bulur

🧩 Tüm indirmeleri JSZip kullanarak tek bir ZIP dosyasında toplar

⚙️ CORS engeli olan PDF’leri doğrudan tarayıcı indirme yöntemiyle indirir

🧭 Liste sayfaları arasında sayfa aralığı belirterek toplu tarama yapabilir

💾 ZIP dosyasını otomatik olarak insize.com-Scraper .zip adıyla indirir

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Gereksinimler

Bu scraper tamamen tarayıcı üzerinde çalışır. Ek bir sunucu veya terminal gerekmez.

Modern bir tarayıcı (Chrome, Edge, Firefox önerilir)

Hedef web sayfasında oturum açılmış olmalıdır (login’li sayfalar için)

JavaScript etkin olmalıdır

Kütüphaneler otomatik olarak CDN üzerinden yüklenir: https://cdn.jsdelivr.net/npm/jszip@3.10.1/dist/jszip.min.js


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1️⃣ Liste sayfasını açın

https://www.insize.com/index.php/list-382-1.html
