# Proje kataloğu

[English](https://github.com/arslanserhat/arslanserhat/blob/main/PROJECTS.md) · [GitHub profili](https://github.com/arslanserhat)

Ticaret operasyonları, raporlama, çok dilli ürünler, web siteleri ve oyun prototipleri üzerine çalışmalarım. Aşağıdaki açıklamalar uygulama kaynaklarında bulunan yapıları ve belgelenmiş kapsamı anlatır; güncel canlı erişim yalnız herkese açık bağlantı verilen üründe gösterilir.

| Proje | Odak | Durum |
|---|---|---|
| [eTahlil / e-Sonuç+](#etahlil) | Çok dilli belge ve rapor akışları | Herkese açık ürün; geliştirme sürüyor |
| [Fulfillment Hub](#fulfillment-hub) | B2B ticaret ve depo operasyonları | Geliştirme aşamasında |
| [Ciro Master](#ciro-master) | Ticaret operasyonları ve ERP raporlama | Uygulama ve entegrasyon çalışması |
| [İhracat Ürün Kataloğu](#export-catalogue) | Ürün bilgisi, görsel ve katalog hazırlama | Uygulama kaynakları mevcut |
| [BizReports](#bizreports) | Web analitiği ve dönemsel raporlama | Geçmiş dönem raporlama betikleri |
| [Klinik Web Sitesi ve İçerik Akışları](#clinic-website) | Hizmet içeriği, iletişim formları ve yayınlama | Geçmiş dönem web projesi |
| [Mobile Game Lab](#mobile-game-lab) | 3D web ve mobil oyun prototipleme | Prototip |
| [Zombie Runner 3D — Unity Prototipi](#zombie-runner-3d) | Üçüncü şahıs oynanış temelleri | Prototip |

<a id="etahlil"></a>

## eTahlil / e-Sonuç+

**Odak:** Çok dilli belge ve rapor akışları  
**Teknolojiler:** Next.js · TypeScript · FastAPI · PostgreSQL · Redis · Celery  
**Durum:** Herkese açık ürün; geliştirme sürüyor

Laboratuvar belgelerinin yüklenmesi, yapılandırılmış sonuçların işlenmesi ve anlaşılır açıklamaların sunulması için geliştirdiğim çok dilli web ürünü. Ürün akışları, web uygulaması ve Arapça RTL dahil çok dilli deneyim üzerinde çalışıyorum. Next.js arayüzleri; FastAPI, belge işleme ve rapor modülleri, kullanıcı panelleri ve bilgilendirici içerikle birlikte çalışıyor.

[Ürünü incele](https://www.etahlil.com.tr)

Bu vaka yazılım ve arayüz geliştirme çalışmasını anlatır; klinik doğrulama iddiası içermez.

<a id="fulfillment-hub"></a>

## Fulfillment Hub

**Odak:** B2B ticaret ve depo operasyonları  
**Teknolojiler:** React · TypeScript · Vite · NestJS · Prisma · PostgreSQL  
**Durum:** Geliştirme aşamasında

Bayi satın alma akışlarıyla depo operasyonlarını bir araya getiren B2B uygulama. Ürün ve stok yönetimi, siparişler, role göre ayrılmış ekranlar, depo dalga planlama, toplama listeleri ve barkodla toplama/paketleme kontrolü bulunuyor. İş kuralları, uygulama akışları ve entegrasyon ihtiyaçlarını aynı operasyon ürünü içinde ele alıyorum.

ERP ve kanal bağlantılarının geliştirilmesi sürüyor; uçtan uca canlı entegrasyon tamamlanmış olarak sunulmuyor.

<a id="ciro-master"></a>

## Ciro Master

**Odak:** Ticaret operasyonları ve ERP raporlama  
**Teknolojiler:** PHP · Laravel · React · Vite · Tailwind CSS · Recharts  
**Durum:** Uygulama ve entegrasyon çalışması

Pazaryeri operasyonları ve iş raporlaması için Laravel ve React çalışma alanı. Ürün ve sipariş akışları, Netsis bağlantılı fatura/cari raporları, stok durumu ve stok devir ekranları ile KPI panelleri içeriyor. Kaynakta Excel/PDF araçları bulunuyor; canlı bağlantılar ve uçtan uca çalıştırma doğrulanmadı.

<a id="export-catalogue"></a>

## İhracat Ürün Kataloğu

**Odak:** Ürün bilgisi, görsel ve katalog hazırlama  
**Teknolojiler:** React · Laravel · PHP · Excel import · jsPDF  
**Durum:** Uygulama kaynakları mevcut

İhracat ürün bilgilerini düzenlemek ve paylaşılabilir kataloglar hazırlamak için web uygulaması. Arama, kategori filtresi, ürün düzenleme, görsel yönetimi, Excel içe aktarma, fiyat geçmişi ve PDF katalog çıktısını bir araya getiriyor. React arayüzü ve Laravel API, katalog bakımını düzenli bir iş akışına dönüştürüyor.

<a id="bizreports"></a>

## BizReports

**Odak:** Web analitiği ve dönemsel raporlama  
**Teknolojiler:** Python · Google API clients · Search Console · MySQL Connector · pandas  
**Durum:** Geçmiş dönem raporlama betikleri

Sayfa bazında günlük ve aylık raporlama için Python betikleri. Web analitiği metriklerini Search Console tıklama, CTR ve konum verileriyle birleştiriyor. Komut satırı girişleri, API istek sınırlandırması ve rapor kayıt arayüzleri içeriyor. Veri toplama, düzenleme ve dönemsel raporlama alanındaki geçmiş çalışmalarımı gösteriyor.

Yeniden kullanım öncesinde eski API ve bağımlılık sürümlerinin uyumluluğu değerlendirilmelidir.

<a id="clinic-website"></a>

## Klinik Web Sitesi ve İçerik Akışları

**Odak:** Hizmet içeriği, iletişim formları ve yayınlama  
**Teknolojiler:** Python · Django · Templates · CKEditor · Sitemaps  
**Durum:** Geçmiş dönem web projesi

Hizmet tanıtımı, iletişim formları ve blogu bir araya getiren Django web sitesi. Ana sayfa, hakkımızda ve iletişim sayfaları; sunucu tarafında form işleme, sayfalı makaleler, zengin metinli yazılar, slug üretimi ve sitemap yapısı içeriyor. Sunucu tarafında oluşturulan web sayfaları ve içerik akışları konusundaki geçmiş deneyimimi gösteriyor.

Bazı özel içerik düzenleme işlemleri taslak kaldı. Proje, geçmiş dönem web sitesi çalışması olarak sunuluyor.

<a id="mobile-game-lab"></a>

## Mobile Game Lab

**Odak:** 3D web ve mobil oyun prototipleme  
**Teknolojiler:** TypeScript · Three.js · Vite · Capacitor  
**Durum:** Prototip

TypeScript ve Three.js ile 3D oyun prototipi. WebGL görüntüleme, durum tabanlı ekranlar, karakter/model ön yükleme, arenada düşman üretimi ve geliştirme sistemleri içeriyor. Vite araçları ve Capacitor Android paketleme yapılandırmasıyla uygulama mimarisini etkileşimli tarayıcı ve mobil oyun geliştirmeye taşıyor.

<a id="zombie-runner-3d"></a>

## Zombie Runner 3D — Unity Prototipi

**Odak:** Üçüncü şahıs oynanış temelleri  
**Teknolojiler:** Unity · C# · URP · Cinemachine · Input System · Starter Assets  
**Durum:** Prototip

Unity, C#, URP, Cinemachine ve Input System ile üçüncü şahıs oynanış prototipi. Starter Assets bileşenlerinden yararlanan çalışmada hareket ve kamera kontrolü, toplanabilir nesne etkileri, kalan nesne sayacı ve oyuncuyu yeniden doğurma akışları bulunuyor.

<details>
<summary>Başlangıç depoları ve proje geçmişi</summary>

Aşağıdaki üç depo, ayrı çalışan ürünler olarak sayılmıyor:

- **ciro-master-laravel:** Yalnız yapılandırma içeren depo başlangıcı. Uygulama çalışması yukarıdaki Ciro Master başlığında anlatılıyor.
- **laravel-ciro-app:** Uygulama kodu içermeyen, lisans dosyasıyla başlatılmış depo.
- **thehaberler:** Henüz anlatılabilecek uygulama kodu bulunmayan boş depo.

</details>

Arayüz örnekleri ve proje iletişimi: [Bionluk](https://bionluk.com/serhatarslan).
