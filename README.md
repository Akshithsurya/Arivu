<div align="center">

<img src="og-image.png" alt="Arivu — Science Career Literacy for Palakkad" width="100%" style="border-radius:8px;" />

<br /><br />

# Arivu · അറിവ്

**Science Career Literacy, in Malayalam, for students in Palakkad.**
Built by two students from here. For students from here. Free, forever.

<br />

[![Site](https://img.shields.io/badge/Live%20Site-arivu--palakkad.github.io-2D6A4F?style=for-the-badge&logo=github-pages&logoColor=white)](https://arivu-palakkad.github.io/)
[![License: MIT](https://img.shields.io/badge/Code-MIT%20License-1B4332?style=for-the-badge)](LICENSE)
[![Content: CC BY-SA 4.0](https://img.shields.io/badge/Content-CC%20BY--SA%204.0-40916C?style=for-the-badge)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Made in Palakkad](https://img.shields.io/badge/Made%20in-Palakkad%2C%20Kerala-D4A017?style=for-the-badge)]()
[![No Tracking](https://img.shields.io/badge/No%20Tracking-No%20Cookies-52B788?style=for-the-badge)]()

<br />

> *"You can't aim for something you've never heard of. The problem isn't IIT or NEET —*
> *it's that most students here never get to see the full map."*

</div>

---

## What this is

Arivu (അറിവ് — Malayalam for *"knowledge"*) is a bilingual science career literacy project. It exists because most +2 school students in Palakkad hear about exactly **two** futures when pursuing STEM — IIT-JEE or NEET — not because those are the only options, but because the information gap is real and wide. There are over **fifty**.

This repo is the website. It is also the philosophy.

- A static site, deployed on GitHub Pages at **zero cost**
- A bilingual map of 50+ Indian science careers and entrance routes
- A Kerala heritage module connecting modern science to the Kerala School of Mathematics (c. 1300–1600 CE)
- A career matcher that helps students discover paths by interest
- A downloadable STEM **Exam Calendar** PDF covering 13 major entrance exams
- A planned Malayalam newsletter distributed via WhatsApp — the actual messaging channel people in rural Kerala use
- A planned in-person school outreach — 3 to 5 +2 schools in Palakkad

**No login. No paywall. No tracking. No upsell.** This stays this way.

---

## Why it exists

Information asymmetry in Indian science education is defensible and documented. Students in metros hear about IISER, TIFR, ISI, NISER, JEST, and the Kerala School of Mathematics from teachers, peers, and podcasts. Students in Palakkad mostly don't.

Arivu was built to close that gap — not from the outside, but from inside the community. The two co-founders went to school in this district. They grew up speaking the language. **The Malayalam is not a translation layer bolted on for funding applications. The language is the point of the work.**

This project is also rooted in something most Palakkad students are not told: **the first calculus textbook was written in Malayalam.** Jyeṣhadeva's *Yuktibhāṣā* (c. 1530) — written in Kerala, in the vernacular, with rigorous proofs. Mādhava of Saṅgamagrāma derived the infinite series for π nearly 300 years before Leibniz. Arivu carries that forward.

---

## Screenshots

<div align="center">

| Pathways Map | Kerala Heritage | Career Matcher |
|:---:|:---:|:---:|
| <img src="https://arivu-palakkad.github.io/og-image.png" width="260" alt="Pathways Map" /> | *(screenshot)* | *(screenshot)* |
| *50+ science careers, filterable by stream and interest* | *Mādhava's series for π, rendered live in KaTeX* | *Discover your path by subject and curiosity* |

> **Note to contributors:** Replace the placeholder cells above with actual screenshots. You can generate them by opening `index.html` in a browser, taking a screenshot of each section, and committing them to a `/docs/screenshots/` folder.

</div>

---

## What's in the website

The site is a single `index.html` file — no framework, no build step, no JavaScript bundler. One file, one mission.

| Section | What it does |
|---|---|
| **Hero** | The opening question: 2 paths most students know vs. 50+ that actually exist |
| **Problem** | The information gap, named and visualised |
| **Pathways** | 50+ science career cards — astrophysics, marine biology, science policy, materials, comp bio, and more — filterable by interest and stream |
| **Matcher** | An interactive "find your path" tool that recommends careers based on subjects + interests |
| **Heritage** | The Kerala School of Mathematics — Mādhava, Nīlakaṇṭha Somayājī, Jyeṣhadeva — with a live KaTeX render of Mādhava's series for π |
| **Exam Calendar** | A complete timeline of 13 major STEM entrance exams with a downloadable PDF |
| **Roadmap** | What we've done, what's in progress, what's planned |
| **Impact** | What success looks like — language accessibility, school sessions, careers mapped, heritage context |
| **Team** | The two co-founders. Same district. Same language. Same schools. |
| **FAQ** | Honest answers to honest questions |
| **Contact** | A real form, to real people |
| **Join** | How to get the newsletter, host a session, or contribute |

The whole site is designed to be readable, printable, and usable on a ₹6,000 phone over a 2G connection. **Performance is a feature.**

---

## The Exam Calendar

<div align="center">

[![Download Exam Calendar PDF](https://img.shields.io/badge/⬇%20Download-Arivu%20Exam%20Calendar%20PDF-D4A017?style=for-the-badge)](https://arivu-palakkad.github.io/Arivu-Exam-Calendar.pdf)

</div>

A separate, downloadable PDF (`Arivu-Exam-Calendar.pdf`, ~750 KB, 8 pages) covering **13 entrance exams** across 4 categories:

| Category | Exams |
|---|---|
| **UG** | JEE Main, JEE Advanced, NEET-UG, IISER IAT, NEST |
| **PG** | JAM, GATE |
| **PhD / Research** | JEST, TIFR GS, CSIR-UGC NET |
| **Specialised** | ISI Admission Test, CUET (UG), ICAR AIEEA |

Each exam card carries: registration window, exam date, eligibility, what it leads to, and direct links to the official site + syllabus. Plus a 12-month year-at-a-glance grid and a practical notes section (*"KVPY is discontinued"*, *"NEET now also qualifies for IISER IAT"*, *"CSIR NET has two cut-offs"*, etc.).

The PDF is styled to match the site — same paper-and-ink palette, same Playfair Display + IBM Plex Mono typography, same hand-drawn accents. Print it. Pin it on a wall. Plan the year.

---

## Tech stack

Deliberately boring. Deliberately light.

| Layer | Choice | Why |
|---|---|---|
| Structure | Single `index.html` | No framework, no SPA, no build step. One file. |
| Styling | Vanilla CSS | Custom properties only. No Tailwind, no dependency. |
| Logic | Vanilla JavaScript | Matcher, filter bar, nav scroll, count-up animations. |
| Math rendering | KaTeX (CDN) | Mādhava's series for π, rendered live in the browser. |
| Fonts | Google Fonts | Playfair Display, Instrument Sans, IBM Plex Mono, Noto Sans Malayalam, Caveat |
| Hosting | GitHub Pages | Free HTTPS. Free CDN. Zero cost. |
| Privacy | None | No analytics. No cookies. No tracking. Nothing. |

The exam calendar PDF is generated from a standalone HTML file rendered via Playwright (`html2pdf-next.js`). The source HTML is in `/scripts/exam-calendar.html`.

---

## Project structure

```
arivu/
├── index.html                       # The entire website. One file.
├── Arivu-Exam-Calendar.pdf          # Downloadable exam calendar (13 exams, 8 pages)
├── favicon.png
├── og-image.png
├── README.md
│
└── scripts/
    └── exam-calendar.html           # Source HTML for the PDF (render with Playwright)
```

No `src/`. No `dist/`. No `package.json`. No `node_modules/`. No build step. If you want to deploy your own version — copy `index.html` to any static host. Done.

---

## Run it locally

You don't need a server. Just open the file.

```bash
# Option 1 — just open it
open index.html            # macOS
xdg-open index.html        # Linux
start index.html           # Windows

# Option 2 — static server, if you want live reload
python3 -m http.server 8000
# → http://localhost:8000
```

No build. No install. No dependencies. No Node. Just a browser.

---

## Regenerate the Exam Calendar PDF

The PDF is rendered from `scripts/exam-calendar.html` via Playwright. To regenerate after editing the source:

```bash
# Requires: Node.js, Playwright, Chromium
node skills/pdf/scripts/html2pdf-next.js \
  scripts/exam-calendar.html \
  --output Arivu-Exam-Calendar.pdf \
  --width 720px --height 1020px --nopaged
```

The HTML source is hand-written — no Blueprint, no design engine. Edit the cards directly in `exam-calendar.html`, re-render, and ship.

---

## Contributing

This project is built for a specific community, but the **method** is portable. If you want to:

- **Add or correct an exam date / syllabus link** → edit `scripts/exam-calendar.html`, regenerate the PDF, open a PR
- **Add a new career pathway** → edit the Pathways data in `index.html` (the pathway cards are inline JSON/HTML objects)
- **Improve the Malayalam translations** → please do, and open a PR — native speaker review is always welcome
- **Translate the model to your own district / language** → fork the repo, change the content, keep the philosophy. Tell us if you do — we'd love to link to it.

### Things we will not merge

| ❌ | Reason |
|---|---|
| Tracking, analytics, or third-party scripts | Privacy is a value, not a feature |
| Login walls or paywalls | Free, forever. That's the deal. |
| Removal of bilingual character | The Malayalam is the point. |
| Shift of focus from Palakkad to "students in general" | The specificity is what makes it useful. Generic sites already exist. |

---

## Roadmap

| Phase | Status | What it is |
|---|---|---|
| **Phase 0** | ✅ Done | Research & planning — conversations with +2 students in Palakkad, identifying the gap |
| **Phase 1** | ✅ Done | Platform build — bilingual website, Pathways Map, Kerala Heritage module, Career Matcher |
| **Phase 1.5** | ✅ Done | Exam Calendar PDF — 13 exams, 8 pages, downloadable |
| **Phase 2** | 🟡 In progress | School outreach — 3–5 career talks at +2 schools in Palakkad, documented with photos and feedback |
| **Phase 3** | 🟡 In progress | Malayalam newsletter — monthly 2–4 page PDF, distributed via WhatsApp |
| **Phase 4** | ⚪ Planned | Student stories & evidence — document students who discovered new pathways, build a feedback loop |

---

## Values

These are not aspirational. They are constraints held since day one.

**1. Free, forever.**
No login, no paywall, no upsell. GitHub Pages at zero cost. This is not a freemium funnel.

**2. Bilingual by design, not by translation.**
Malayalam content is written in Malayalam, not translated from English. The first calculus textbook was written in Malayalam. We are not going to pretend that doesn't matter.

**3. Specific, not generic.**
This is for Palakkad. Not "India." Not "rural students." Palakkad. The specificity is what makes it useful — and what makes it honest.

**4. Built by the community, for the community.**
Both co-founders went to school here. The credibility is not institutional. It is peer.

**5. Documented, not anecdotal.**
The information gap is real and defensible. The careers are real and funded. The heritage is real and verifiable. Nothing here is decorative.

**6. Open source, in the literal sense.**
MIT-style permissive licensing. Fork it. Translate it. Take it to your own district. Just keep it free.

---

## The team

<div align="center">

| | |
|:---:|:---:|
| **Akshith Surya** | **Aadi Mahesh** |
| Co-founder · Science & Content | Co-founder · Design & Editorial |
| Grade 10, Palakkad | Grade 10, Palakkad |
| NASA Space Apps Global Nominee | NASA Space Apps Nominee |
| Astrophysics · Cybersecurity | Design · Quantum Physics mentorship |
| Malayalam · English · Tamil | Malayalam · English |

</div>

We both went to school in this district. We both grew up speaking this language. **That is not a footnote — it is the entire premise.**

---

## Acknowledgements

- **The Kerala School of Mathematics** (c. 1300–1620 CE) — Mādhava of Saṅgamagrāma, Nīlakaṇṭha Somayājī, Jyeṣhadeva, and the many unnamed scholars who did serious mathematics in Malayalam, in Kerala, centuries before Europe caught up. The heritage module is the smallest possible acknowledgement of a debt that cannot be repaid.
- **The +2 students of Palakkad** who told us, in conversations and in classrooms, what they didn't know. This project is built from your questions.
- **The teachers** who let us visit, and the principals who said yes.
- **NASA Space Apps Challenge** — for the nomination that gave two students from a small town the confidence to keep building.
- **GitHub Pages** — for being free, fast, and reliable.

---

## License

| | License |
|---|---|
| **Source code** (HTML, CSS, JS, build scripts) | [MIT License](LICENSE) |
| **Written content** (career descriptions, heritage text, exam calendar, Malayalam translations) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |

The exam calendar PDF is released under CC BY-SA 4.0. Print it, photocopy it, pin it on a classroom wall. That is the point.

---

## Contact

- **Website**: [arivu-palakkad.github.io](https://arivu-palakkad.github.io/)
- **Email**: via the Contact form on the site
- **WhatsApp newsletter**: subscribe via the Join section on the site
- **GitHub Issues**: for bugs, content corrections, and translation improvements

We read everything. We reply slowly. We are still in school.

---

<div align="center">

**Arivu is a bilingual science career literacy project for +2 students in Palakkad, Kerala.**
**Built by two students from here. Free, forever.**
**The first calculus textbook was written in Malayalam. We are carrying that forward.**

<br />

*Arivu · അറിവ് · Knowledge · Palakkad, Kerala · Est. 2025*

</div>
