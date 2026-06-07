# Project MXSA — Website

A premium fundraising website for **Project MXSA** — a bionic arm with AI neural control and haptic sensation.

---

## 🚀 Deploy to GitHub Pages

### Step 1 — Extract the ZIP
Unzip the file anywhere on your computer.

### Step 2 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click **+ New repository**
3. Name it anything (e.g., `project-mxsa`)
4. Set it to **Public**
5. Click **Create repository**

### Step 3 — Upload the Files
In your new repo, click **Add file → Upload files** and drag in:
- `index.html`
- the `images/` folder (with your photos inside)

Click **Commit changes**.

### Step 4 — Enable GitHub Pages
1. Go to **Settings → Pages** in your repository
2. Under **Source**, select **Deploy from a branch**
3. Choose **main** branch and **/ (root)** folder
4. Click **Save**

After 1–2 minutes your site will be live at:
`https://YOUR-USERNAME.github.io/REPO-NAME/`

---

## 📷 Adding Your Photos

1. Copy your photo files into the `/images` folder
2. Open `index.html` in any text editor (Notepad, VS Code, etc.)
3. Find the **Gallery** section (search for `GALLERY ITEM`)
4. For each photo slot, uncomment the `<img>` line by removing `<!--` and `-->`
5. Update the `src` to match your file name (e.g., `images/photo1.jpg`)
6. Delete the `<div class="g-ph">` placeholder block below it

**Example — Before:**
```html
<!-- <img src="images/photo1.jpg" alt="Project MXSA — Build Photo 1"> -->
<div class="g-ph">...</div>
```

**Example — After:**
```html
<img src="images/photo1.jpg" alt="Project MXSA — Build Photo 1">
```

**For the Hero image** (the big photo on the front page):
Search for `Add Hero Image` and uncomment that `<img>` line, then delete the `<div class="h-ph">` block.

---

## 💳 UPI Payment

The UPI ID is already set to: **maxsharma0137@fam**

The QR code is auto-generated on page load. The "Open UPI App" button works on mobile — it will open PhonePe, Google Pay, Paytm, BHIM, or any installed UPI app automatically.

---

## 📁 File Structure

```
project_MXSA/
├── index.html      ← Main website (everything is in here)
├── images/         ← Put your photos in this folder
│   └── .gitkeep
└── README.md       ← This file
```

---

## ✏️ Customizing Content

Everything is in `index.html`. Open it in a text editor and search for these to update them:

| What to change | Search for |
|---|---|
| Project description | `next-generation bionic arm` |
| Funding goal | `₹5,00,000` |
| Stats (hours, models, etc.) | `data-val=` |
| Milestones | `₹50,000 — Prototype` |
| FAQ answers | `faq-a-in` |
| Your name / contact | Footer section |

---

**Built for Project MXSA · Made in India 🇮🇳**
