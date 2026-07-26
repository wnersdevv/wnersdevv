<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=WnersCode%20Ticket%20Bot&fontSize=40&fontColor=ffffff&animation=fadeIn" width="100%"/>

# 🎫 Aşırı Gelişmiş Ticket Bot

**MongoDB destekli, Discord Components V2 ile zenginleştirilmiş, uçtan uca otomatik destek talebi altyapısı**

[![Node.js](https://img.shields.io/badge/Node.js-18%2B-3C873A?logo=node.js&logoColor=white&style=for-the-badge)](https://nodejs.org)
[![discord.js](https://img.shields.io/badge/discord.js-v14.19%2B-5865F2?logo=discord&logoColor=white&style=for-the-badge)](https://discord.js.org)
[![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-47A248?logo=mongodb&logoColor=white&style=for-the-badge)](https://www.mongodb.com/atlas)
[![Components V2](https://img.shields.io/badge/Discord-Components%20V2-EB459E?logo=discord&logoColor=white&style=for-the-badge)]()
[![License](https://img.shields.io/badge/Lisans-MIT-F2C744?style=for-the-badge)](LICENSE)

![Kategori](https://img.shields.io/badge/Kategori-6-blue?style=flat-square)
![Buton](https://img.shields.io/badge/Ticket%20Butonu-7-orange?style=flat-square)
![Komut](https://img.shields.io/badge/Slash%20Komut-11-9cf?style=flat-square)
![Otomatik%20Kapanma](https://img.shields.io/badge/Otomatik%20Kapanma-Aktif-success?style=flat-square)
![Dil](https://img.shields.io/badge/Dil-TR%20%7C%20EN-lightgrey?style=flat-square)

</div>

---

## 📋 İçindekiler

- [Hakkında](#-hakkında)
- [Öne Çıkan Özellikler](#-öne-çıkan-özellikler)
- [Gereksinimler](#️-gereksinimler)
- [Kurulum](#-kurulum)
- [Komutlar](#️-komutlar)
- [Ticket Kanalı Butonları](#-ticket-kanalı-butonları)
- [Ticket Akışı Nasıl Çalışır?](#-ticket-akışı-nasıl-çalışır)
- [Yapılandırma](#️-yapılandırma)
- [Destek](#-destek)

---

## 💡 Hakkında

Bu bot, sunucunuzun destek talebi (ticket) sürecini **komple otomatikleştirmek** için sıfırdan tasarlandı. Klasik "tek kanal, tek buton" ticket botlarının aksine; **çoklu kategori, dinamik form, öncelik seviyesi, otomatik kapanma ve tam istatistik takibi** gibi kurumsal seviyede özellikler barındırır.

Arayüzün tamamı Discord'un en yeni **Components V2** teknolojisiyle inşa edildi — panelden loglara, karşılama mesajından yönetici panosuna kadar her şey modern, düzenli ve okunaklı kartlar halinde sunulur.

> ⚡ Kur, kategorileri tanımla, arkana yaslan — gerisini bot halleder.

<img src="https://capsule-render.vercel.app/api?type=rect&color=5865F2&height=3&width=100%" width="100%"/>

## ✨ Öne Çıkan Özellikler

### 🗂️ ![Kategori](https://img.shields.io/badge/-Çoklu%20Kategori-5865F2?style=flat-square&logoColor=white) Çoklu Kategori Sistemi
Tek panelden **6 farklı destek kategorisi**: Genel Destek, Teknik Destek, Şikayet, Soru & Bilgi, Satın Alma & Ödeme, Öneri & Geri Bildirim. Her kategori kendi **destek rolüne** ve kendi **form sorularına** sahip olabilir.

### 📝 ![Form](https://img.shields.io/badge/-Dinamik%20Form-57F287?style=flat-square&logoColor=white) Dinamik Form Sistemi
Kullanıcı bir kategori seçtiğinde, o kategoriye özel hazırlanmış bir **modal form** açılır. Verilen cevaplar otomatik olarak ticket kanalına işlenir — yetkililer konuya hiçbir şey sormadan hâkim olur.

### 🎛️ ![Panel](https://img.shields.io/badge/-Tam%20Donanım-FEE75C?style=flat-square&logoColor=black) Tam Donanımlı Ticket Paneli
Her ticket kanalında hazır butonlar: **Üstlen · Kullanıcı Ekle · Yetkilileri Çağır · Transkript Oluştur · Öncelik Ayarla · Kullanıcı Çıkar · Ticket'ı Sonlandır.**

### ⏰ ![Otomatik](https://img.shields.io/badge/-Otomatik%20Kapanma-ED4245?style=flat-square&logoColor=white) Akıllı Otomatik Kapanma
Yapılandırılabilir süre boyunca (varsayılan **5 saat**) mesajlaşma olmayan ticketlar otomatik olarak kapanır, transkripti çıkarılır, log kanalına işlenir ve **ticket'ı açan kullanıcıya DM ile transkript gönderilir**.

### 📄 ![Transkript](https://img.shields.io/badge/-Transkript-EB459E?style=flat-square&logoColor=white) Otomatik Transkript
Her kapanışta (manuel veya otomatik) konuşmanın tam HTML transkripti oluşturulur ve arşiv kanalına yüklenir.

### 🚦 ![Öncelik](https://img.shields.io/badge/-Öncelik%20Sistemi-F2C744?style=flat-square&logoColor=black) Öncelik Sistemi
Ticketlara 🟩 Düşük / 🟨 Orta / 🟥 Yüksek öncelik atanabilir, değişiklikler kanala ve loglara otomatik yansır.

### 📊 ![Dashboard](https://img.shields.io/badge/-Denetim%20Masası-3C873A?style=flat-square&logoColor=white) Gelişmiş İstatistik & Denetim Masası
`/istatistik` ile sunucu bazlı ticket verileri; `/denetim-masasi` ile **geliştiriciye özel** genel bot sağlık paneli — kaç sunucuda çalışıyor, toplam komut kullanımı, en çok kullanılan komutlar, en aktif kullanıcılar.

### 🏆 ![Sıralama](https://img.shields.io/badge/-Yetkili%20Sıralaması-9B59B6?style=flat-square&logoColor=white) Yetkili Sıralaması
`/ticket sirala` ile en çok ticket kapatan/üstlenen yetkililerin liderlik tablosu.

### 🎨 ![ComponentsV2](https://img.shields.io/badge/-Components%20V2-5865F2?style=flat-square&logoColor=white) Components V2 Arayüz
Panel, karşılama mesajı, loglar ve denetim masası — hepsi eski embed sistemine değil, Discord'un yeni nesil **Container/TextDisplay** bileşen mimarisine göre tasarlandı.

### 🔊 ![Ses](https://img.shields.io/badge/-7%2F24%20Ses%20Kanalı-1ABC9C?style=flat-square&logoColor=white) 7/24 Ses Kanalı Bağlantısı
İsteğe bağlı olarak bot, belirlediğin bir ses kanalına otomatik katılıp bağlantı koptuğunda kendini toparlayarak 7/24 orada kalabilir.

### 🌍 ![Dil](https://img.shields.io/badge/-Çoklu%20Dil-95A5A6?style=flat-square&logoColor=white) Çoklu Dil Desteği
Türkçe ve İngilizce dil dosyaları hazır altyapıda mevcuttur, kolayca genişletilebilir.

<img src="https://capsule-render.vercel.app/api?type=rect&color=57F287&height=3&width=100%" width="100%"/>

## 🛠️ Gereksinimler

| Gereksinim | Minimum Sürüm | İndirme |
|:---:|:---:|:---:|
| ![Node](https://img.shields.io/badge/Node.js-000?logo=node.js) | `v18.0.0+` | [nodejs.org](https://nodejs.org) |
| ![npm](https://img.shields.io/badge/npm-CB3837?logo=npm&logoColor=white) | `v8.0.0+` | Node.js ile gelir |
| ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) | Atlas / yerel | [mongodb.com/atlas](https://www.mongodb.com/atlas) |
| ![Discord](https://img.shields.io/badge/Discord-5865F2?logo=discord&logoColor=white) | Bot Token | [Discord Developer Portal](https://discord.com/developers/applications) |

---

## 📦 Kurulum

### 1️⃣ Bağımlılıkları yükleyin
```bash
npm install
```

### 2️⃣ `ayarlar.json` dosyasını doldurun
```json
{
  "token": "BOT_TOKEN_BURAYA",
  "clientId": "BOT_CLIENT_ID",
  "mongoUri": "mongodb+srv://kullanici:sifre@cluster.mongodb.net/ticketbot",
  "ownerId": "SENIN_DISCORD_ID_IN"
}
```

> 🔴 **Uyarı:** Token ve MongoDB bağlantı bilgini asla kimseyle paylaşma, `.gitignore` dosyasına eklemeyi unutma!

### 3️⃣ Slash komutlarını Discord'a kaydet
```bash
npm run deploy-commands
```

### 4️⃣ Botu başlat
```bash
npm start
```

🟢 Konsolda MongoDB bağlantısının başarılı olduğunu ve komutların yüklendiğini gördüysen kurulum tamamdır.

### 5️⃣ Ticket sistemini kur
Discord'da yetkili olduğun bir sunucuda:
```
/ticket sistemi-kur
```
Panel kanalı, ticket kategorisi, log kanalı ve destek rolünü seç — istersen her departman için (teknik, şikayet, soru, ödeme, öneri) ayrı rol de atayabilirsin.

<img src="https://capsule-render.vercel.app/api?type=rect&color=FEE75C&height=3&width=100%" width="100%"/>

## ⌨️ Komutlar

| Komut | Yetki | Açıklama |
|-------|:---:|----------|
| `/ticket sistemi-kur` | 🔵 Yönetici | Ticket sistemini kurar: panel, kategori, log kanalı, roller, otomatik kapanma süresi |
| `/ticket sifirla` | 🔵 Yönetici | Sunucudaki ticket sistemini tamamen sıfırlar |
| `/ticket goster` | 🔵 Yönetici | Mevcut ticket sistemi ayarlarını gösterir |
| `/ticket sirala` | 🟢 Herkes | Yetkilileri kapattıkları ticket sayısına göre sıralar |
| `/ticket loglar` | 🔵 Yönetici | Son kapatılan ticketların özet loglarını listeler |
| `/istatistik` | 🟢 Herkes | Sunucunun genel ticket istatistiklerini gösterir |
| `/denetim-masasi` | 🔴 Geliştirici | Botun kaç sunucuda çalıştığı, toplam komut kullanımı, en çok kullanılan komutlar ve en aktif kullanıcılar |
| `/yardım` | 🟢 Herkes | Kullanılabilir tüm komutları listeler |
| `/ping` | 🟢 Herkes | Botun ve veritabanının çalışıp çalışmadığını kontrol eder |
| `/davet` | 🟢 Herkes | Botu kendi sunucuna davet etmen için bağlantı verir |
| `/developer` | 🟢 Herkes | Botun geliştiricisi hakkında bilgi verir |

<img src="https://capsule-render.vercel.app/api?type=rect&color=ED4245&height=3&width=100%" width="100%"/>

## 🎛️ Ticket Kanalı Butonları

Her açılan ticket kanalında otomatik olarak şu butonlar yer alır:

| Buton | Renk | İşlev |
|-------|:---:|-------|
| 🙋 **Üstlen** | 🔵 Mavi | Ticket'ı bir yetkilinin adına atar |
| 👤 **Kullanıcı Ekle** | ⚪ Gri | Kanala ek bir kullanıcı davet eder (kullanıcı seçim menüsü ile) |
| ⚠️ **Yetkilileri Çağır** | ⚪ Gri | Kategoriye tanımlı destek rolünü kanalda etiketler |
| 📄 **Transkript Oluştur** | ⚪ Gri | Kanalı kapatmadan anlık HTML transkript üretir |
| 🟨 **Öncelik Ayarla** | ⚪ Gri | Ticket'a Düşük / Orta / Yüksek öncelik atar |
| 🔓 **Kullanıcı Çıkar** | ⚪ Gri | Sonradan eklenmiş bir kullanıcıyı kanaldan çıkarır |
| 🔴 **Ticket'ı Sonlandır** | 🔴 Kırmızı | Onay alarak ticket'ı kapatır, transkript çıkarır, kanalı siler |

<img src="https://capsule-render.vercel.app/api?type=rect&color=EB459E&height=3&width=100%" width="100%"/>

## 🔄 Ticket Akışı Nasıl Çalışır?

```mermaid
graph TD
    A[👤 Kullanıcı panelden kategori seçer] --> B{Form var mı?}
    B -- Evet --> C[📝 Modal form dolduruluyor]
    B -- Hayır --> D[📂 Ticket kanalı oluşur]
    C --> D
    D --> E[🙋 Yetkili üstlenir / öncelik atar]
    E --> F{Kapatıldı mı?}
    F -- Manuel --> G[📄 Transkript + Log]
    F -- 5 saat sessizlik --> H[⏰ Otomatik kapanır]
    H --> G
    H --> I[📩 Ticket sahibine DM]
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=1ABC9C&height=3&width=100%" width="100%"/>

## ⚙️ Yapılandırma

Tüm temel ayarlar `ayarlar.json` dosyasından yönetilir:

| Alan | Açıklama |
|------|----------|
| `token` | Discord bot token'ın |
| `clientId` | Botunun uygulama ID'si |
| `mongoUri` | MongoDB bağlantı string'i (`mongodb://` veya `mongodb+srv://`) |
| `ownerId` | `/denetim-masasi` komutunu kullanabilecek geliştirici ID'si |
| `dil` | Varsayılan dil (`tr` / `en`) |
| `renkler` | Embed/panel renk paleti |
| `botAyarlari.sesKanali` | 7/24 ses kanalı bağlantısı ayarları |

Sunucuya özel ayarlar (kategoriler, roller, otomatik kapanma süresi, maksimum ticket sayısı vb.) `/ticket sistemi-kur` komutuyla veritabanına kaydedilir, dosya düzenlemeye gerek yoktur.

---

## 🆘 Destek

Bir sorunla karşılaştıysan:

1. ✅ `ayarlar.json` dosyasındaki tüm alanları doğru doldurduğundan emin ol
2. ✅ Node.js sürümünün **v18+** olduğunu kontrol et
3. ✅ MongoDB bağlantısının kurulduğunu konsoldan doğrula (`🟢 MongoDB bağlantısı başarılı!`)
4. ✅ `npm run deploy-commands` komutunu çalıştırdığından emin ol

---

<div align="center">

**WnersCode ekosistemi için geliştirildi ⚡**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
