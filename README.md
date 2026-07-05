# Manish Verma — Personal Website

A single-page professional profile (plain HTML/CSS, no build step). Theme: off-white, grey, and light-black.

## Folder layout

```
your-site/
├─ index.html          <- the website (already done)
├─ README.md           <- this file
└─ assets/
   ├─ profile.jpg      <- your headshot (add this)
   ├─ Manish_Verma_Resume.pdf
   ├─ Tech_Insights.pdf
   ├─ Tech Forecast.pdf
   ├─ Large Language Models Rewriting Pharma's Playbook.pdf
   ├─ Is Drug Discovery Undergoing a Revolution with Large Language Model.pdf
   ├─ Injector.pdf
   └─ Slime Mold.pdf
```

## Step 1 — Add your files
Copy the PDFs you already have into the `assets/` folder using the **exact names above**.
Add your headshot as `assets/profile.jpg`. (No photo? The site shows a clean "MV" monogram automatically.)

## Step 2 — Preview locally (optional)
Just double-click `index.html`, or run a tiny local server:
```
python -m http.server 8000
```
then open http://localhost:8000

## Step 3 — Deploy on Render (static site — free)
1. Put this whole folder in a **GitHub repo** (e.g. `manish-portfolio`).
2. Go to https://render.com → **New +** → **Static Site**.
3. Connect the GitHub repo.
4. Fill in:
   - **Build Command:** *(leave empty)*
   - **Publish Directory:** `.`  (a single dot — the folder that contains `index.html`)
5. Click **Create Static Site**. Render gives you a public link like
   `https://manish-portfolio.onrender.com` — anyone with the link can view your profile.

Every time you push to GitHub, Render redeploys automatically.

### No GitHub? Fastest alternative
Drag-and-drop the folder onto https://app.netlify.com/drop for an instant public link — same result, no repo needed.

## Editing later
- Text lives directly in `index.html` (search for the section you want).
- Colors are CSS variables at the top of `index.html` under `:root`.
