LeadRun - Gelişmiş X Lead Generation ve Pazarlama Platformu
LeadRun, Twitter'da lead generation için gelişmiş yapay zeka destekli anahtar kelime üretimi sağlayan ve sosyal medya pazarlama stratejilerinizi optimize etmenize yardımcı olan bir platformdur.

Teknoloji Altyapısı
LeadRun, modern web teknolojileri kullanılarak geliştirilmiş bir full-stack uygulamadır:

Frontend
Next.js 15: React tabanlı modern web framework
TypeScript: Tip güvenliği sağlayan JavaScript süper kümesi
Tailwind CSS: Hızlı UI geliştirme için utility-first CSS framework
Clerk: Güvenli kimlik doğrulama ve kullanıcı yönetimi
Radix UI: Erişilebilir ve özelleştirilebilir UI bileşenleri
Sonner: Bildirim sistemi
Backend
Next.js API Routes: Frontend ile entegre API endpoint'leri
FastAPI: Python tabanlı yüksek performanslı API framework'ü
MongoDB: NoSQL veritabanı çözümü
OpenRouter API: Yapay zeka modellerine erişim (Grok-2, Claude vb.)
Brave Search API: Twitter içerik araması için API
RapidAPI: Alternatif Twitter arama API'si
DevOps
Vercel: Frontend deployment ve hosting
Railway: Backend deployment ve hosting
Sistem Mimarisi
LeadRun, frontend ve backend olmak üzere iki ana bileşenden oluşur:

Frontend (Next.js): Kullanıcı arayüzü ve client-side işlevsellik
Backend (FastAPI): Yapay zeka entegrasyonları ve veri işleme
Bu iki bileşen arasındaki iletişim, Next.js API Routes üzerinden gerçekleştirilir. Kullanıcı verileri ve uygulama durumu MongoDB'de saklanır.

