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
├── lectures/      ← my Arabic study notes (.txt) for each lecture
└── web code/      ← original source files provided by the teacher
```

### code/

Student practice projects organised by section and lecture number.

```
code/
├── section1/           lectures 4 – 6   (lectures 1–3 had no code exercise)
├── section2/           lectures 8 – 18  (lectures 7 and 17 were theory-only)
└── section3/           lectures 20 – 38 (lectures 23, 24, 31, 32, 33 were theory-only; 39 not yet saved)
```

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
- Coverage mirrors `code/` exactly: sections 1–3, same lecture numbers, same gaps.
- Lecture 20 has three separate note files (one per CSS method: inline, internal, external).
- Lecture 18 has two files (blog and blog1 matching the two HTML files in `code/section2/web site 18/`).

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
- Section 4 and Section 5 teacher materials exist here only — there is no matching `code/section4` or `code/section5` folder.

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

- Earning money from web design skills.
- Deploying a website for free with Netlify and GitHub Pages.
- A hamburger-menu overlay project using CSS checkboxes and transitions.

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
2. Open the matching note file under `lectures/sectionN/` and read the intro block and inline Arabic comments.
3. Open the linked practice project under `code/` in your editor, then open `index.html` in a browser to see the result.
4. Compare with the teacher's original files under `web code/` whenever you need the exact course bundle.

---

## Accessibility Note

This README uses simple English and a clear heading hierarchy — it works well with screen readers such as NVDA (Windows), VoiceOver (macOS / iOS), TalkBack (Android), and Orca (Linux).

The `lectures/` text files are also structured for screen reader use: important lines carry Arabic HTML/CSS comments that describe what each line does.
