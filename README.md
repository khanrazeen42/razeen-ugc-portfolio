# Razeen UGC Portfolio

Simple static UGC portfolio site (HTML + CSS), ready for GitHub Pages.

## Local preview

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to GitHub Pages

1. Create a new GitHub repo (e.g. `razeen-ugc-portfolio` or `yourusername.github.io`).
2. Push this folder to the repo's default branch.
3. In the repo: **Settings → Pages → Build and deployment**.
4. Set **Source** to **Deploy from a branch**.
5. Choose branch `main` (or `master`) and folder `/ (root)`.
6. Save — your site will be at:
   - `https://<username>.github.io/<repo>/`  
   - or `https://<username>.github.io/` if the repo is named `<username>.github.io`

## Customize

Edit `index.html` to update:

- Name and bio
- Brand partner names
- Work titles / descriptions
- Email and social links

To add real thumbnails, replace the `.work__thumb` gradient backgrounds in `styles.css` with `background-image: url("images/your-file.jpg")`, or swap the thumb `div`s for `<img>` tags.