Özellikler
Anahtar Kelime Üretimi X
Yapay Zeka Destekli Anahtar Kelimeler: OpenRouter API ve Grok-2 modeli kullanılarak şirketinize özel, yüksek kaliteli anahtar kelimeler üretme
Tam Olarak 60 Benzersiz Anahtar Kelime: Her sorguda tam olarak 60 adet benzersiz anahtar kelime üretilir
Detaylı Metrikler: Her anahtar kelime için arama hacmi, rekabet, tıklama başına maliyet ve dönüşüm potansiyeli gibi metrikler
Özelleştirilebilir Girdiler: Şirket bilgileri, sektör, ürünler/hizmetler, hedef kitle ve rakip bilgilerine göre özelleştirilmiş anahtar kelimeler
MongoDB Entegrasyonu: Üretilen anahtar kelimeler MongoDB'ye kaydedilir ve tekrar kullanılabilir
Tweet Arama ve Analiz
BraveSearch ve Rapid API Entegrasyonu: Twitter'da anahtar kelimelerinizle ilgili tweet'leri bulma
API Seçimi: Tweet aramalarında Brave Search veya Rapid API arasında seçim yapabilme, her iki API de tam işlevsel
Dil Seçimi: Türkçe veya İngilizce olarak tweet araması yapabilme, her iki API için de dil parametresi desteği
Toplu Arama: Tüm anahtar kelimeleriniz için otomatik ve sıralı tweet araması (10 saniye aralıklarla)
Koleksiyon Bazlı Organizasyon: Anahtar kelimeler tarih ve saate göre koleksiyonlar halinde düzenlenir, en yeni koleksiyonlar en üstte gösterilir
Optimize Edilmiş Arayüz: 3 sütunlu (3/12-3/12-6/12) düzen ile kolay kullanım ve daha iyi görsel organizasyon
MongoDB Veri Saklama: Tweet sonuçları doğrudan MongoDB'ye kaydedilir, aynı tweet farklı anahtar kelimeler için ayrı ayrı saklanabilir
Türkçe Karakter Desteği: Türkçe karakterleri doğru şekilde işleme ve görüntüleme
Arama ID Takibi: Her arama için benzersiz bir arama ID'si oluşturularak sonuçların takibi kolaylaştırılır
Arama Geçmişi: Kullanıcıların önceki aramalarını görüntüleyebilme ve filtreleyebilme
Anahtar Kelime Bazlı Tweet Kayıtları: Tweet kayıtları artık tweet_id, keyword_record_id VE search_keyword kombinasyonuna göre benzersiz olarak saklanır
Detaylı Loglama: Tweet kaydetme sürecinde kapsamlı log mesajları ile sorun giderme kolaylığı
Null Değer Güvenliği: Tweet verilerinde eksik alanlar için varsayılan değerler atanarak veri bütünlüğü korunur
Esnek MongoDB Sorguları: keywordRecordId null olduğunda bile doğru şekilde çalışan esnek sorgu yapısı
Veri Tutarlılığı: Tweet ve brave_search_results koleksiyonlarında tutarlı veri yapısı
Performans İzleme: Tweet işleme sonunda başarılı ve başarısız işlem sayıları detaylı olarak raporlanır
Mevcut Tweet Güncellemesi: Aynı tweet farklı bir anahtar kelime koleksiyonu aramasında bulunduğunda, tweet'in keyword_record_id ve diğer ilgili alanları güncellenerek son arama ile ilişkilendiriliyor
Doğru Dil Parametresi Desteği: Tweet arama API'sinde dil parametresi sorunu çözülerek, İngilizce ve Türkçe aramaların doğru şekilde çalışması sağlandı
Tip Güvenliği: TypeScript tip güvenliği artırılarak any kullanımı azaltıldı, özel arayüzler eklendi
Anahtar Kelime Koleksiyonu ID Entegrasyonu: Tweet aramaları artık anahtar kelime koleksiyonu ID'si ile ilişkilendirilerek, uyumluluk analizi sayfası için doğru veri bütünlüğü sağlanıyor
Frontend-Backend Veri Tutarlılığı: Frontend'den gönderilen keywordRecordId ve keywordCreatedAt değerleri MongoDB'de doğru şekilde saklanıyor
Yeni Özellik: Tweet Arama ve Analiz İyileştirmeleri:
Geliştirilmiş Arama Algoritması: Anahtar kelimeler ile ilgili daha doğru ve ilgili tweet'leri bulma
Hızlı Arama: Arama sonuçlarının daha hızlı geri dönmesi için optimize edilmiş arama algoritması
Detaylı Arama Sonuçları: Arama sonuçlarında daha fazla bilgi gösterilmesi için geliştirilmiş arayüz
Tweet Uyumluluk Analizi
OpenRouter API Entegrasyonu: Grok-2 modeli kullanılarak tweet'lerin şirket ve hedef kitle için uyumluluğunu analiz etme
Uyumluluk Puanı: Her tweet için 0-100 arasında bir uyumluluk puanı ve detaylı açıklama
Toplu Analiz: Tüm tweet'leri tek seferde analiz etme veya sadece analiz edilmemiş tweet'leri seçme imkanı
Analiz Durumu İzleme: Analiz sırasında gerçek zamanlı ilerleme takibi ve başarılı/başarısız analiz sayıları
Optimum Analiz Hızı: Tweet analizi arasında sadece 2 saniye bekleme süresi ile hızlı analiz imkanı
Filtreleme Seçenekleri: Tweet'leri uyumlu/uyumsuz olarak filtreleme
Debug Modu: Tweet analiz sonuçlarını detaylı inceleme imkanı
Gelişmiş Token Yönetimi: Her tweet analizi için güvenli token yenileme mekanizması
Hata Toleransı: Bir tweet'in analizi başarısız olsa bile diğer tweet'lerin analizine devam etme
Erişilebilirlik İyileştirmeleri: ARIA özellikleri ile ekran okuyucu desteği
Analiz Yenileme: Daha önce analiz edilmiş tweet'leri yeniden analiz etme imkanı
Veritabanı Entegrasyonu: Analiz sonuçlarının MongoDB'ye kaydedilmesi ve sonraki oturumlarda kullanılabilmesi
Performans Optimizasyonu: API isteklerinin ve veritabanı işlemlerinin optimize edilmesi
Tweet Yanıtlama
Yapay Zeka Destekli Yanıt Önerileri: OpenRouter API ve Grok-2 modeli kullanılarak tweet'lere profesyonel yanıtlar oluşturma
Çoklu Yanıt Seçenekleri: Her tweet için 3 farklı yanıt seçeneği sunma
Karakter Sınırı Kontrolü: Twitter'ın 280 karakter sınırına uygun yanıtlar oluşturma
Müşteri Bilgisi Entegrasyonu: Şirket ve müşteri bilgilerine göre özelleştirilmiş yanıtlar
Yanıt Geçmişi: Gönderilen yanıtları görüntüleme ve takip etme
MongoDB Entegrasyonu: Yanıt seçeneklerinin ve gönderilen yanıtların veritabanında saklanması
Genel Özellikler
Güvenli Kimlik Doğrulama: Clerk ile güvenli kullanıcı kimlik doğrulama ve yönetimi
Responsive Tasarım: Mobil ve masaüstü cihazlarda optimum kullanıcı deneyimi
Tema Desteği: Açık ve koyu tema seçenekleri
Hata İşleme: Kapsamlı hata yakalama ve kullanıcı bilgilendirme mekanizmaları
Performans Optimizasyonu: Hızlı sayfa yükleme ve işlem süreleri
Veri Önbelleği: Sık kullanılan verilerin önbelleğe alınması ile performans artışı
Kullanıcı Dostu Arayüz: Sezgisel ve kolay kullanılabilir kullanıcı arayüzü
Teknik Detaylar
Veri Modelleri
Anahtar Kelime Kaydı
Şirket bilgileri (ad, sektör, ürünler/hizmetler, hedef kitle)
Anahtar kelimeler listesi (her biri için metrikler)
Oluşturulma tarihi ve kullanıcı ID'si
Tweet Kaydı
Tweet metni ve ID'si
Yazar bilgileri
Arama anahtar kelimesi
Uyumluluk analiz sonuçları (puan, açıklama, uyumluluk durumu)
Yanıt seçenekleri
API Entegrasyonları
OpenRouter API
Anahtar kelime üretimi
Tweet uyumluluk analizi
Yanıt önerileri oluşturma
Brave Search API
Twitter içerik araması
Dil bazlı filtreleme
Sonuçların yapılandırılması
RapidAPI Twitter
Alternatif Twitter içerik araması
Gelişmiş filtreleme seçenekleri
Veritabanı Yapısı
MongoDB'de aşağıdaki koleksiyonlar kullanılmaktadır:

keywords: Anahtar kelime kayıtları
tweets: Tweet kayıtları ve analiz sonuçları
brave_search_results: Brave Search API sonuçları
tweet_replies: Gönderilen tweet yanıtları
Kurulum ve Çalıştırma
Gereksinimler
Node.js 18+
Python 3.9+
MongoDB
Kurulum Adımları
Repo'yu klonlayın:
git clone https://github.com/kullaniciadi/leadrun-clerk-next.git
cd leadrun-clerk-next
Bağımlılıkları yükleyin:
npm install
cd api && pip install -r requirements.txt
Gerekli ortam değişkenlerini ayarlayın:
# .env dosyası
MONGODB_URI=mongodb://...
OPENROUTER_API_KEY=...
BRAVESEARCH_API_KEY=...
CLERK_SECRET_KEY=...
CLERK_PUBLISHABLE_KEY=...
Uygulamayı çalıştırın:
npm run dev
Bu komut hem Next.js frontend'i hem de FastAPI backend'i eşzamanlı olarak başlatacaktır.

Geliştirme
LeadRun, modern web geliştirme pratiklerini takip eden bir yapıya sahiptir:

Component-Based Architecture: Yeniden kullanılabilir UI bileşenleri
API-First Development: Backend ve frontend arasında net API sözleşmeleri
Type Safety: TypeScript ile tip güvenliği
Responsive Design: Tüm cihazlarda optimum kullanıcı deneyimi
Progressive Enhancement: Temel işlevsellik her tarayıcıda çalışır, modern tarayıcılarda gelişmiş özellikler aktif olur
Katkıda Bulunma
Projeye katkıda bulunmak için:

Bu repo'yu fork edin
Yeni bir branch oluşturun (git checkout -b feature/amazing-feature)
Değişikliklerinizi commit edin (git commit -m 'Add some amazing feature')
Branch'inizi push edin (git push origin feature/amazing-feature)
Pull Request açın