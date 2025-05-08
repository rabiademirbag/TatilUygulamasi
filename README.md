# 🧳 C# Tatil Planlayıcı Konsol Uygulaması

Bu uygulama, kullanıcıların 3 günlük bir tatil planı yaparken konaklama ve ulaşım seçeneklerine göre toplam tatil maliyetini hesaplamalarına yardımcı olur. Konsol üzerinden etkileşimli olarak çalışır.

## 🚀 Özellikler

- **3 farklı lokasyon seçeneği**: Bodrum, Marmaris, Çeşme
- **Ulaşım türü seçimi**: Kara yolu veya hava yolu
- **Kişi sayısına göre hesaplama**
- **Geçersiz giriş kontrolü**
- **Birden fazla tatil planı yapma imkânı**

## 📍 Lokasyonlar ve Başlangıç Fiyatları

| Lokasyon | Başlangıç Paketi (3 Gün) |
|----------|---------------------------|
| Bodrum   | 4000 TL                   |
| Marmaris | 3000 TL                   |
| Çeşme    | 5000 TL                   |

## 🚗 Ulaşım Seçenekleri

| Ulaşım Türü | Kişi Başı Gidiş-Dönüş Fiyatı |
|-------------|------------------------------|
| Kara Yolu   | 1500 TL                      |
| Hava Yolu   | 4000 TL                      |

## 💡 Kullanım Senaryosu

1. Kullanıcıdan tatil yapmak istediği lokasyonu girmesi istenir.
2. Girilen lokasyon geçerli değilse, kullanıcı tekrar yönlendirilir.
3. Kaç kişilik tatil planladığı sorulur.
4. Ulaşım türü (1: Kara, 2: Hava) seçimi yapılır.
5. Toplam maliyet hesaplanarak kullanıcıya gösterilir.
6. Kullanıcıya yeni bir tatil planlamak isteyip istemediği sorulur.
7. Eğer isterse baştan başlar, istemezse uygulama “İyi günler” mesajı ile kapanır.

## ✅ Giriş Kontrolleri

- Lokasyon seçiminde büyük/küçük harf duyarlılığı yoktur.
- Geçersiz lokasyon veya ulaşım tipi girildiğinde tekrar sorulur.
- Kişi sayısı negatif girilemez.
- Kullanıcıdan “evet” ya da “hayır” dışında cevap alındığında tekrar sorulur.
