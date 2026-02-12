# مدرب التجويد - رواية ورش عن نافع
# Warsh Tajweed Trainer

A web-based tajweed training app for **Warsh recitation** (رواية ورش عن نافع), serving learners in North Africa, West Africa, and the Maghreb.

![Warsh Tajweed Trainer](https://img.shields.io/badge/Riwaya-Warsh-orange)
![License](https://img.shields.io/badge/license-MIT-blue)
![No Build](https://img.shields.io/badge/build-none_required-green)

## Features

- 📖 **Authentic Warsh Text** — From King Fahd Quran Complex (KFGQPC)
- 🎨 **11 Tajweed Rules** — Color-coded with custom detection engine
- 🎧 **Warsh Reciters** — Ibrahim Al-Dosary, Yassin Al-Jazaery
- 🎙️ **Self-Recording** — Record and playback your recitation
- 📱 **Mobile-First** — Works on phones, tablets, desktops
- 🌐 **Fully Offline** — Single HTML file, no server needed
- 🔤 **RTL Arabic UI** — Native interface for Arabic speakers

## Warsh-Specific Rules Detected

| Rule | Arabic | Color | Description |
|------|--------|-------|-------------|
| Naql | نقل | Cyan | Vowel transfer from hamza wasl |
| Taqlil | تقليل | Orange | Alif tilted toward ya sound |
| Tashil | تسهيل | Purple | Softened second hamza |
| Ibdal | إبدال | Pink | Hamza replaced with madd letter |
| Tarqiq Ra | ترقيق الراء | Sky Blue | Light Ra after kasra |
| Madd Badal | مد البدل | Red | 2/4/6 counts flexibility |
| Madd 6 | مد 6 حركات | Dark Red | Extended madd (obligatory 6) |
| Ghunnah | غنة | Green | Nasalization (2 counts) |
| Qalqalah | قلقلة | Blue | Echo on قطبجد |
| Tafkheem | تفخيم | Dark Blue | Heavy letters خصضغطقظ |
| Silent | صامت | Gray | Unpronounced letters |

## Quick Start

1. Download `index.html`
2. Open in any browser
3. Select surah and ayah range
4. Click "تحميل النص والتجويد"
5. Listen, practice, record!

Or use GitHub Pages: `https://[username].github.io/warsh-tajweed-trainer/`

## Data Sources

| Resource | Source | License |
|----------|--------|---------|
| Warsh Text | [fawazahmed0/quran-api](https://github.com/fawazahmed0/quran-api) → KFGQPC | CC BY 3.0 |
| Warsh Font | [KFGQPC](https://fonts.qurancomplex.gov.sa/) | Free for Quran apps |
| Audio | [everyayah.com](https://everyayah.com/) | Free for personal use |

## Technical Details

- **Zero build process** — Pure HTML + React (CDN) + Tailwind (CDN)
- **No backend** — All APIs are public CDNs
- **LocalStorage** — Settings and recordings persist locally
- **Custom Engine** — Pattern-based tajweed detection for Warsh

## Why Warsh?

Warsh (ورش) is the recitation of **Uthman ibn Said al-Misri**, transmitted from **Nafi' al-Madani**. It's the dominant recitation in:

- 🇲🇦 Morocco
- 🇩🇿 Algeria  
- 🇹🇳 Tunisia
- 🇱🇾 Libya
- 🇲🇷 Mauritania
- 🇸🇳 Senegal
- 🇲🇱 Mali
- 🇳🇬 Northern Nigeria
- Parts of Sudan and Chad

Key differences from Hafs include **naql** (نقل), **taqlil** (تقليل), **ibdal** (إبدال), and extended madd rules.

## Contributing

Contributions welcome, especially:

- [ ] Expanded taqlil word list
- [ ] More precise naql detection
- [ ] Tashil patterns for همزتين
- [ ] Additional Warsh reciters
- [ ] Translations (French, Wolof, Hausa)

## License

MIT License — Free for personal and commercial use.

**Important:** The Quranic text itself is from KFGQPC under CC BY 3.0. Modifications to the sacred text are not permitted per Islamic scholarly consensus and the source license.

## Acknowledgments

- King Fahd Glorious Quran Printing Complex (مجمع الملك فهد)
- [fawazahmed0](https://github.com/fawazahmed0) for the Quran API
- [everyayah.com](https://everyayah.com) for audio files
- Scholars of Warsh recitation worldwide

---

<div align="center">

**بسم الله الرحمن الرحيم**

Made with ❤️ for the Ummah

</div>
