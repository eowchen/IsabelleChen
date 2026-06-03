# Isabelle Chen — Website

**isabelleachen.com** (or your domain)  
Built by: Liz / Your Agency Name  
Hosted: GitHub Pages (free)

---

## Folder Structure

```
isabelle-chen/
├── index.html              ← The entire website (all 6 pages)
├── css/
│   └── style.css           ← All styling
├── js/
│   └── main.js             ← Navigation, gallery, interactions
├── images/
│   ├── hero/               ← Drop hero photos here
│   │   ├── hero-portrait.jpg    ← Main homepage hero (portrait/vertical)
│   │   └── isabelle-bw.jpg      ← About page sidebar photo (b&w works great)
│   └── gallery/            ← Drop gallery photos here
│       ├── photo-01.jpg    ← Largest tile (5 cols × 3 rows)
│       ├── photo-02.jpg
│       └── ... up to photo-12.jpg
└── README.md
```

---

## Before Going Live — Checklist

### 1. Add Photos
- Copy Isabelle's photos into `images/hero/` and `images/gallery/`
- Name them exactly as shown above (or update the `src` attributes in index.html)
- Gallery supports 12 photos in a mosaic layout

### 2. Add GoFundMe URL
In `index.html`, search for `YOUR_GOFUNDME_URL_HERE` and replace with the real link:
```html
href="https://www.gofundme.com/f/isabelle-chen-worlds-2026"
```

### 3. Set Up Contact Form (Free)
1. Go to https://formspree.io and create a free account
2. Create a new form, set the email to `isabelleachen@gmail.com`
3. Copy your form ID (looks like `xabcdefg`)
4. In `index.html`, find `YOUR_FORM_ID` and replace it
5. Free tier: 50 submissions/month — plenty for a personal site

---

## Deploying to GitHub Pages (Free Hosting)

### Step 1 — Create GitHub Account
Go to https://github.com and sign up (free)

### Step 2 — Create a New Repository
- Click the green "New" button
- Name it: `isabelle-chen` (or `isabelleachen.com`)
- Set it to **Public**
- Click "Create repository"

### Step 3 — Upload the Files
- Click "uploading an existing file"
- Drag the entire `isabelle-chen` folder contents
- Click "Commit changes"

### Step 4 — Enable GitHub Pages
- Go to Settings → Pages
- Source: "Deploy from a branch"
- Branch: `main`, folder: `/ (root)`
- Click Save
- Your site goes live at: `https://yourusername.github.io/isabelle-chen`

### Step 5 — Connect GoDaddy Domain
In GoDaddy DNS settings, add:

| Type  | Name | Value                          | TTL  |
|-------|------|-------------------------------|------|
| A     | @    | 185.199.108.153               | 600s |
| A     | @    | 185.199.109.153               | 600s |
| A     | @    | 185.199.110.153               | 600s |
| A     | @    | 185.199.111.153               | 600s |
| CNAME | www  | yourusername.github.io        | 600s |

Then in GitHub Pages settings, add her custom domain (e.g. `isabelleachen.com`)

DNS changes take 10 minutes to 48 hours to propagate.

---

## Updating the Site Later

To update content (press releases, photos, etc.):
1. Go to github.com → your repository
2. Click the file you want to edit
3. Click the pencil icon (Edit)
4. Make changes → Commit
5. Site updates automatically in ~1 minute

---

## Total Cost
| Item | Cost |
|------|------|
| GitHub Pages hosting | **Free** |
| Formspree contact form | **Free** (50/mo) |
| GoDaddy domain | ~$15–20/year (already paying) |
| **Total/month** | **$0** |
