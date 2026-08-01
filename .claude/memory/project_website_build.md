---
name: project-website-build
description: "Rashid's portfolio — index.html + story.html + favicon.svg — LIVE at rashid-bioinfo.github.io as of 2026-08-02"
metadata: 
  node_type: memory
  type: project
  originSessionId: 4c0626b6-062f-4fce-9bc7-d7d240d4a630
---

Portfolio for Rashid Hussain. Local files at `/Users/rashid/Documents/99_Personal/my_profile/myWebsite/`.

**Why:** Redesigned profile to replace old Hugo-based rashid-bioinfo.github.io site.

**How to apply:** Self-contained HTML/CSS/JS, no build step. Preview locally: `python3 -m http.server 8765` from myWebsite/, then open http://localhost:8765. Hard-refresh with Cmd+Shift+R after edits. To deploy: copy changed files into `/tmp/rashid-bioinfo.github.io/`, commit, and push to `origin main`.

## Status — LIVE at rashid-bioinfo.github.io (deployed 2026-08-02)

GitHub repo: `rashid-bioinfo/rashid-bioinfo.github.io` (main branch = live site)
Old Hugo site preserved at: `backup/old-portfolio` branch (safe, never deleted)

### Files (3 total)
- `index.html` — main portfolio (~1150 lines)
- `story.html` — standalone interactive life story page
- `rashid.jpg` — profile photo
- `favicon.svg` — original SVG favicon (R monogram, blue→teal gradient, no copyright)

## index.html — sections

- `#home` — Hero: "Hi, I'm Rashid Hussain" (white-space:nowrap keeps it one line); subtitle shows Humanitas role; bio + research interests bullet list; social links (ORCID, GitHub, LinkedIn, Google Scholar, ResearchGate, X, Kaggle)
- `#stats` — 12+ Publications · 7+ Projects · 8+ Years Experience · 3 Countries
- `#banner` — "Postdoctoral Researcher in Computational Pathology" blue strip
- `#skills` — Technical skills grid (Python, R, Bash, SQL, PyTorch, RDKit, AutoDock, GROMACS/AMBER, etc.)
- `#experience` — Work + Education timelines (two-column exp-grid)
- `#publications` — 6 pub cards + Google Scholar link; peer review list at bottom
- `#projects` — 7 project cards
- `#activities` — Professional Activities (Teaching & Training, Certifications, Kaggle/Data Science, Memberships)
- `#tutorials` — 3 YouTube tutorial series cards (Mendeley 2 vids, MODELLER 6 vids, CADD/AutoDock 11 vids)
- `#connect` — CTA + footer

### Navbar links
Home · Skills · Experience · Publications · Projects · Activities · Tutorials · Contact

### Hero fix
`.hero-name` has `white-space: nowrap` — keeps "Hi, I'm Rashid Hussain" on one line always.

## story.html — interactive life story

Standalone page linked from index.html hero ("My Story" button). Written in **first person** throughout. Features: reading progress bar, typing hero tagline, animated stat counters, side chapter nav dots, scroll-reveal (IntersectionObserver), 7 chapters, credentials gallery, highlights, closing CTA.

### Chapters (CV-verified facts)
- **Ch1 (2006–2010):** B.S. Bioinformatics · COMSATS University Islamabad
- **Ch2 (2011–2013):** M.S. Bioinformatics · COMSATS University Islamabad
- **Ch3 (2014–2019):** Research Intern (NCB, Quaid-e-Azam Univ, Jun 2014–Jan 2015) → Research Associate & TA (LUMS, Feb 2015–Jan 2016) → Research Assistant (A.Z. Pharma, Feb 2016–Dec 2019) · Best Poster IST Feb 2015
- **Ch4 (Aug 2017–Mar 2023):** Ph.D. Chemistry (Computational) · Forman Christian College · Magna Cum Laude (Higher Honors) · HCV NS3 thesis · COVID-19 virtual screening paper (2020) · 19 YouTube tutorials
- **Ch5 (2022):** IRSIP Fellowship £6,250 · University of Manchester · VSpipe-GUI developed · Carpentries Instructor certified Oct 2022
- **Ch6 (2022–2025):** Deep Waters NY (PyMOL/GIST plugin) · Ayass BioScience TX (Jul 2023–May 2025) · Carpentries teaching 3 continents · UK Global Talent Visa (Royal Society, UK endorsement · May 2025)
- **Ch7 (Jan 2026–Present):** Postdoc · Humanitas Research Hospital (IRCCS), Milan · SMS project (sarcoma AI) · Visiting Academic Manchester (Jul 2025–) · RSC Chemical Biology Symposium London Jul 2026

### Credentials section (9 cards)
RSci (Science Council UK · Jun 2025) · UK Global Talent Visa (Royal Society, UK · May 2025) · AMRSC (RSC · Oct 2023) · ACS Member (May 2022) · Carpentries Instructor (Oct 2022) · 5-Day AI Agents (Kaggle×Google 2025) · International Speaker (COMSATS Feb 2026) · Best Poster FCC (2022) · Leadership for Scientists (SCI London 2026)

### Stats counters
20 Years in Science · 5 Countries · 12 Publications · 7 Research Projects · 671 LinkedIn Followers · 19 Tutorial Videos

## favicon.svg
Original SVG created from scratch — no copyright. Bold white "R" on blue→teal gradient rounded square (rx=7). Colors: `#2563eb` → `#0d9488`. Linked via `<link rel="icon" type="image/svg+xml" href="favicon.svg">` in both index.html and story.html.

## Design system (DO NOT CHANGE)
- Primary: #2563eb · Teal: #0d9488 · Gold: #f59e0b · Navy: #0a0f1e
- Font: Inter + Playfair Display · Icons: Font Awesome 6.5 CDN
- Profile photo: `rashid.jpg`
- Animations: IntersectionObserver adds `.visible` / `.on` class

## Key CV facts (sourced from CV.pdf)
- Education: B.S. & M.S. Bioinformatics both at COMSATS University Islamabad (NOT Punjab / NOT LUMS)
- PhD: Forman Christian College, Aug 2017–Mar 2023, Magna Cum Laude
- A.Z. Pharma role: Research Assistant, Feb 2016–Dec 2019 (NOT Regulatory Affairs Officer)
- Best Poster: Institute of Space Technology, Feb 2015 (NOT Institute of Science & Technology)
- Global Talent endorsing body: Royal Society, UK (NOT Royal Society of Chemistry)
- Ayass BioScience end date: May 2025 (NOT Jun 2025)

## Backups
- **GitHub:** Old Hugo site preserved at `backup/old-portfolio` branch on rashid-bioinfo/rashid-bioinfo.github.io
- **Local zip:** `20270802_rashidBlog.zip` — full source + all relevant files, created 2026-08-02

## Pending
- SEO/meta improvements and structured data
- DOI link verification pass
