# Your Academic Website — GitHub Setup Instructions

## Files in this folder

| File | What it is |
|---|---|
| `index.html` | Home page |
| `research.html` | Research page |
| `teaching.html` | Teaching page |
| `cv.html` | CV page |
| `assets/css/style.css` | All the visual styling — you don't need to edit this |
| `assets/img/` | Put your headshot here (name it `photo.jpg`) |
| `assets/cv.pdf` | Put your CV PDF here (name it `cv.pdf`) |

---

## How to put this on GitHub Pages (step by step)

### Step 1 — Create a new GitHub repository
1. Go to github.com and sign in.
2. Click the **+** icon (top right) → **New repository**.
3. Name it exactly: `yourusername.github.io` (replace with your actual GitHub username).
4. Set it to **Public**. Click **Create repository**.

### Step 2 — Upload all the files
1. In your new empty repo, click **"uploading an existing file"** (the link in the middle of the page).
2. Drag and drop ALL the files and folders from this folder into the upload window.
   - Make sure the folder structure is preserved: `assets/css/style.css` and `assets/img/` should be inside an `assets` folder.
3. Click **"Commit changes"** at the bottom.

### Step 3 — Turn on GitHub Pages
1. Click **Settings** (top menu of your repo).
2. Click **Pages** in the left sidebar.
3. Under "Build and deployment," set Source to **"Deploy from a branch"**, Branch to **main**, folder to **/ (root)**.
4. Click **Save**.
5. Wait 2–3 minutes, then visit `https://yourusername.github.io` — your site is live.

---

## What to edit (checklist)

All edits are done the same way: open the file in GitHub → click the pencil icon → edit → Commit changes.

- [ ] Replace every `[Your Name]` with your actual name (in all 4 HTML files)
- [ ] Replace `youremail@gwu.edu` with your real email (in `index.html`)
- [ ] Add your photo: upload `photo.jpg` to `assets/img/`, then in `index.html` delete the photo-placeholder div and uncomment the `<img>` line
- [ ] Add your CV PDF: upload it to `assets/` as `cv.pdf`
- [ ] Fill in your dissertation/book project description in `research.html`
- [ ] Add publications in `research.html` (or delete that section for now)
- [ ] Add works in progress in `research.html`
- [ ] Write your teaching philosophy in `teaching.html`
- [ ] Fill in your courses in `teaching.html`
- [ ] Fill in all CV details in `cv.html`
- [ ] Update your expected graduation year in `cv.html`

---

## Optional: add a custom domain
If you buy a domain (e.g. yourname.com), add a file called `CNAME` to your repo root containing just your domain name (no https://, just: `yourname.com`), then point your domain's DNS to GitHub Pages. GitHub's Pages settings page shows you the exact DNS records to add.
