---
name: profesyonel-web-tasarim
description: Profesyonel web sitesi ve web uygulaması projelerini uzman rolleriyle (ürün yöneticisi, UI/UX tasarımcı, frontend, backend, içerik yazarı, SEO uzmanı, QA) sistematik şekilde yürütür. Kullanıcı bir web sitesi, landing page, kurumsal site, web uygulaması, dashboard veya online platform yapmak/tasarlamak/geliştirmek istediğinde MUTLAKA bu skill'i kullan — "site yap", "web tasarım", "landing page", "arayüz", "frontend", "backend" gibi ifadeler geçtiğinde de, kullanıcı açıkça "profesyonel" demese bile tetiklenmeli.
---

# Profesyonel Web Tasarım

Bu skill, bir web projesini gerçek bir ajans gibi çok rollü şekilde yürütmeni sağlar. Her rolün detaylı talimatı `references/` klasöründedir. Projenin aşamasına göre ilgili rol dosyasını oku ve o rolün perspektifiyle çalış.

## Roller

| Rol | Dosya | Ne zaman |
|-----|-------|----------|
| Ürün Yöneticisi | `references/urun-yoneticisi.md` | Her projenin BAŞINDA — kapsam, hedef kitle, sayfa yapısı |
| UI/UX Tasarımcı | `references/ui-tasarim.md` | Tasarım sistemi, renk/tipografi, layout kararları |
| Frontend Geliştirici | `references/frontend.md` | HTML/CSS/JS, React, responsive kod yazarken |
| Backend Geliştirici | `references/backend.md` | API, veritabanı, auth, form işleme gerektiğinde |
| İçerik & Metin Yazarı | `references/icerik-metin.md` | Sitedeki tüm metinler — başlıklar, CTA'lar, açıklamalar |
| SEO & Performans | `references/seo-performans.md` | Meta etiketler, semantik yapı, hız optimizasyonu |
| QA & Test | `references/qa-test.md` | Teslimden ÖNCE — son kontrol listesi |

## İş Akışı

Aşamaları sırayla uygula. Basit projelerde (tek sayfalık landing page) aşamaları hızlı geç ama hiçbirini atlama.

### 1. Keşif — Ürün Yöneticisi şapkası
`references/urun-yoneticisi.md` dosyasını oku. Kullanıcının isteğinden proje özetini çıkar: hedef, hedef kitle, sayfa listesi, ana özellikler. Kullanıcı detay vermediyse sektöre uygun mantıklı varsayımlar yap ve bunları kısa bir "Proje Özeti" olarak yaz — uzun soru listesiyle kullanıcıyı yorma. Kritik belirsizlik varsa (örn. e-ticaret mi tanıtım sitesi mi) TEK soru sor.

### 2. Tasarım Sistemi — UI/UX Tasarımcı şapkası
`references/ui-tasarim.md` dosyasını oku. Renk paleti, tipografi, spacing sistemi ve genel görsel yön kararlarını ver. Şablonvari, jenerik görünümden kaçın.

### 3. İçerik — Metin Yazarı şapkası
`references/icerik-metin.md` dosyasını oku. Lorem ipsum ASLA kullanma — sektöre ve markaya uygun gerçekçi Türkçe (veya kullanıcının istediği dilde) metinler yaz.

### 4. Geliştirme — Frontend (+ gerekiyorsa Backend) şapkası
`references/frontend.md` dosyasını oku ve kodu yaz. Dinamik özellik (form kaydı, üyelik, veritabanı) gerekiyorsa `references/backend.md` dosyasını da oku.

### 5. SEO & Performans
`references/seo-performans.md` dosyasını oku ve kodu bu kriterlere göre gözden geçir.

### 6. Kalite Kontrol — QA şapkası
`references/qa-test.md` dosyasındaki kontrol listesini uygula. Sorunları düzeltmeden teslim etme.

### 7. Teslimat
Dosyaları `/mnt/user-data/outputs/` içine kaydet ve kullanıcıya sun. Kısa bir teslim notu yaz: ne yapıldı, hangi kararlar alındı, sonraki adım önerileri (3-4 cümle, uzun rapor yazma).

## Genel Kurallar

- Kullanıcıyla Türkçe konuş (aksi istenmedikçe).
- Hızlı ve üretim odaklı ol: uzun açıklama yerine çalışan, kaliteli çıktı.
- Tek sayfalık işlerde tek HTML dosyası (CSS/JS gömülü) yeterli; çok sayfalı projelerde düzenli klasör yapısı kur.
- Her rol geçişini kullanıcıya ilan etme — bu iç süreçtir. Sadece sonucu ve önemli kararları paylaş.
- Kullanıcının mevcut markası varsa (logo, renk, kurumsal kimlik) onu temel al; yoksa markaya uygun yeni kimlik öner.
