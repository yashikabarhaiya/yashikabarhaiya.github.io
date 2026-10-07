# Yashika Barhaiya — Portfolio Site

Personal portfolio for Yashika Barhaiya, Supply Chain Digital Transformation specialist.  
Built as a single `index.html` file — no build tools, no dependencies, no framework.

---

## Editing the page

Open `index.html` in any browser. Click **Edit page** (bottom-right corner).

- Every text block becomes clickable and editable in place
- Changes auto-save to your browser's local storage as you type
- Click **Done editing** when finished
- Use **Download HTML** to export a clean, deploy-ready `index.html` (editor UI stripped out)
- Use **Reset changes** to go back to the original content

> The downloaded file is what you deploy — not this one. This one keeps the editor in it.

---

## Deploying to GitHub Pages

### Step 1 — Create a GitHub account

Go to [github.com](https://github.com) and sign up if you don't have an account.

---

### Step 2 — Create a new repository

1. Click the **+** icon (top right) → **New repository**
2. Name it exactly: `yashikabarhaiya.github.io`  
   *(Replace `yashikabarhaiya` with your actual GitHub username)*
3. Set visibility to **Public**
4. Leave everything else as default
5. Click **Create repository**

> The repository name must follow the pattern `yourusername.github.io` for GitHub Pages to work automatically.

---

### Step 3 — Upload your file

**Option A — via the GitHub website (easiest):**

1. Open your new repository
2. Click **uploading an existing file** (or drag and drop)
3. Upload the `index.html` you downloaded from the editor
4. Scroll down, click **Commit changes**

**Option B — via Git (if you have Git installed):**

```bash
git clone https://github.com/yourusername/yourusername.github.io
cd yourusername.github.io
# Copy your downloaded index.html into this folder
git add index.html
git commit -m "Add portfolio"
git push
```

---

### Step 4 — Enable GitHub Pages

1. Go to your repository → **Settings** tab
2. In the left sidebar, click **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Branch: `main` / Folder: `/ (root)`
5. Click **Save**

---

### Step 5 — Wait ~60 seconds, then visit your site

Your site will be live at:

```
https://yourusername.github.io
```

GitHub sends an email when the deployment completes. If it doesn't load immediately, wait a minute and refresh.

---

## Making changes after deployment

1. Open `index.html` in your browser
2. Click **Edit page**, make your changes
3. Click **Download HTML**
4. Upload the new `index.html` to your GitHub repository (replacing the old one)
5. GitHub Pages redeploys automatically — usually within 30 seconds

---

## File structure

```
yashikabarhaiya.github.io/
└── index.html     ← the entire site (HTML + CSS + JS, self-contained)
```

No other files are needed. All fonts load from Google Fonts via CDN.

---

## Placeholders to fill in before going live

Search the file for `placeholder-note` to find everything that still needs real content:

| Section | What's missing |
|---|---|
| Hero / Contact | Your actual email address |
| Contact | Your phone number |
| Education | University name for B.Tech |
| Certifications | Year of o9 Advanced Technical Expert cert |
| Work (EY) | A quantified metric for that engagement |
| Work (Ralph Lauren PM) | A quantified metric for that engagement |
| Experience (Accenture Tech 2017–2019) | Role details and contributions |
| Approach | Sixth principle (title + description) |

---

*Last updated: October 2026*
