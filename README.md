# ReadEasy — Making Reading Easier and More Fun

> *Transforming any scanned document into a dyslexia-friendly reading experience.*

Built by **Phoebe Wang, Tuhina Das, Laurence Moung, Clement Poon** | Zero install. Zero cost. Zero excuses.

---

## The Problem

**1 in 5 people have dyslexia — and most digital tools ignore them.**

- Students with dyslexia often receive printed worksheets, scanned PDFs, and physical handouts that can't be reformatted
- Existing PDFs and images are locked — you can't change the font, spacing, or color
- Text-to-speech tools require selectable text — scanned images break them entirely
- No single free, zero-install tool combines OCR + dyslexia-friendly formatting + read-aloud

---

## The Solution

ReadEasy is a **single HTML file** that requires no installation, no account, and no back-end server.

**How it works:**
1. Upload a PDF or image (scanned worksheet, photo of a textbook page)
2. ReadEasy uses OCR (via OCR.space API) to extract the text
3. Text is rendered with fully customizable accessibility settings
4. Listen with the built-in Read Aloud feature

---

## Features

| Feature | Details |
|---|---|
| Dyslexia-friendly fonts | OpenDyslexic, Lexie Readable, or Arial |
| Bionic Reading | Bolds the first half of each word to guide the eye |
| Letter Spacing | Adjustable 0–8px |
| Line Height | Adjustable 1.0–2.5x |
| Font Size | 12px–32px slider |
| Background Colors | White, Soft Yellow, Light Blue, Light Peach |
| Read Aloud | Native browser text-to-speech with pause/resume |
| Download | Save the reformatted text |
| File support | Multi-page PDF and JPG/PNG images |

---

## Technology Stack

| Layer | Technology |
|---|---|
| Front-end | Pure HTML, CSS, JavaScript — no frameworks |
| PDF rendering | PDF.js (Mozilla, open-source, CDN) |
| OCR engine | OCR.space API (free tier, English) |
| Text-to-speech | Web Speech API (native browser) |
| Fonts | OpenDyslexic (open source), Lexie Readable (CDNfonts) |
| Hosting | Any static host — even a USB drive |

---

## Cost Breakdown

| Item | Cost |
|---|---|
| OCR.space API (free tier — 25,000 req/mo) | $0 |
| PDF.js | $0 (open source) |
| OpenDyslexic & Lexie Readable fonts | $0 (open source) |
| Web Speech API | $0 (built into browsers) |
| Hosting (GitHub Pages, Netlify, etc.) | $0 |
| **Total MVP cost** | **$0** |
| At scale with OCR.space Pro | ~$10–$30/month |

---

## Competitor Comparison

| Tool | OCR | Dyslexia Fonts | Read Aloud | Free | No Account | Bionic Reading |
|---|---|---|---|---|---|---|
| **ReadEasy** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Adobe Acrobat | ✅ | ❌ | ✅ | ❌ | ❌ | ❌ |
| Beeline Reader | ❌ | ❌ | ❌ | Partial | ❌ | ✅ |
| Natural Reader | ✅ | ❌ | ✅ | Partial | ❌ | ❌ |
| Helperbird | ❌ | ✅ | ✅ | Partial | ❌ | ✅ |
| Read&Write (Texthelp) | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ |
| Google Docs | ❌ | ❌ | ✅ | ✅ | ❌ | ❌ |

**ReadEasy is the only tool that combines OCR of scanned documents + dyslexia-friendly fonts + bionic reading + read aloud — for free, with no account or install.**

---

## Market Opportunity

- ~1 in 5 people have dyslexia (International Dyslexia Association)
- ~780 million people globally have reading difficulties
- US K–12 special education market: $50B+/year
- EdTech accessibility tools market growing at ~15% CAGR
- 70% of students with dyslexia are never formally identified — they still struggle daily

---

**Who it helps:**
- K–12 and college students with dyslexia or reading difficulties
- Teachers who want to quickly make materials more accessible
- Parents supporting children with learning differences
- Anyone who reads better with larger spacing, different fonts, or audio support

---

## Impact

- Any student with dyslexia can make any printed document readable — for free, in seconds
- Teachers spend zero extra time reformatting materials
- No expensive software license or school IT department required
- Runs on a Chromebook, phone browser, or off a USB stick

---

## Roadmap

- [ ] Multi-language OCR support
- [ ] Word highlighting synced with Read Aloud (karaoke-style)
- [ ] Syllable breaking mode
- [ ] Saved user profiles (remember your settings)
- [ ] Browser extension version
- [ ] Teacher dashboard for sharing formatted docs with students
- [ ] Offline mode via Tesseract.js (no API key needed)

---

## How to Use

1. Open `ReadEasy.html` in any browser — no install needed
2. Drag and drop a PDF or image, or click to upload
3. Click **Process File** and wait for OCR to extract the text
4. Adjust font, spacing, size, and background color to your preference
5. Click **Read Aloud** to have the text read to you
6. Click **Download** to save the reformatted text

---

## SASE Roots Competition

**SASE** — Society of Asian Scientists and Engineers
