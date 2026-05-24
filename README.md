# Ahmed Sami Web Development Course

My notes and practice code from the Arabic web development course **Rock Foundation in the Web World** (صخرة الأساس في عالم الويب) taught by Ahmed Samy El-khouly on Udemy.

---

## Student Information

| Field | Detail |
|-------|--------|
| Student | Mahmoud Shaabo |
| Teacher | Ahmed Samy El-khouly |
| Teacher channel | [Ahmed Samy on YouTube](https://www.youtube.com/@ahmedthebest) |
| Course link | [Rock Foundation in the Web World — Udemy](https://www.udemy.com/course/rockforweb/) |
| Course rating | 4.8 / 5 |
| Language | Arabic |
| Full course length | 8 hr 55 min — 55 lectures across 5 sections |

---

## Repository Structure

```
ahmed-sami-web-course/
├── code/          ← practice websites I built during each lecture
│   ├── section1/      lectures 4 – 6     (HTML basics)
│   ├── section2/      lectures 8 – 18    (HTML)
│   ├── section3/      lectures 20 – 38   (CSS)
│   └── section4/      lectures 40 – 44   (DevTools, deployment, Netflix clone, NVDA)
├── lectures/      ← my Arabic study notes (.txt) for each lecture
│   ├── section1/      lectures 4 – 6
│   ├── section2/      lectures 8 – 18
│   ├── section3/      lectures 20 – 38
│   └── section4/      lectures 40, 41, 42, 43 (5 drafts), 44
└── web code/      ← original source files provided by the teacher
    ├── section1/      003.html, 004.html
    ├── section2/      002.html – 011 blog.html
    ├── section3/      teacher CSS bundle (nested section3/section3/)
    ├── section4/      links.txt (deployment resource links)
    └── section5/      full hamburger-menu project (index.html + css/)
```

A local folder named **`اكواد قديمة/`** (old code backup) may exist on disk as an offline backup. It is listed in [`.gitignore`](.gitignore) and is **not** published on GitHub. The editor-agent settings folder `.claude/` is also ignored.

### code/

Student practice projects organised by section and lecture number.

```
code/
├── section1/           lectures 4 – 6   (lectures 1–3 had no code exercise)
├── section2/           lectures 8 – 18  (lectures 7 and 17 were theory-only)
├── section3/           lectures 20 – 38 (lectures 23, 24, 31, 32, 33 were theory-only; 39 not yet saved)
└── section4/           lectures 40 – 44 (lectures 39, 42 were theory-only on disk: 42 folder is a myTunes practice copy)
```

**code/section4/ contents:**

| Folder | Lecture | Project |
|--------|---------|---------|
| `web site40/` | 40 | myTunes — Chrome DevTools demo |
| `web site41/` | 41 | myTunes — deployment target (Netlify / GitHub Pages) |
| `web site42/` | 42 | myTunes practice copy (lecture itself is theory about earning) |
| `web site43/` | 43 | Netflix landing page clone with SEO meta tags |
| `web site43 final test/` | 43 | Tested variant of the Netflix clone |
| `web site 44/` | 44 | Netflix clone reviewed with NVDA + accessibility tweaks |

**Naming conventions inside code/:**

| Pattern | Meaning |
|---------|---------|
| `web site NN/` | Main practice project for lecture NN |
| `web site NN my_code/` | My own independent attempt at the same exercise (written without looking at the teacher's solution) |
| `web site NN test/` | Experimental variant or extra test built while watching the lecture |

**Notes:**
- `code/section2/` contains a loose `index.html` and `files/` folder at its root — these are scratch files from an early exercise, not part of a numbered lecture folder.
- Lecture 27 and 28 each have two pages (`index.html` + `index1.html`) and two stylesheets (`style.css` + `style1.css`) because those lectures demonstrated multi-file site structure.
- Lecture 38 is split into two separate projects: **position** (CSS positioning) and **review** (final section review). Each has a `my_code` variant.

### lectures/

Arabic study notes in plain `.txt` format, one file per lecture, stored in matching section folders.

- Each file is written as a **student reference** (مرجع الطالب) with learning goals and inline Arabic comments on important HTML/CSS lines — suitable for screen reader users following along with the video.
- Coverage mirrors `code/`: sections 1–3 follow lecture numbers exactly; section 4 adds notes for the imported-notes lectures (40–44).
- Lecture 20 has three separate note files (one per CSS method: inline, internal, external).
- Lecture 18 has two files (blog and blog1 matching the two HTML files in `code/section2/web site 18/`).

**lectures/section4/ contents:**

| File | Lecture | Topic |
|------|---------|-------|
| `40 web code  developer tools.txt` | 40 | Chrome Developer Tools |
| `41 web code deployment .txt` | 41 | Deploying for free (Netlify, GitHub Pages) |
| `42 web code earning.txt` | 42 | Earning money from web design (theory, no code) |
| `43 web code.txt` | 43 | Accessibility + SEO — main lesson summary |
| `lec43_detailed_notes.txt` | 43 | Detailed Arabic summary of the same lecture |
| `43 web code accessibility seo notes.txt` | 43 | Accessibility/SEO notes draft |
| `43 web code final version tested .txt` | 43 | Tested final version of the notes |
| `43 web code accessibility seo notesfinal version tested from claude ai.txt` | 43 | Extra reviewed/tested version |
| `44 web code developer toolkit nvda notes.txt` | 44 | NVDA Developer Toolkit (for blind developers) |

Lecture 39 was an introduction to Section 4 and has no code or notes file.

### web code/

Original course bundle from the teacher, kept as-is for reference.

```
web code/
├── section1/       003.html, 004.html
├── section2/       002.html – 011 blog.html
├── section3/
│   └── section3/   numbered folders: 002, 003, 004, 005, 006, 007, 008, 010, base
│                   (the nested section3/section3/ path is how the teacher's bundle is packaged)
├── section4/       links.txt  (deployment resource links, no HTML code)
└── section5/       index.html + css/style.css + css/menu.css  (full hamburger-menu project)
```

- Teacher files in sections 1–3 use a different numbering scheme from the student folders.
- Teacher material for **Section 4** here is just `links.txt`; the student-built code for that section now lives under `code/section4/`.
- Teacher material for **Section 5** exists here only — there is no matching `code/section5/` folder yet.

---

## Course Topics

### Section 1 — Introduction (6 lectures, 40 min)

- Setting up the code editor.
- Writing the first HTML page.
- Basic structure: `DOCTYPE`, `html`, `head`, `body`.
- Heading tags `h1`–`h6`, paragraph `p`, and link `a`.

### Section 2 — HTML (12 lectures, 2 hr 31 min)

- Semantic tags: `main`, `section`, `aside`, `div`.
- Inline tags: `span`, `strong`, `em`, `u`. Adding images with `img`.
- Lists: ordered `ol`, unordered `ul`, navigation lists.
- Tables: `table`, `tr`, `th`, `td`.
- Forms: `form` with inputs `text`, `password`, `email`, `date`, `color`, `time`, `select`.
- HTML entities: `&lt;`, `&gt;`, `&nbsp;`.
- Media: `audio` and `video` tags.
- Embedding: `iframe` with YouTube and Wikipedia examples.
- A small blog project: `article`, `nav`, `footer`, `hr`.

### Section 3 — CSS (20 lectures, 3 hr 39 min)

- Three ways to write CSS: inline, internal, external.
- CSS priority — how the browser picks the winning rule.
- Selectors: class `.class` and id `#id`.
- Colors: names, `rgb`, `rgba`.
- Common rules: fonts, alignment, size.
- Multiple selectors and a two-page site with two style files.
- The box model: padding and margin with shorthand values.
- Link styling: `a:hover`, `a:visited` pseudo-classes. Button styling.
- The display property: `inline`, `block`, `inline-block`.
- List styling and navigation menus using `ul` and `li`.
- Float and overflow: `float: right`, `overflow: hidden`, `clear: both`.
- CSS positioning: `static`, `relative`, `absolute`, `fixed`, `initial`, `inherit`. Layering with `z-index`.
- A full HTML + CSS project with images.
- A final review project combining all CSS concepts.

### Section 4 — Imported Notes (6 lectures, 46 min)

- Lecture 39 — introduction to Section 4 (theory, no code).
- Lecture 40 — Chrome Developer Tools walk-through on the myTunes site.
- Lecture 41 — deploying a website for free on Netlify and GitHub Pages.
- Lecture 42 — earning money from web design skills (theory, no code).
- Lecture 43 — Accessibility and SEO applied to a Netflix landing-page clone.
- Lecture 44 — installing the NVDA Developer Toolkit for blind developers.

### Section 5 — Full Design Project (11 lectures, 1 hr 20 min)

- A complete professional website built from scratch with HTML5 and CSS3.
- Responsive design for desktop, tablet, and mobile.
- Combining all skills into one real-world project.

---

## What You Will Learn

- Design and build professional websites from scratch with HTML5 and CSS3.
- Write standards-compliant HTML that appears in search engines.
- Build responsive websites that work on any screen size.
- Deploy a website online for free using multiple methods.
- Start working in the web design market.

---

## Technologies Used

- **HTML5** — builds the page structure.
- **CSS3** — styles the page and handles layout.

---

## How to Use This Repository

1. Clone or download the repository to your computer.
2. Open the matching note file under `lectures/sectionN/` (sections 1–4) and read the intro block and inline Arabic comments.
3. Open the linked practice project under `code/sectionN/` in your editor, then open `index.html` in a browser to see the result.
4. Compare with the teacher's original files under `web code/` whenever you need the exact course bundle.

---

## Accessibility Note

This README uses simple English and a clear heading hierarchy — it works well with screen readers such as NVDA (Windows), VoiceOver (macOS / iOS), TalkBack (Android), and Orca (Linux).

The `lectures/` text files are also structured for screen reader use: important lines carry Arabic HTML/CSS comments that describe what each line does.
