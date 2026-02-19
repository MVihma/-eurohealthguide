# EuroHealthGuide 🏥

> AI-powered medical information app for the European market — built on EMA & ECDC guidelines.

![License](https://img.shields.io/badge/license-proprietary-blue)
![Languages](https://img.shields.io/badge/languages-8-green)
![GDPR](https://img.shields.io/badge/GDPR-compliant-brightgreen)
![EU AI Act](https://img.shields.io/badge/EU%20AI%20Act-aligned-blue)
![MDR](https://img.shields.io/badge/MDR%202017%2F745-considered-orange)

---

## What is EuroHealthGuide?

**EuroHealthGuide** is an AI-driven medical information assistant designed exclusively for European users. Unlike generic health chatbots trained on American data, EuroHealthGuide is built from the ground up with European clinical standards, regulations, and languages in mind.

Powered by **DeepSeek AI**, the app delivers reliable health guidance based on official European sources — EMA, ECDC, WHO-Europe, and national medicines agencies — in 8 EU languages.

> ⚠️ EuroHealthGuide is an information service. It is **not** a replacement for professional medical care. Always consult a licensed healthcare professional for personal medical advice.

---

## Features

- 🤖 **AI-powered chat** — Conversational medical Q&A powered by DeepSeek
- 🇪🇺 **European guidelines** — All responses based on EMA, ECDC & national health authorities
- 🌍 **8 EU languages** — Swedish, English, German, French, Spanish, Italian, Polish, Dutch
- 🚨 **Emergency protocol** — Detects acute keywords and instantly shows 112 + national helpline
- 🔒 **GDPR-aligned** — Privacy by Design, no PII stored, session-only data
- 💊 **Generic drug names** — Uses INN names, not brand names
- 📏 **Metric units** — kg, cm, °C throughout — never lbs, inches or °F
- 📚 **Source transparency** — Every response links to European medical sources
- ✅ **Confidence indicator** — Each answer shows AI confidence level
- 📱 **Mobile-first design** — Optimised for smartphone use

---

## Supported Languages

| Language | Code | Emergency Number |
|----------|------|-----------------|
| Svenska | `sv` | 112 + 1177 |
| English | `en` | 112 + 111 (NHS) |
| Deutsch | `de` | 112 + 116117 |
| Français | `fr` | 112 + 15 (SAMU) |
| Español | `es` | 112 + 061 |
| Italiano | `it` | 112 + 118 |
| Polski | `pl` | 112 + 999 |
| Nederlands | `nl` | 112 + 0900-8844 |

---

## Medical Sources

EuroHealthGuide bases all responses exclusively on European medical authorities:

- [EMA — European Medicines Agency](https://www.ema.europa.eu)
- [ECDC — European Centre for Disease Prevention and Control](https://www.ecdc.europa.eu)
- [WHO Europe](https://www.who.int/europe)
- [Läkemedelsverket — Swedish Medical Products Agency](https://www.lakemedelsverket.se)
- [Socialstyrelsen — Swedish National Board of Health](https://www.socialstyrelsen.se)
- [1177 Vårdguiden — Swedish Healthcare Guide](https://www.1177.se)

---

## Tech Stack

| Component | Technology |
|-----------|-----------|
| Frontend | Vanilla HTML, CSS, JavaScript |
| AI Engine | DeepSeek API (`deepseek-chat`) |
| Fonts | Instrument Serif + Geist (Google Fonts) |
| Hosting | GitHub Pages / Netlify |
| Design | Mobile-first, phone-frame UI |

---

## Getting Started

### Option 1 — Open directly
Download `index.html` and open it in any modern browser. Enter your DeepSeek API key when prompted.

### Option 2 — Host on GitHub Pages
1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your app will be live at `https://yourusername.github.io/eurohealthguide`

### Option 3 — Host on Netlify
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop `index.html` into the deploy area
3. Done — your app is live instantly

### API Key
You need a [DeepSeek API key](https://platform.deepseek.com) to use the app. The key is entered at runtime and never stored permanently.

---

## Regulatory Considerations

EuroHealthGuide has been designed with the following European regulations in mind:

| Regulation | Status |
|-----------|--------|
| GDPR (2016/679) | ✅ Privacy by Design architecture |
| EU AI Act | ✅ Transparency & human oversight built-in |
| MDR 2017/745 | ⚠️ Formal classification assessment required before commercial launch |
| EU AI Liability Directive | ⚠️ Legal review recommended |

> A full technical specification and compliance document is available separately.

---

## Roadmap

- [ ] Fine-tuning on OpenMed/Medical-Reasoning-SFT-Mega dataset (1.79M samples)
- [ ] RLHF with European licensed healthcare professionals
- [ ] Native iOS & Android app (via Capacitor)
- [ ] Offline mode for basic symptom information
- [ ] Integration with national health record systems
- [ ] Voice input support
- [ ] Additional EU languages (PT, RO, HU, FI, DA, EL)

---

## Contributing

Contributions are welcome, especially from:
- Licensed European healthcare professionals (medical review)
- Native speakers of supported languages (translation review)
- EU regulatory experts (MDR/AI Act compliance)

Please open an issue before submitting a pull request.

---

## Disclaimer

EuroHealthGuide provides general health information only. It does **not**:
- Diagnose medical conditions
- Replace professional medical advice
- Prescribe medications or treatments

In case of a medical emergency, **call 112 immediately**.

---

## License

Proprietary — All rights reserved.
Commercial use, redistribution or modification requires written permission.

---

EuroHealthGuide · Est. 2026 by Mickael Vihma
