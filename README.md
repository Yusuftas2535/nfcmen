# NFCMenu - Restoran & Kafe POS Sistemi

Modern restoranlar için QR kod ve NFC teknolojisi ile dijital menü çözümü.

## 🚀 Özellikler

### İşletme Özellikleri
- ✅ **QR & NFC Menü** - Müşteriler QR kod veya NFC ile menüye erişebilir
- ✅ **Kategori Yönetimi** - Ürünleri kategorilere ayırma ve düzenleme
- ✅ **Ürün Yönetimi** - Görsel, açıklama, alerjen bilgileri ile ürün ekleme
- ✅ **Garson Çağırma Sistemi** - Müşteriler menüden direkt garson çağırabilir
- ✅ **Garson Paneli** - Garsonlar için özel yönetim paneli
- ✅ **Masa Yönetimi** - Masa durumları ve atama sistemi
- ✅ **Sipariş Takibi** - Gerçek zamanlı sipariş yönetimi
- ✅ **Analiz & Raporlar** - Detaylı satış analizleri ve müşteri davranış raporları
- ✅ **Çoklu Dil Desteği** - Türkçe, İngilizce ve diğer diller (Premium)
- ✅ **Offline Menü** - İnternet olmadan da menü görüntüleme (Premium)
- ✅ **Alerjen Bilgileri** - Ürünlerde alerjen uyarıları

### Plan Seçenekleri
- 🆓 **Ücretsiz Plan**: 20 ürüne kadar, temel özellikler
- 👑 **Premium Plan**: Sınırsız ürün, tüm özellikler (₺99/ay)

### Admin Paneli
- 📊 **Sistem Yönetimi** - Tüm restoranları yönetme
- 💰 **Gelir Takibi** - Premium abonelik gelirlerini izleme
- 📈 **Analiz Raporları** - Platform geneli istatistikler
- 🔧 **Restoran Onaylama** - Yeni kayıtları onaylama sistemi
- 👥 **Kullanıcı Yönetimi** - Restoran ve garson hesapları

### Garson Paneli
- 🔔 **Çağrı Yönetimi** - Müşteri çağrılarına yanıt verme
- 🍽️ **Masa Yönetimi** - Masa durumlarını güncelleme
- 📋 **Sipariş Takibi** - Aktif siparişleri görüntüleme ve yönetme
- 📱 **Mobil Uyumlu** - Tablet ve telefonda kullanım

## 🛠️ Teknoloji Stack

- **Frontend**: React 18 + TypeScript
- **Styling**: Tailwind CSS
- **Animasyonlar**: Framer Motion
- **Routing**: React Router DOM
- **State Management**: Zustand
- **Icons**: Lucide React
- **QR Code**: qrcode library
- **Build Tool**: Vite

## 📦 Kurulum

### Gereksinimler
- Node.js 18+ 
- npm veya yarn

### Adım Adım Kurulum

1. **Projeyi İndirin**
```bash
# Projeyi bilgisayarınıza indirin
# ZIP olarak indirip çıkarın veya git clone kullanın
```

2. **Bağımlılıkları Yükleyin**
```bash
npm install
```

3. **Geliştirme Sunucusunu Başlatın**
```bash
npm run dev
```

4. **Tarayıcıda Açın**
```
http://localhost:5173
```

## 🌐 Hosting'e Yükleme (Senkronet)

### 1. Projeyi Build Edin
```bash
npm run build
```

### 2. Senkronet Hosting Paneline Giriş
1. https://senkronet.com.tr adresine gidin
2. Hosting panelinize giriş yapın
3. Dosya Yöneticisi'ni açın

### 3. Dosyaları Yükleyin
1. `dist` klasöründeki tüm dosyaları seçin
2. Hosting'inizin `public_html` klasörüne yükleyin
3. Yükleme tamamlandığında siteniz hazır!

### 4. Domain Ayarları
- Domain'iniz otomatik olarak `public_html` klasörünü gösterecektir
- SSL sertifikası için hosting panelinden "SSL" bölümüne gidin

### 5. Veritabanı Kurulumu (Gelecek Sürümler İçin)
```sql
-- Veritabanı tabloları burada oluşturulacak
-- Şu anda localStorage kullanılıyor
```

## 🔧 Yapılandırma

### Demo Hesapları

**Admin Hesabı:**
- Email: `admin@nfcmenu.com`
- Şifre: `admin123`

**Restoran Hesabı:**
- Email: Herhangi bir email
- Şifre: Herhangi bir şifre

**Garson Hesabı:**
- Email: `garson@test.com`
- Şifre: `garson123`

### Özelleştirme

1. **Logo ve Renk Değişimi**
   - `src/pages/LandingPage.tsx` dosyasında logo ve renkleri değiştirin
   - Tailwind CSS sınıflarını kullanarak tema renklerini güncelleyin

2. **İletişim Bilgileri**
   - Footer bölümündeki iletişim bilgilerini güncelleyin
   - `src/pages/LandingPage.tsx` dosyasının alt kısmında

3. **Fiyatlandırma**
   - `src/pages/PricingPage.tsx` dosyasında plan fiyatlarını güncelleyin

## 📱 Kullanım

