# Arivu · അറിവ്

> Science Career Literacy, in Malayalam, for students in Palakkad.
> Built by two students from here. For students from here. Free, forever.

[![Live Site](https://img.shields.io/badge/LIVE-arivu--pallakad.netlify.app-c8342a?style=for-the-badge&logo=netlify&logoColor=white)](https://arivu-pallakad.netlify.app/) [![License: MIT](https://img.shields.io/badge/Code-MIT-1b2433.svg?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE) [![License: CC BY-SA 4.0](https://img.shields.io/badge/Content-CC_BY--SA_4.0-e8b73a.svg?style=for-the-badge&logo=creativecommons&logoColor=black)](https://creativecommons.org/licenses/by-sa/4.0/) [![Status](https://img.shields.io/badge/Phase-2_in_progress-3e7050?style=for-the-badge)](#roadmap) [![Cost](https://img.shields.io/badge/Cost_to_Access-₹0-1b2433?style=for-the-badge)](#values) [![No Tracking](https://img.shields.io/badge/Tracking-NONE-1b2433?style=for-the-badge&logo=mozilla&logoColor=white)](#values)

---

## About

A bilingual science career literacy project for +2 school students in Palakkad, Kerala. Most students here hear about two futures when pursuing STEM — IIT-JEE or NEET — not because those are the only options, but because the information gap is real and wide. There are over fifty. This project exists to close that gap, from inside the community, in the language of the community.

Built by two Grade 10 students from Palakkad who went to the same schools, speak the same language, and refused to wait for someone else to fix the asymmetry. The site is one `index.html` file. The exam calendar is a downloadable PDF. The heritage module traces the Kerala School of Mathematics — Mādhava of Saṅgamagrāma derived the infinite series for pi nearly 300 years before Leibniz. The first calculus textbook was written in Malayalam. The language is not a barrier to this work. It is the point of it.

One file. One mission. No login. No paywall. No tracking. No upsell. This stays this way.

---

## Live

The site is deployed at **[arivu-pallakad.netlify.app](https://arivu-pallakad.netlify.app/)** — open it on a 2G connection on a Rs 6,000 phone and it still works. Performance is a feature, not an afterthought.

The downloadable **Exam Calendar PDF** (`Arivu-Exam-Calendar.pdf`, 8 pages, ~750 KB) covers 13 major STEM entrance exams — JEST, GATE, JAM, IIT-JEE (Main and Advanced), NEET-UG, IISER IAT, NEST, ISI Admission Test, TIFR GS, CSIR-UGC NET, CUET (UG), and ICAR AIEEA. Each card carries the registration window, exam date, eligibility, what it leads to, and direct links to the official site and syllabus. Print it. Pin it on a wall. Plan the year.

---

## Socials

[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/ak_45_______) [![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?logo=Reddit&logoColor=white)](https://reddit.com/user/Plane_Channel_7406) [![Codepen](https://img.shields.io/badge/Codepen-000000?logo=codepen&logoColor=white)](https://codepen.io/Akshithsurya) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:akshithsurya1@proton.me) [![Website](https://img.shields.io/badge/Website-arivu--pallakad.netlify.app-c8342a?logo=googlechrome&logoColor=white)](https://arivu-pallakad.netlify.app/)

---

## Tech Stack

The site is deliberately boring and deliberately light. No framework. No SPA. No client-side router. No build step. The whole website is one HTML file.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

![KaTeX](https://img.shields.io/badge/KaTeX-3291A8?style=for-the-badge&logo=katex&logoColor=white) ![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=googlefonts&logoColor=white)

![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=%23C7B7A3) ![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-121011?style=for-the-badge&logo=github&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

The exam calendar PDF is generated from a standalone HTML file rendered via Playwright (`html2pdf-next.js`). The source HTML lives in `scripts/exam-calendar.html` — hand-written, no Blueprint, no design engine. Edit the cards directly, re-render, ship.

---

## Site Map

The whole site is a single `index.html` — every section below lives inline in that file.

| Section | What it does |
|---|---|
| **Hero** | The opening question — 2 paths most students know vs. 50+ that actually exist |
| **Problem** | The information gap, named and visualised |
| **Pathways** | 50+ science career cards — astrophysics, marine biology, science policy, materials, computational biology, and more — filterable by interest and stream |
| **Matcher** | An interactive "find your path" tool that recommends careers based on subjects and interests |
| **Heritage** | The Kerala School of Mathematics — Madhava, Nilakantha Somayaji, Jyeshthadeva — with a live KaTeX render of Madhava's series for pi |
| **Exam Calendar** | A complete timeline of 13 major STEM entrance exams with a downloadable PDF |
| **Roadmap** | What is done, what is in progress, what is planned |
| **Impact** | What success looks like — language accessibility, school sessions, careers mapped, heritage context |
| **Team** | The two co-founders. Same district. Same language. Same schools. |
| **FAQ** | Honest answers to honest questions |
| **Contact** | A real form, to real people |
| **Join** | How to get the newsletter, host a session, or contribute |

---

## GitHub Stats

![](https://github-readme-stats.shion.dev/api?username=Akshithsurya&theme=tokyonight&hide_border=false&include_all_commits=true&count_private=true)

![](https://streak-stats.demolab.com/?user=Akshithsurya&theme=tokyonight&hide_border=false)

![](https://github-readme-stats.shion.dev/api/top-langs/?username=Akshithsurya&theme=tokyonight&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

### Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=Akshithsurya&limit=5&theme=dark&combine_all_yearly_contributions=true)

---

## Team

### Akshith Surya — Co-founder · Science and Content
Grade 10, Palakkad. NASA Space Apps 2025 Global Nominee and ISRO Space Week 1st Prize winner. Builds AI-powered exoplanet finders, hardware pentesting tools, and career platforms — usually all at the same time. Hardware security researcher who enjoys poking at ESP32s, RF signals, and firmware that was never meant to be touched. Mentored by a NASA-affiliated planetary scientist. Multilingual — Malayalam, English, Tamil. Focuses on astrophysics content and the science backbone of Arivu. One commit, one paper, one launch at a time, working toward a future in astrophysics and aerospace research.

### Aadi Mahesh — Co-founder · Design and Editorial
Grade 10, Palakkad. NASA Space Apps nominee. Handles designing, editing, and the visual identity of Arivu. Mentored in quantum physics. The Malayalam newsletter is his writing. **Credited with the original brainstorming idea behind Arivu and the frontend implementation that shaped the site you see today.** Built and designed this website alongside Akshith.

> We both went to school in this district. We both grew up speaking this language. That is not a footnote — it is the entire premise.

---

## Roadmap

| Phase | Status | What it is |
|---|---|---|
| Phase 0 | Done | Research and planning — conversations with +2 students in Palakkad, identifying the gap |
| Phase 1 | Done | Platform build — bilingual website, Pathways Map, Kerala Heritage module, Career Matcher |
| Phase 1.5 | Done | Exam Calendar PDF — 13 exams, 8 pages, downloadable from the site |
| Phase 2 | In Progress | School outreach sessions — 3 to 5 career talks at +2 schools in Palakkad |
| Phase 3 | In Progress | Malayalam newsletter — monthly 2 to 4 page PDF, distributed via WhatsApp |
| Phase 4 | Planned | Student stories and evidence — document students who discovered new pathways through Arivu |

---

## Values

These are not aspirational. They are constraints held to since day one.

1. **Free, forever.** No login, no paywall, no upsell. The site lives on Netlify at zero cost. This is not a freemium funnel.
2. **Bilingual by design, not by translation.** Malayalam content is written in Malayalam, not translated from English. The first calculus textbook was written in Malayalam. We are not going to pretend that does not matter.
3. **Specific, not generic.** This is for Palakkad. Not "India." Not "rural students." Palakkad. The specificity is what makes it useful — and what makes it honest.
4. **Built by the community, for the community.** Both co-founders went to school here. The credibility is not institutional. It is peer.
5. **Documented, not anecdotal.** The information gap is real and defensible. The careers are real and funded. The heritage is real and verifiable. Nothing here is decorative.
6. **Open source, in the literal sense.** MIT for code, CC BY-SA 4.0 for content. Fork it. Translate it. Take it to your own district. Just keep it free.

---

## Contributing

This project is built for a specific community, but the **method** is portable.

- Add or correct an exam date or syllabus link — edit `scripts/exam-calendar.html`, regenerate the PDF, open a PR
- Add a new career pathway — edit the Pathways data in `index.html` (the pathway cards are inline)
- Improve the Malayalam translations — please do, open a PR
- Translate the model to your own district or language — fork the repo, change the content, keep the philosophy. Tell us if you do — we would love to link to it

### Things we will not merge

- Anything that adds tracking, analytics, or third-party scripts
- Anything that puts content behind a login or paywall
- Anything that removes the bilingual character of the project
- Anything that shifts the focus from Palakkad students to "students in general"

The specificity is the point. Generic science career sites already exist. This one is for here.

---

## Project Structure

```
.
├── index.html                       # The entire website. One file.
├── Arivu-Exam-Calendar.pdf          # Downloadable exam calendar
├── favicon.png
├── og-image.png
├── README.md                        # This file.
│
└── scripts/
    └── exam-calendar.html           # Source HTML for the PDF
```

No `src/`. No `dist/`. No `package.json`. No `node_modules/`. If you want to deploy your own version, copy `index.html` (and optionally `Arivu-Exam-Calendar.pdf`, `favicon.png`, `og-image.png`) to any static host. Done.

---

## Run Locally

You don't need a server. Just open the file.

```bash
# Option 1: just open the file
open index.html            # macOS
xdg-open index.html        # Linux
start index.html           # Windows

# Option 2: any static server, if you want one
python3 -m http.server 8000
# → http://localhost:8000
```

No build. No install. No dependencies.

---

## Regenerate the Exam Calendar PDF

```bash
# Requires: Node.js, Playwright, Chromium
node skills/pdf/scripts/html2pdf-next.js \
  scripts/exam-calendar.html \
  --output Arivu-Exam-Calendar.pdf \
  --width 720px --height 1020px --nopaged
```

The HTML source is hand-written. Edit the cards directly in the HTML, re-render, ship.

---

## Acknowledgements

- **The Kerala School of Mathematics** (c. 1300–1620 CE) — Madhava of Sangamagrama, Nilakantha Somayaji, Jyeshthadeva, and the many unnamed scholars who did serious mathematics in Malayalam, in Kerala, centuries before Europe caught up. The heritage module is the smallest possible acknowledgement of a debt that cannot be repaid.
- **The +2 students of Palakkad** who told us, in conversations and in classrooms, what they didn't know. This project is built from your questions.
- **The teachers** who let us visit, and the principals who said yes.
- **NASA Space Apps Challenge** — for the nomination that gave two students from a small town the confidence to keep building.
- **ISRO Space Week** — for the recognition that says the work matters.
- **Netlify** — for free, fast, reliable hosting.
- **GitHub Pages** — for being there as a fallback, always free.

---

## Contact

- **Website**: [arivu-pallakad.netlify.app](https://arivu-pallakad.netlify.app/)
- **Email**: akshithsurya1@proton.me
- **WhatsApp newsletter**: subscribe via the Join section on the site
- **GitHub issues**: for bugs, content corrections, and translation improvements

We read everything. We reply slowly. We are still in school.

---

## License

- **Source code** (HTML, CSS, JS, build scripts): **MIT License**
- **Written content** (career descriptions, heritage text, exam calendar content, Malayalam translations): **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**

The exam calendar PDF is released under CC BY-SA 4.0. Print it, photocopy it, pin it on a classroom wall. That is the point.

---

## The one-line version

> Arivu is a bilingual science career literacy project for +2 students in Palakkad, Kerala. Built by two students from here. Free, forever. The first calculus textbook was written in Malayalam. We are carrying that forward.

---

Arivu · അറിവ് · Knowledge · Palakkad, Kerala · 2025
