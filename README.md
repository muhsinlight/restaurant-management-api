Restaurant Management API
📌 Proje Hakkında
Restaurant Management API, restoran işletmeleri için menü yönetimi, sipariş takibi ve masa rezervasyonları gibi temel işlevleri sunan bir backend servisidir. Node.js ve Express.js kullanılarak geliştirilmiştir.

✨ Özellikler
Menü Yönetimi: Yemek ekleme, güncelleme ve silme

Sipariş Takibi: Masa bazlı sipariş oluşturma ve yönetme

Rezervasyon Sistemi: Masa rezervasyonları için API endpoint'leri

Kullanıcı Yönetimi: Farklı yetki seviyeleri (admin/garson)

Raporlama: Günlük/haftalık satış raporları

🛠 Teknoloji Stack'i
Backend: Node.js, Express.js

Veritabanı: MongoDB (Mongoose ODM)

Kimlik Doğrulama: JWT

Test: Jest, Supertest

Diğer: Docker, Swagger (API dökümantasyonu)

🚀 Kurulum
Depoyu klonlayın:
git clone https://github.com/muhsinlight/restaurant-management-api.git
cd restaurant-management-api
Gerekli paketleri yükleyin:
npm install

Ortam değişkenlerini ayarlayın:
cp .env.example .env
.env dosyasını kendi bilgilerinizle düzenleyin.

Uygulamayı başlatın:
npm start

Veya geliştirme modunda çalıştırmak için:
npm run dev

📚 API Dökümantasyonu
Proje Swagger UI ile dökümante edilmiştir. Uygulama çalışırken aşağıdaki adresten erişebilirsiniz:
http://localhost:3000/api-docs

🐳 Docker ile Çalıştırma
docker-compose up --build

🧪 Testler
Testleri çalıştırmak için:
npm test

🤝 Katkıda Bulunma
Katkılarınızı bekliyoruz! Lütfen önce bir issue açın ve ardından pull request gönderin.

📜 Lisans
Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için LICENSE dosyasına bakın.
