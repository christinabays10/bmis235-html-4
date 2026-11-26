# BMIS 235 · HTML-4 · Path 2

**Name:** Christina Bays
**GU username:** cbays2

**My live site:** https://bmis235-html-4.christinabays10.workers.dev

## What's in this folder

- `index.html`: Home page, with an interactive "click a place" fact box
- `christina.html`: Aran Islands
- `christinab.html`: Cliffs of Moher
- `christinabays.html`: Guinness Storehouse
- `learn.html`: my learning tool, a practice game for links and file paths
- `styles.css`: my brand (font, colors, menu). Every page links to it.
- `img/`: my menu images

## My path: Path 2

**Why I picked Path 2:**

I wanted to learn how to use AI tools to build and fix a real website, since that's a skill employers want.

## By hand vs. by AI

**By hand:**
- The four pages (Home, Aran Islands, Cliffs of Moher, Guinness Storehouse) and what they say
- The image menu, including making the menu images
- `styles.css` with my brand colors and font
- The author comment, author meta tag and footer on each page

**By AI:**
- The interactive fact box on the Home page (the bouncing place buttons and fun facts), which I pasted into `index.html`
- Changed the course label in each page's author comment from HTML-3 to HTML-4
- Fixed the Home page fact box so its styles apply (wrapped it in `<div class="showcase">`)
- Built `learn.html`, the learning tool (see below)
- Added a "Learn Links" button to the menu on every page
- Changed the Home page text to "Ireland is part of the EU." (Ireland is not part of the UK)
- Fixed three bugs in `styles.css`: a missing semicolon that switched off my background and text colors, a 7-digit heading color, and a menu image too wide for phones
- Drafted this README. I wrote the answers in the blanks.

**How I checked the AI's work:**

I opened the live site after each change, clicked through every page and link, played the Learn Links game including wrong answers, and read Claude's explanations of what it changed before merging.

## My learning tool: Learn Links (`learn.html`)

Learn Links is a practice game that teaches how `<a href>`, `<img src>` and `<link href>` find other files. It uses my own site's file tree: `index.html`, my three place pages, `styles.css` and the `img` folder. For each question, the tree highlights the page I'm editing and the file I'm linking to.

There are 8 questions. Some are multiple choice and some I type. Each answer gets instant feedback that explains why it works or doesn't, plus the steps the browser follows to find the file. The questions cover:

1. Linking to a page in the same folder (`christinab.html`)
2. Typing a link back to Home (`index.html`, not `home.html`)
3. Going into a folder (`img/screenshot4.png`)
4. Linking the stylesheet (`styles.css`)
5. Exact spelling (my real file is `screentshot1.png`)
6. Capital letters (they matter on a web server)
7. Linking to another website (`https://www.cliffsofmoher.ie`)
8. Going up a folder with `../`

**Why this tool fits how I learn:**

I learn best by practicing and getting instant feedback, so a quiz with my own file names helps me remember how links and paths work.

**Classmate tester:** None
