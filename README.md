# Prem Chand Aravapalli — Static Resume Website

A premium, animated, dependency-free static resume site built from the provided resume content.

## Files
- `index.html` — the full static site
- `Prem_Chand_Aravapalli_Resume.pdf` — downloadable source resume
- `README.md` — deployment notes

## Deploy on GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html`, `Prem_Chand_Aravapalli_Resume.pdf`, and `README.md`.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select the main branch and `/root`.
6. Save.

## Deploy on Netlify
1. Create a new site.
2. Drag the whole folder into the Netlify deploy area, or connect the GitHub repository.
3. No build command is required.
4. Publish directory: `/`.

## Deploy on Cloudflare Pages
1. Create a Pages project and connect the GitHub repository.
2. Framework preset: **None**.
3. Build command: leave empty.
4. Build output directory: `/`.
5. Deploy.

## Notes
- The site intentionally uses no framework or build step.
- Animations respect `prefers-reduced-motion`.
- Replace the LinkedIn link in `index.html` with your actual LinkedIn profile URL.
