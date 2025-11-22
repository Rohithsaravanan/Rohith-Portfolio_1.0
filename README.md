# Rohith Saravanan — GitHub Pages Portfolio

This is a single-page portfolio site built with pure HTML & CSS so it can be easily hosted on **GitHub Pages**.

## Files
- `index.html` — main portfolio page
- `styles.css` — styling (light, modern UI)
- `Rohith_Saravanan_AB_Resume.pdf` — your resume (linked in multiple places)
- `README.md` — instructions

## Run locally
Just open `index.html` in a browser.

## Deploy to GitHub Pages

1. Create a new **public** repository, e.g. `rohith-portfolio`.
2. Put these files in the root of the repo:
   - `index.html`
   - `styles.css`
   - `Rohith_Saravanan_AB_Resume.pdf`
   - `README.md`
3. From that folder, run:

   ```bash
   git init
   git add .
   git commit -m "Add portfolio website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

4. In GitHub, go to **Settings → Pages**:
   - Set **Source** to `main` branch and `/ (root)`.
   - Click **Save**.

5. Your portfolio will be live at:

   `https://<your-username>.github.io/<repo-name>/`

For example, if your repo is `rohith-portfolio` and username is `Rohithsaravanan`, the URL will be:

`https://rohithsaravanan.github.io/rohith-portfolio/`
