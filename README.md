# Erdi Skills — Claude Code Skill Marketplace

Claude Code için özel skill koleksiyonu.

## Kurulum

Claude Code içinde şu komutları çalıştırın:

```
/plugin marketplace add erdiakgul/claude-skills
/plugin install profesyonel-web-tasarim@erdi-skills
```

> Not: `erdiakgul/claude-skills` kısmını kendi GitHub kullanıcı adınız/repo adınızla değiştirin.

Kurulumdan sonra Claude Code'u yeniden başlatın (`/exit` yazıp tekrar açın).

## İçerik

### profesyonel-web-tasarim

Web sitesi ve web uygulaması projelerini 7 uzman rolüyle sistematik yürütür:

- **Ürün Yöneticisi** — kapsam, sayfa haritası, dönüşüm hedefi
- **UI/UX Tasarımcı** — tasarım sistemi, jenerik görünümden kaçınma
- **Frontend** — responsive, temiz kod standartları
- **Backend** — gerektiğinde; önce "backend'siz çözülür mü?" kontrolü
- **İçerik & Metin** — gerçek Türkçe metinler, lorem ipsum yasak
- **SEO & Performans** — meta etiketler, yerel SEO, hız
- **QA & Test** — teslim öncesi kontrol listesi

"Site yap", "landing page", "web tasarım" gibi isteklerde otomatik tetiklenir.

## Yeni Skill Ekleme

1. Repo köküne yeni bir klasör ekleyin (içinde `SKILL.md` olmalı)
2. `.claude-plugin/marketplace.json` dosyasındaki `plugins` listesine yeni bir kayıt ekleyin
3. Değişiklikleri push edin — kullanıcılar `/plugin marketplace update erdi-skills` ile güncel halini alır
