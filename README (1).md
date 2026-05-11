# Paraform Case Study — Publishing Walkthrough

## What's in this bundle

Three files that together form one deliverable:

- **`index.html`** — Landing page · pick Part 01 or Part 02
- **`part1_recruiter_icp.html`** — Part 01 · Recruiter ICP (21 recruiters · 4 archetypes · 2 GTM moves)
- **`part2_candidate_eval.html`** — Part 02 · Pipeline evaluation (30 candidates · 9 actions · 4 archetypes)

## Goal: one shareable URL for Andrew

After this walkthrough, you'll have a URL like `https://yourusername.github.io/paraform-case/` that you can send Andrew. He clicks → lands on `index.html` → clicks into either part. All links work, no zips, no PDFs.

---

## Setup steps (~5 min, one time)

### 1. Create the GitHub repo

- Go to **github.com → green "New" button** (top-left of left sidebar)
- Repository name: `paraform-case` (this becomes part of the URL)
- Visibility: **Public** (required for free GitHub Pages)
- Check **"Add a README file"** so the repo isn't empty
- Click **Create repository**

### 2. Upload your three files

- On your new repo page, click **"Add file" → "Upload files"**
- Drag-and-drop from `/mnt/user-data/outputs/`:
  - `index.html`
  - `part1_recruiter_icp.html`
  - `part2_candidate_eval.html`
- Scroll down, click **"Commit changes"**

### 3. Turn on GitHub Pages

- Click **Settings** (top-right of repo page)
- Left sidebar → **Pages**
- Under "Build and deployment":
  - **Source**: Deploy from a branch
  - **Branch**: `main` · folder: `/ (root)`
  - Click **Save**

### 4. Wait ~1–2 minutes, then visit

- The page will show: "Your site is live at https://**yourusername**.github.io/paraform-case/"
- Click that URL → confirms it works
- Internal nav between Part 01 ↔ Part 02 should all work

---

## What you share with Andrew

Just one URL:

```
https://yourusername.github.io/paraform-case/
```

No GitHub access needed. No download. He clicks → reads.

---

## Updating later (if needed)

Resist the urge to keep tweaking after sharing. But if you do need a fix:

- Go to your GitHub repo → click the file → click the **pencil** icon
- Paste the updated content → "Commit changes"
- ~1 minute later, the live site updates

---

## Troubleshooting

- **404 after 5 minutes**: Pages takes 2–10 min on first deploy. Refresh.
- **Links don't work**: Confirm filenames are lowercase and exact: `index.html`, `part1_recruiter_icp.html`, `part2_candidate_eval.html`.

---

## Snapshot moment

Once you send Andrew the URL: **stop editing**. The version he reads should be the version he discusses. Live edits during prep create inconsistencies you'll have to explain.
