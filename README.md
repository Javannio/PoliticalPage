# The Campaign Dispatch
### Political Media in the Internet Age

A single-page interactive website based on Chapter 10 of the *Routledge Handbook of Political Management* — **"The New Media in Political Campaigns: What the Future Holds"** by Peter Fenn.

**Live site:** `https://YOUR-USERNAME.github.io/campaign-dispatch`

---

## What's on the site

- **Hero & Stats** — Key data on internet adoption and political media shifts
- **Three Challenges** — Audience fragmentation, rising ad costs, media saturation
- **The Internet Advantage** — Internet advertising, e-mail campaigns, and candidate websites
- **Interactivity & Customisation** — The two strategic pillars of digital campaigning
- **Cost Management** — Comparing online vs. TV ad spend
- **Newsletter Signup** — Subscribe form revealing *The Campaign Dispatch* digital newspaper
- **Page-Flip Newspaper** — A 3-page interactive newspaper with animated page-turn transitions
- **QR Code** — Auto-generated QR pointing to the live site for classroom sharing

---

## Deploy to GitHub Pages (step by step)

### 1. Create a new GitHub repository

Go to [github.com/new](https://github.com/new) and create a repo named `campaign-dispatch` (or any name you like). Leave it public.

### 2. Upload the files

**Option A — via GitHub website (easiest):**
1. Open your new repo on GitHub
2. Click **"Add file" → "Upload files"**
3. Drag and drop `index.html` and `README.md`
4. Click **"Commit changes"**

**Option B — via Git (if you have it installed):**
```bash
git init
git add index.html README.md
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/campaign-dispatch.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. In your repo, go to **Settings → Pages**
2. Under **"Source"**, select **"Deploy from a branch"**
3. Choose branch: **`main`**, folder: **`/ (root)`**
4. Click **Save**

### 4. Your site is live

After ~60 seconds, your site will be available at:
```
https://YOUR-USERNAME.github.io/campaign-dispatch
```

Copy this URL and paste it into the QR code section of the site — the QR will auto-update to encode it.

---

## Using the QR Code in class

1. Deploy the site (steps above) and copy the live URL
2. Open the site and scroll to the **QR Code** section
3. The QR auto-generates from your live URL
4. Click **"↓ Download QR"** to save as PNG
5. Display it on a projector or print it — classmates scan to open the newspaper instantly

---

## Files

| File | Description |
|------|-------------|
| `index.html` | The complete site — all HTML, CSS, and JS in one file |
| `README.md` | This file |

---

*Based on: Fenn, P. "The New Media in Political Campaigns." In Johnson, D.W. (ed.) Routledge Handbook of Political Management. Routledge, 2009.*
