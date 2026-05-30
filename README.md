# Emebala E-Book Viewer

🌐 **Website**: [https://emebala.vercel.app/](https://emebala.vercel.app/)
💬 **Reddit**: [r/emebala](https://www.reddit.com/r/emebala/)
🐙 **GitHub**: [teamsunplaza/emebala](https://github.com/teamsunplaza/emebala)
🤝 **Sponsor**: [teamsunplaza.gumroad.com/l/emebala](https://teamsunplaza.gumroad.com/l/emebala)

---

## 📥 Download

### Option 1: wAI Installer (Model Included) — Cloudflare R2

[**Emebala_v0.10.0_wAI_Setup.exe** (2.54 GB)](https://pub-9e1fd15dbb4e489c8010bb5617dbe4fb.r2.dev/v0.10.0/Emebala_v0.10.0_wAI_Setup.exe)

> ✅ AI translation model (HY-MT1.5-1.8B) built-in. No additional download required.
> Inno Setup installer — works on Windows 10/11 64-bit.

### Option 2: Lightweight Installer (Model Separate) — GitHub Releases

| File | Size | Description |
|------|:---:|------|
| [**Emebala_v0.10.0_Setup.exe**](https://github.com/teamsunplaza/emebala/releases/download/v0.10.0/Emebala.Setup.0.10.0.exe) | 433 MB | App installer (NSIS) |
| [**hy-mt1.5-1.8b.gguf**](https://github.com/teamsunplaza/emebala/releases/download/v0.10.0/hy-mt1.5-1.8b.gguf) | 1.13 GB | AI translation model (download separately) |
| [**samplebooks.zip**](https://github.com/teamsunplaza/emebala/releases/download/v0.10.0/samplebooks.zip) | 6.0 MB | Sample EPUB/PDF books for testing |
| [**emebala_manual_en.pdf**](https://github.com/teamsunplaza/emebala/releases/download/v0.10.0/emebala_manual_en.pdf) | 4.1 MB | English user manual |
| [**emebala_manual_kr.pdf**](https://github.com/teamsunplaza/emebala/releases/download/v0.10.0/emebala_manual_kr.pdf) | 5.4 MB | Korean user manual |
| [**Things_you_must_know.txt**](https://github.com/teamsunplaza/emebala/releases/download/v0.10.0/Things_you_must_know.txt) | 51 KB | Model setup guide in 38 languages |

> ℹ️ After installing, place `hy-mt1.5-1.8b.gguf` in `[App folder]\resources\models\` or `%APPDATA%\Emebala\models\`.

---

📜 **The Genesis: Why "Eme-bala"?**

"Eme-bala" is an ancient Mesopotamian term signifying humanity's earliest translators and interpreters. They were the key intellectuals who transmitted information and bridged the gap of human knowledge across civilizations.

Though history rarely remembers these individuals, the modern world exists because of them. If the mathematical insights of Mesopotamia had never reached Greece, Pythagoras might never have emerged. What would our world look like if the capitalist concepts of Assyria or the statecraft expertise of Persia had never been transmitted across borders?

On a deeply personal note, if I hadn't been able to read the poems of Goethe and Heinrich Heine through someone else's dedicated translation, I would never have met my wife. Knowledge transmission is not just academic—it is the fabric of human destiny.

---

💡 **The Personal Catalyst: Books as Salvation**

Some might think, "An e-book reader of all things... what an uncool, boring program!" Yet, I am certain that this tool will offer the happiest moments in the world to those who harbor deep curiosity about civilizations.

During my 20s, throughout my nearly two years of mandatory military service in South Korea, I read about 500 books. In response to a letter I wrote requesting book donations for soldiers, a major economic federation built a library for us and supplied thousands of books.

Whether it was weeping over a painful breakup, facing suicidal urges after a devastating business failure, weathering days filled with depression, or when my now-late mother was diagnosed with cancer—the physical books and reports authored by ancient and modern sages brought me laughter, a reason to survive, and opportunities to rebuild my reality.

I know that countless people read books for reasons similar to mine—for survival, growth, and enlightenment. It is for "us" that I started this project.

---

🛑 **The Invisible Borders of the Digital Age**

Every day, the world pours out an overwhelming amount of knowledge. AI appears to be dominating the digital sphere, seemingly pushing humans aside. Yet, for book lovers, a massive barrier still exists: Language.

I once met a young friend from Nigeria through a startup community to whom I desperately wanted to recommend a book by a legendary South Korean entrepreneur. The book contained a profound philosophical foundation capable of inspiring a young mind in a developing nation. However, because no English translation existed, I could not share it. Similarly, after reading Kautilya's 4th-century BCE Indian classic, I longed to dive deeper into related historical texts, only to find myself barred by language barriers.

Granted, you can read an untranslated book with a dictionary in hand—but at 5% of your native reading speed. Our lives are finite, and we cannot invest all our time fighting syntax when we should be absorbing wisdom. I believed there was a vital opportunity for AI to serve us—the book lovers—rather than displace us.

---

🛠️ **Product Architecture & Global Roadmap**

We are moving beyond a simple "translator." We are building a high-context, seamless ecosystem for global literature.

1. **The Present: Windows Prototype (SLM Engine)**
   Currently, Emebala allows users to import EPUB or PDF files and rely on localized, small AI models (SLMs) to handle reading comprehension and translation. This ensures privacy, low computation costs, and contextual semantic accuracy.

2. **The Near Future: Cross-Platform Expansion**
   We are actively refining the engine to eliminate bugs and make it lighter. We will expand from Windows to native Android and iOS/Apple applications to deliver a flawless, high-performance mobile reading experience.

3. **Paginated Reading Mode (Book-Like Experience)**
   The current continuous-scroll view is optimized for skimming, reference reading, and compatibility with `react-virtuoso` virtualization. However, we recognize that many readers deeply prefer the tactile, spatial rhythm of physical books. We plan to introduce an optional CSS Columns–based pagination mode that dynamically calculates pages based on viewport size, font size, and margins. This will enable realistic page-turning, two-page synthetic spreads on wide screens, and page-number navigation—without sacrificing the existing scroll mode.

4. **Global Bookstore & Discovery Integration**
   We aim to index and connect with bookstores, publishers, and knowledge repositories worldwide. The system will implement an algorithm that helps you discover niche books written in rare languages based on your specific conceptual interests, allowing you to purchase and translate them instantly.

5. **Absolute Accessibility (Audio & Braille)**
   Technology must be inclusive. Emebala will automatically convert untranslated text into high-quality audiobooks and digital braille for the visually impaired—unlocking texts that have never been accessible to them before.

6. **Human-in-the-Loop Collaboration**
   We aim to support and collaborate with professional translators who are currently being marginalized by crude machine translation. True translation requires massive architectural nuance; we will provide tools where human experts and AI work synchronously to protect linguistic depth.

---

🏛️ **The Ultimate Mission: Safeguarding Human History**

Our ultimate, long-term concern is architecting a way to preserve our collective knowledge for future generations.

Papyrus decays, and paper rots. CDs degrade, and floppy disks have already vanished. Despite humanity's millions of years of existence, the reason we only possess a few thousand years of recorded history is that the intellectuals of those eras etched their knowledge onto stone tablets. That seemingly primitive, raw medium is precisely what transmitted historical truth to us across millennia.

We all face mortality. In the grand timeline of the universe, we live and pass through like cosmic dust. Yet, the descendants who will wonder about the knowledge, struggles, and wisdom of our fleeting era are waiting for us in the future. Emebala aims to be the digital 'Stone Tablet' for the next generations.

---

📖 **Knowledge for All: A Right, Not a Privilege**

We believe every human being has the fundamental right to access the wisdom of our collective history. A visually impaired person in Kenya deserves to read the same philosophical treatises as a sighted scholar in Paris. Language must never be a cage, and disability must never be a wall. Emebala exists to dismantle both. Our roadmap toward audio synthesis, digital braille, and screen-reader deep integration is not a feature list—it is a moral commitment.

---

🤝 **Join and Sponsor Team Sunplaza**

Executing a project of this magnitude requires a vast collective effort. If you resonate with this vision, have technical insights to share (AI/SLM, RAG, Mobile Dev), or wish to back us financially, please stand with us. Your generous sponsorship will directly fund our development stability and empower global knowledge equity.

Developed by: **Team Sunplaza** (Lead: Yongtai Kim)  
Location: Seoul, South Korea  
Contact: teamsunplaza@gmail.com

> **Note:** You are more than welcome to email us directly in your native language, or use AI translation. Every voice matters.

Please sponsor us generously to keep the fire of human wisdom alive.  
[https://teamsunplaza.gumroad.com/l/emebala](https://teamsunplaza.gumroad.com/l/emebala)

---

## Build Instructions

```bash
npm install
npm run build
npm run dist
```

## Translation Model Setup

Emebala does **not** bundle the translation model in the installer due to licensing restrictions.

Please download the model file manually from:
[https://huggingface.co/tencent/HY-MT1.5-1.8B-GGUF](https://huggingface.co/tencent/HY-MT1.5-1.8B-GGUF)

Place the downloaded `.gguf` file in the `resources/models/` directory (for development) or in the app's user data `models/` folder.

---

## License

**Emebala's source code is released under the Elastic License 2.0.**

- Anyone may use it for learning and non-commercial purposes. Contributions are welcome.
- Using Emebala in a competing commercial product or service is prohibited.

The bundled translation model (HY-MT1.5-1.8B) is provided by Tencent under a separate license (Tencent HY Community License Agreement) and is independent of this project's code license.

See the `LICENSE` file for the full Elastic License 2.0 text, and `THIRD_PARTY_LICENSES` for open source component attributions.
