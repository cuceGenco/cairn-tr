---
layout: default
title: Adventure Conversions
nav_order: 3
parent: Submissions
---

# Macera Dönüşümleri

- Cairn web sitesine bir macera gönderirken aşağıdaki şablonu kopyalayın.
- Dönüşüm metni için lütfen [Stil Kılavuzu](/submissions/style-guide)'nu takip edin.
- Dosya [Markdown](/submissions/submission-guide/#markdown) biçiminde yazılmalıdır. Dosya adı küçük harfli olmalı ve *.md sonekini kullanmalıdır (örnek: cool-adventure.md).
- Dosyanın en üstüne "front matter" (başlangıçta `---` ile başlayan kısımlar) eklediğinizden emin olun, aksi halde gönderim çalışmaz. Bir örnek için [buraya](/adventures/conversions/stellarium-of-the-vinteralf) bakın (ham metin [burada](https://github.com/yochaigal/cairn/blob/main/adventures/conversions/stellarium-of-the-vinteralf.md)).
- Macera gönderimleri _her zaman_ eserin _yazarının yanı sıra_ eseri dönüştüren kişinin adını da belirtmelidir.
- Lütfen yazarın yanı sıra maceraya ve (isterseniz) kendi web sitenize veya iletişim bilgilerinize bağlantı verin.
- Mümkünse, yazardan izin isteyin. Değilse, sorun yok! Genellikle buna ihtiyacımız yok, ancak iznin olması harika.

## Gönderim Şablonu


```
---
layout: default
parent: Conversions
grand_parent: Adventures
title: Adventure Title
nav_exclude: true
search_exclude: true
---

# Macera Başlığı

- [Yazar Adı](yazar-sitesine-bağlantı) tarafından yazılan [orijinal esere](oyun-sayfasına-bağlantı) dayanmaktadır.
- [Sizin Adınız](web üzerinde iletişim bağlantınız) tarafından dönüştürülmüştür.

## Genel Notlar
- Dönüşümle ilgili notları buraya ekleyin!
- Canavarları ve NPC'leri ayrı ayrı veya bulundukları konuma göre listeleyebilirsiniz.

## Canavarlar veya NPC'ler

### Canavar Adı
Canavar 1
- Canavar özelliği (kritik hasar, yetenekler)
- Daha fazla canavar özelliği vb.

## Konumlar
### Konum A
#### Tuhaf şey 1
- Tuhaf şey 1 hakkında notlar


```

Not: Ön Bölüm'deki "nav_exclude" ve "search_exclude" yönergeleri yalnızca hazırlık aşaması içindir; dönüşüm "tam"landığında kaldırılabilirler.