### Restoran Sahibi İçin
1. Siteye kayıt olun
2. İşletme bilgilerinizi girin
3. Kategoriler oluşturun
4. Menü ürünlerinizi ekleyin (görsel, açıklama, alerjen bilgileri ile)
5. Garson hesapları oluşturun
6. Masa düzenlemesi yapın
7. QR kodunuzu indirin ve masalarınıza yerleştirin
8. NFC etiketleri sipariş edin (opsiyonel)
9. Ayarlar bölümünden özellikleri aktif/pasif yapın

### Müşteri İçin
1. QR kodu okutun veya NFC etiketine dokunun
2. Kategorilere göre menüyü görüntüleyin
3. Ürün detaylarını ve alerjen bilgilerini görün
4. Garson çağırma butonunu kullanın
5. Sipariş verin (Premium özellik)

### Garson İçin
1. Garson hesabıyla giriş yapın
2. Bekleyen çağrıları görüntüleyin ve yanıtlayın
3. Masa durumlarını güncelleyin
4. Siparişleri takip edin ve tamamlayın
5. Müşteri taleplerini yönetin

### Admin İçin
1. Admin hesabıyla giriş yapın
2. Restoranları onaylayın/reddedin
3. Premium planları yönetin
4. Sistem istatistiklerini takip edin
5. Gelir analizlerini görüntüleyin
6. Platform ayarlarını düzenleyin

## 🔒 Güvenlik

- Tüm formlar doğrulama ile korunmuştur
- XSS saldırılarına karşı koruma
- Güvenli şifre gereksinimleri
- Admin paneli erişim kontrolü
- Rol tabanlı yetkilendirme sistemi

## 📊 Analiz Özellikleri

- Menü görüntülenme sayıları
- Popüler ürün analizleri
- Masa kullanım oranları
- Garson performans raporları
- Müşteri davranış raporları
- Gelir takibi (Premium)
- Şehir bazlı dağılım analizleri

## 🎨 Tasarım Özellikleri

- Mobil uyumlu responsive tasarım
- Modern ve temiz arayüz
- Kolay kullanım
- Hızlı yükleme süreleri
- Erişilebilirlik standartları
- Animasyonlu geçişler
- Kullanıcı dostu navigasyon

## 🚀 Gelecek Özellikler

- [ ] Gerçek veritabanı entegrasyonu (PostgreSQL/MySQL)
- [ ] Ödeme sistemi entegrasyonu (Stripe, PayTR)
- [ ] Mobil uygulama (React Native)
- [ ] Yemeksepeti/Trendyol entegrasyonu
- [ ] WhatsApp sipariş sistemi
- [ ] Müşteri sadakat programı
- [ ] Çoklu şube yönetimi
- [ ] Stok takip sistemi
- [ ] Muhasebe entegrasyonu
- [ ] Push notification sistemi
- [ ] Sesli sipariş alma
- [ ] AI destekli menü önerileri

## 🆘 Destek

Herhangi bir sorun yaşarsanız:

1. **Yaygın Sorunlar**
   - Sayfa yüklenmiyor: Tarayıcı önbelleğini temizleyin
   - Giriş yapamıyorum: Demo hesap bilgilerini kontrol edin
   - QR kod çalışmıyor: HTTPS bağlantısı gereklidir
   - Görsel yüklenmiyor: Dosya boyutunu kontrol edin (max 5MB)

2. **Teknik Destek**
   - GitHub Issues bölümünden sorun bildirin
   - Email: destek@nfcmenu.com
   - WhatsApp: +90 555 123 45 67

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

## 🤝 Katkıda Bulunma

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/AmazingFeature`)
3. Commit edin (`git commit -m 'Add some AmazingFeature'`)
4. Push edin (`git push origin feature/AmazingFeature`)
5. Pull Request oluşturun

## 📋 Kurulum Sonrası Yapılacaklar

### 1. Veritabanı Bağlantısı (Gelecek Sürümler)
```javascript
// .env dosyası oluşturun
DATABASE_URL=your_database_url
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_key
```

### 2. Email Servisi Kurulumu
```javascript
// Email servisi için
SMTP_HOST=your_smtp_host
SMTP_USER=your_smtp_user
SMTP_PASS=your_smtp_password
```

### 3. Dosya Yükleme Servisi
```javascript
// Cloudinary veya AWS S3 için
CLOUDINARY_URL=your_cloudinary_url
AWS_ACCESS_KEY=your_aws_key
AWS_SECRET_KEY=your_aws_secret
```

---

**NFCMenu** - Restoranınızı dijital çağa taşıyın! 🚀

### 📞 İletişim
- **Website**: nfcmenu.com
- **Email**: info@nfcmenu.com
- **Telefon**: +90 555 123 45 67
- **Adres**: İstanbul, Türkiye

### 🏆 Özellikler Özeti
✅ Kategori ve ürün yönetimi  
✅ Görsel yükleme sistemi  
✅ Garson çağırma ve yönetimi  
✅ Masa yönetimi  
✅ Sipariş takip sistemi  
✅ Admin paneli  
✅ Analiz ve raporlama  
✅ Ücretsiz/Premium plan sistemi  
✅ Mobil uyumlu tasarım  
✅ NFC ve QR kod desteği