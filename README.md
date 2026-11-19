# Employability Skills Webpage — Ion-mirel Gozgar (25011328)

A personal **Employability Skills Webpage** built for Assessment Task 3 (LO4): *demonstrate attainment of employability skills in developing and presenting a new venture.* The venture used throughout is **EcoBite**, a surplus-food meal-box concept.

The site is a static website (HTML, CSS, JavaScript) with no build step. It runs by opening `index.html` or by publishing it free on **GitHub Pages**.

---

## What is in this folder

```
employability-skills-webpage/
├── index.html          Main webpage (all content)
├── css/
│   └── style.css       Styles (responsive, light theme)
├── js/
│   └── main.js         Menu, scroll reveal, animated progress bars
├── images/             All evidence pictures (SVG)
│   ├── profile.svg
│   ├── hero-bg.svg
│   ├── venture-pitch.svg
│   ├── market-research.svg
│   ├── business-model-canvas.svg
│   ├── swot.svg
│   ├── gantt-chart.svg
│   ├── financials.svg
│   ├── team-workshop.svg
│   ├── networking.svg
│   ├── prototype.svg
│   ├── leadership.svg
│   ├── reflection.svg
│   └── digital-poster.svg
├── .nojekyll           Tells GitHub Pages to serve files as-is
├── .gitignore
└── README.md           This file
```

---

## View it on your own computer first

Double-click `index.html`. It opens in your browser with everything working. No internet or install needed.

---

## Publish it on GitHub Pages (free web link)

You do not need the command line. The upload method below is the easiest.

### Option A — Upload through the GitHub website (recommended)

1. Go to <https://github.com> and sign in (create a free account if needed).
2. Click the **+** at the top right → **New repository**.
3. Name it `employability-skills` (or anything). Set it to **Public**. Click **Create repository**.
4. On the new repo page, click **uploading an existing file**.
5. Open this `employability-skills-webpage` folder on your computer, select **everything inside it** (the `index.html`, the `css`, `js`, `images` folders, and the dot-files), and drag it all into the browser upload box.
6. Scroll down and click **Commit changes**.
7. Go to the repo's **Settings** → **Pages** (left menu).
8. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose branch **main** and folder **/ (root)**, then **Save**.
9. Wait about one minute, then refresh. GitHub shows your live link, for example:
   `https://YOUR-USERNAME.github.io/employability-skills/`

Share that link in your submission.

### Option B — Using Git on the command line

```bash
cd employability-skills-webpage
git init
git add .
git commit -m "Employability Skills Webpage"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/employability-skills.git
git push -u origin main
```

Then do steps 7–9 above to turn on Pages.

---

## Replace the sample pictures with your own real evidence

Every image is in the `images/` folder. To use your own photo, poster, or screenshot:

1. Rename your file to match the one you are replacing, for example `market-research.svg` → save your photo as `market-research.jpg`.
2. Put it in the `images/` folder.
3. In `index.html`, find the matching `<img src="images/market-research.svg" ...>` and change `.svg` to `.jpg` (or `.png`).
4. Save, re-upload to GitHub, and the new picture shows.

The page is designed so there are **no empty image slots** — if you replace nothing, it still looks complete.

### Adding a video
To add a video as evidence, put the file in a new `videos/` folder and paste this where you want it in `index.html`:

```html
<video controls width="100%" src="videos/your-pitch.mp4"></video>
```

---

## Editing the text

Open `index.html` in any text editor (Notepad, VS Code). The content is plain text between the tags. Change the venture name, the figures, or the reflection to match your own work. The name and ID appear in the hero section and footer.

---

## Credits
Built as coursework evidence for LO4. Sample evidence graphics are original SVGs included in `images/`.
