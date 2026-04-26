# AI Rock Songwriter Skill

> A copyright-safe, professional framework for producing AI-generated rock music using Suno, Udio, and similar tools.

[🇬🇧 English](#english) | [🇹🇷 Türkçe](#türkçe)

---

## English

### What is this?

`ai-rock-songwriter` is a Claude skill that turns AI music tools like Suno or Udio into a professional songwriting partner. It provides Claude with a complete framework for:

- Writing copyright-safe rock lyrics in multiple languages
- Generating Suno/Udio-ready style prompts with proper structure
- Adapting songs across languages (not just translating)
- Producing songs that sound authentic, not like AI gimmicks

### Why use it?

Most AI music outputs sound generic because the prompts are generic. This skill solves three core problems:

1. **Copyright risks:** AI tools can produce content that resembles existing artists. This skill enforces strict rules to avoid copyright issues.
2. **Generic output:** Without specific direction, AI generates forgettable music. This skill provides templates for 12+ rock subgenres with detailed era and atmosphere references.
3. **Multilingual production:** Translating songs word-for-word doesn't work. This skill teaches proper adaptation methodology.

### Features

- ✅ Copyright safety rules built into every output
- ✅ 12+ subgenre prompt templates (classic rock, grunge, doom, post-rock, etc.)
- ✅ Multilingual support (Turkish and English primary, others supported)
- ✅ Detailed song structure guidance for 4-minute commercial format
- ✅ Vocal direction templates by subgenre
- ✅ Complete production workflow from concept to upload
- ✅ Integration with Suno's Persona feature for channel consistency

### Installation

#### Option 1: Direct download

Download the `.skill` file from the latest release and add it to your Claude.ai skills.

#### Option 2: From source

Clone this repository and package the skill yourself:

```bash
git clone https://github.com/diabolikss/ai-rock-songwriter-skill.git
cd ai-rock-songwriter-skill
# Follow the packaging instructions in docs/packaging.md
```

### Usage

Once installed, the skill activates automatically when you ask Claude to help create rock music. Example prompts:

```
"Help me write a grunge ballad about lost love in Turkish"
```

```
"Create an original post-rock instrumental track inspired by 
late 1990s atmospheric guitar music"
```

```
"I want a doom metal song about isolation, with both Turkish 
and English versions"
```

The skill will guide Claude through the full process: gathering your brief, suggesting titles, writing lyrics, generating Suno-ready style prompts, and providing production tips.

### Real-World Example

This skill was originally developed for **The Riff Keeper**, a YouTube channel producing AI-generated rock music. The channel features bilingual (Turkish and English) original songs across multiple rock subgenres, all produced using the methodology in this skill.

You can see real-world output examples in the `examples/` directory of this repository.

### Supported Languages

**Primary support:** English, Turkish

**Secondary support** (with attention to AI generator compatibility): Spanish, French, German, Italian, Portuguese

Adding more languages? See `CONTRIBUTING.md`.

### Project Structure

```
ai-rock-songwriter-skill/
├── README.md               # This file
├── LICENSE                 # MIT License
├── CHANGELOG.md            # Version history
├── skill/                  # The actual skill content
│   ├── SKILL.md           # Main skill instructions
│   ├── references/        # Detailed reference documents
│   └── assets/            # Templates and tools
├── examples/              # Sample outputs
├── docs/                  # Additional documentation
└── ai-rock-songwriter.skill # Packaged skill file
```

### Credits

Created and maintained by **Diabolikss**.

This skill represents methodology developed through extensive practical use in AI music production. It's shared openly with the community to advance the craft of AI-assisted music creation.

### License

MIT License. See `LICENSE` file for details.

You're free to use, modify, and redistribute this skill. If you find it useful, a credit to Diabolikss is appreciated but not required.

### Contributing

Contributions are welcome. See `CONTRIBUTING.md` for guidelines on:

- Adding new subgenre templates
- Adding new language support
- Improving existing rules
- Sharing example outputs

### Contact

- GitHub Issues: For bugs, feature requests, and questions
- Diabolikss brand: diabolikss@gmail.com

---

## Türkçe

### Bu nedir?

`ai-rock-songwriter`, Suno veya Udio gibi yapay zeka müzik araçlarını profesyonel bir şarkı yazımı ortağına dönüştüren bir Claude skill'idir. Claude'a şu konularda kapsamlı bir çerçeve sağlar:

- Birden fazla dilde telif güvenli rock şarkı sözleri yazmak
- Doğru yapıyla Suno/Udio için hazır style prompt üretmek
- Şarkıları diller arası adapte etmek (sadece çevirmek değil)
- AI ürünü gibi değil, gerçek müzik gibi ses çıkartan şarkılar üretmek

### Neden kullanmalı?

Çoğu AI müzik çıktısı jenerik geliyor çünkü prompt'lar jenerik. Bu skill üç temel sorunu çözüyor:

1. **Telif riskleri:** AI araçları mevcut sanatçılara benzeyen içerik üretebiliyor. Bu skill telif sorunlarından kaçınmak için sıkı kurallar uyguluyor.
2. **Jenerik çıktı:** Spesifik yönlendirme olmadan AI unutulan müzikler üretiyor. Bu skill 12'den fazla rock alt türü için detaylı dönem ve atmosfer referanslarıyla şablonlar sağlıyor.
3. **Çok dilli üretim:** Şarkıları kelime kelime çevirmek işe yaramıyor. Bu skill doğru adaptasyon metodolojisini öğretiyor.

### Özellikler

- ✅ Her çıktıda yerleşik telif güvenliği kuralları
- ✅ 12'den fazla alt tür prompt şablonu (klasik rock, grunge, doom, post-rock, vb.)
- ✅ Çok dilli destek (öncelik Türkçe ve İngilizce, diğer diller destekleniyor)
- ✅ 4 dakikalık ticari format için detaylı şarkı yapısı rehberi
- ✅ Alt tür bazında vokal yönlendirme şablonları
- ✅ Konseptten yüklemeye kadar tam üretim akışı
- ✅ Kanal tutarlılığı için Suno Persona özelliğiyle entegrasyon

### Kurulum

#### Seçenek 1: Doğrudan indirme

En son sürümden `.skill` dosyasını indir ve Claude.ai skills'lerine ekle.

#### Seçenek 2: Kaynaktan

Bu repository'yi klonla ve skill'i kendin paketle:

```bash
git clone https://github.com/diabolikss/ai-rock-songwriter-skill.git
cd ai-rock-songwriter-skill
# docs/packaging.md dosyasındaki paketleme talimatlarını takip et
```

### Kullanım

Kurulduktan sonra skill, Claude'dan rock müzik üretmesini istediğinde otomatik aktive olur. Örnek prompt'lar:

```
"Türkçe olarak kayıp aşk üzerine bir grunge ballad yaz"
```

```
"1990'ların sonu atmosferik gitar müziğinden esinlenerek 
orijinal bir post-rock enstrümantal parça oluştur"
```

```
"Yalnızlık üzerine bir doom metal şarkısı istiyorum, 
hem Türkçe hem İngilizce versiyonları olsun"
```

Skill, Claude'u tüm süreç boyunca yönlendirir: brief'in alınması, başlık önerileri, söz yazımı, Suno için hazır style prompt üretimi ve üretim ipuçları.

### Gerçek Dünya Örneği

Bu skill orijinal olarak **The Riff Keeper** için geliştirildi. AI üretimi rock müzik üreten bir YouTube kanalı. Kanal, bu skill'deki metodoloji kullanılarak üretilmiş çoklu rock alt türlerinde iki dilli (Türkçe ve İngilizce) orijinal şarkılar yayınlıyor.

Gerçek dünya çıktı örneklerini bu repository'nin `examples/` dizininde görebilirsin.

### Desteklenen Diller

**Birincil destek:** İngilizce, Türkçe

**İkincil destek** (AI üretici uyumluluğuna dikkat ederek): İspanyolca, Fransızca, Almanca, İtalyanca, Portekizce

Daha fazla dil eklemek mi istiyorsun? `CONTRIBUTING.md` dosyasına bak.

### Proje Yapısı

```
ai-rock-songwriter-skill/
├── README.md               # Bu dosya
├── LICENSE                 # MIT Lisansı
├── CHANGELOG.md            # Sürüm geçmişi
├── skill/                  # Asıl skill içeriği
│   ├── SKILL.md           # Ana skill talimatları
│   ├── references/        # Detaylı referans belgeleri
│   └── assets/            # Şablonlar ve araçlar
├── examples/              # Örnek çıktılar
├── docs/                  # Ek dokümantasyon
└── ai-rock-songwriter.skill # Paketlenmiş skill dosyası
```

### Krediler

**Diabolikss** tarafından oluşturuldu ve sürdürülüyor.

Bu skill, AI müzik üretiminde kapsamlı pratik kullanım yoluyla geliştirilen metodolojiyi temsil eder. AI destekli müzik yaratma zanaatını ilerletmek için topluluğa açıkça paylaşılıyor.

### Lisans

MIT Lisansı. Detaylar için `LICENSE` dosyasına bak.

Bu skill'i kullanma, değiştirme ve yeniden dağıtma özgürlüğüne sahipsin. Faydalı bulursan Diabolikss'e atıf yapman takdir edilir ama zorunlu değildir.

### Katkıda Bulunma

Katkılar memnuniyetle karşılanır. Şunlar için yönergeler için `CONTRIBUTING.md` dosyasına bak:

- Yeni alt tür şablonları ekleme
- Yeni dil desteği ekleme
- Mevcut kuralları iyileştirme
- Örnek çıktılar paylaşma

### İletişim

- GitHub Issues: Hatalar, özellik istekleri ve sorular için
- Diabolikss markası: diabolikss@gmail.com

---

**Made with ❤️ by Diabolikss**
