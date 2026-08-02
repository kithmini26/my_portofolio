# Vimarshana Kithmini — Portfolio

## What's new in this version
- Your photo is now embedded directly inside `index.html` (as base64) — it will NEVER fail to load,
  even if the `images` folder gets separated. No more broken image issue.
- Contact is now a real form (Name / Email / Message / Submit) matching the style you liked.
  Since this is a static site with no backend server, clicking Submit opens the visitor's email app
  with everything pre-filled, addressed to you. This works with zero setup. (If you later want a
  true "send without opening email app" form, services like Formspree.io offer a free tier — ask me
  and I can wire that in instead.)
- Phone number removed from Contact.
- "Visit Project" buttons removed from all 3 projects — now just visual, title, description, and tags.
- Footer redesigned with your name, tagline, and LinkedIn/GitHub icons.
- Certifications section now has 4 cards, two with "View Certificate" links to the actual PDFs you sent.

## Files
- `index.html` — the page (photo is embedded inside this file now)
- `style.css` — all styling
- `script.js` — footer year + contact form handler
- `Kithmini_CV.pdf` — your resume (downloadable from Hero and About)
- `certificates/Introduction_to_Software_Testing.pdf`
- `certificates/What_is_Software_Development.pdf`

## About adding real project screenshots
Right now, each project shows a colored gradient block with its name (since I don't have actual
screenshots of your projects). To swap in real screenshots:

1. Take a screenshot of each project running (or its GitHub repo page)
2. Save them as `images/loan-approval.png`, `images/utopia.png`, `images/smart-library.png`
3. Send them to me and I'll update the HTML to use `<img>` tags instead of the colored blocks —
   or, do it yourself: in `index.html`, find `<div class="project-visual project-visual-1">...</div>`
   and replace its contents with `<img src="images/loan-approval.png" alt="Loan Approval XAI">`
   (repeat for the other two, matching image filenames)

## Preview it right now
Just double-click `index.html` — no coding or terminal needed. The photo will show up immediately
since it's built into the file.

## Publish it — no terminal needed
1. Go to **github.com**, log in.
2. Click **+** (top-right) → **New repository** → name it `photofolio` → **Create repository**.
3. Click **uploading an existing file**.
4. Drag in ALL files/folders from this download (`index.html`, `style.css`, `script.js`,
   `Kithmini_CV.pdf`, `certificates/` folder).
5. Click **Commit changes**.
6. Go to **Settings → Pages** → under **Source**, choose **main** branch → **Save**.
7. After about a minute, your site is live at:
   ```
   https://kithmini26.github.io/photofolio/
   ```
