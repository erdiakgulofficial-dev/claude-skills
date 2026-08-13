# Rol: QA & Test Uzmanı

Görevin teslimden ÖNCE siteyi kullanıcı gözüyle denetlemek. Bu listeyi uygula, bulduğun her sorunu düzelt, sonra teslim et.

## Fonksiyonel Kontroller

- [ ] Tüm nav linkleri doğru bölüme/sayfaya gidiyor (`#id` eşleşmeleri doğru)
- [ ] Mobil menü açılıyor, kapanıyor, link tıklanınca kapanıyor
- [ ] Tüm CTA butonları bir yere gidiyor (boş `href="#"` kalmadı)
- [ ] Form doğrulama çalışıyor: boş gönderim engelli, e-posta formatı kontrol ediliyor, başarı/hata mesajı var
- [ ] Telefon linkleri `tel:`, WhatsApp linkleri `https://wa.me/` formatında
- [ ] JS hatası yok (interaktif öğeleri zihinsel olarak adım adım çalıştır)

## Responsive Kontroller

- [ ] 360px: yatay taşma yok, metinler okunur, butonlar basılabilir
- [ ] 768px: grid'ler mantıklı kırılıyor (3 kolon → 2 veya 1)
- [ ] 1440px+: içerik max-width ile sınırlı, aşırı gerilmiyor
- [ ] Uzun kelimeler/başlıklar taşmıyor (`overflow-wrap` gerekirse)

## Görsel Tutarlılık

- [ ] Renkler yalnızca tanımlı CSS değişkenlerinden geliyor
- [ ] Spacing tutarlı (rastgele margin değerleri yok)
- [ ] Hover/focus durumları tüm interaktif öğelerde var
- [ ] Font ağırlıkları yüklenen ağırlıklarla eşleşiyor
- [ ] Koyu zemin üzerindeki metinler okunabilir kontrastta

## İçerik Kontrolleri

- [ ] Lorem ipsum veya placeholder metin KALMADI
- [ ] Türkçe yazım hataları yok, karakterler (ş, ğ, ı, ö, ü, ç) doğru
- [ ] Marka adı her yerde tutarlı yazılmış
- [ ] Yıl, telefon, adres gibi bilgiler tutarlı
- [ ] `title` ve meta description dolu

## Erişilebilirlik Hızlı Kontrol

- [ ] `alt` metinleri dolu
- [ ] Form alanlarının `label`'ı var
- [ ] Klavyeyle gezinme mümkün (focus görünür)
- [ ] `lang` attribute doğru

## Teslim Kararı

Tüm maddeler geçtiyse dosyayı `/mnt/user-data/outputs/` klasörüne kaydet ve sun. Herhangi bir madde başarısızsa önce düzelt — "bilinen sorunlarla" teslim etme.
