# Mohamed Zaghoo — personal website

A standalone, responsive port of https://zaghoo.wixsite.com/mysite-1, captured on 18 November 2026. Plain HTML and CSS; no package installation or build step. Includes six main pages, five research articles, local images and the latest reviewed CV PDF.

## Preview

Open `index.html` directly, or run `python3 -m http.server 8000` in this folder and visit http://localhost:8000.

## Publish on GitHub Pages

1. Create a GitHub repository. For a personal root website, name it `YOUR-USERNAME.github.io`; otherwise choose a project name.
2. Upload the **contents of this folder** to the repository root. `index.html`, `style.css`, `assets/` and `.nojekyll` should be at the top level, not inside another folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then **main** and **/(root)**, and save.
5. GitHub will show the published address when deployment completes. A personal root site uses `https://YOUR-USERNAME.github.io/`; a project site uses `https://YOUR-USERNAME.github.io/REPOSITORY/`.

All internal links and asset references are relative, supporting both arrangements.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Edit

Edit each page's HTML for content and `style.css` for appearance. The shared header, navigation and footer are repeated in each page; update them consistently. The files in `assets/` use stable names; the PDF is the latest reviewed CV (18 November 2026). Update all CV links if you rename or replace it.

## Migration notes and review items

- Preserved the astronomy banner, headshot, academic visual style, biography, education, research interests, 12 listed journal publications, two in-preparation entries, eight news items and five blog posts.
- Homepage and About Me now reflect AMWAL, Mercor, Madena AI, independent Arabic reward-reliability work, and the latest reviewed CV. Rochester is a former role (2017–2021). Header, footer and contact details are aligned with the current CV.
- Scientific article dates, claims and publication statuses remain historical; papers marked submitted or in preparation have not been re-verified.
- Removed Wix advertising, placeholder links to Wix social profiles, and dummy Wix publication links.
- Replaced the Wix contact form with an email link. It opens the visitor's email app; it does not submit or store messages.
- Blog articles are independent local HTML pages. Wix login, comments, likes, view counters and blog search were not carried over.
- Replaced the animated homepage slideshow with a static research highlight. About-page embedded media widgets were not carried over; the source lab photographs are included.
- Images and CV are stored locally. External news/article links remain external; their destinations have not all been checked for availability.
- This package does not change or redirect the original Wix site ; publication destination is https://mzaghoo.github.io/.

## Validation

Checked all local page/asset references, downloaded asset formats, article text preservation, and browser rendering of the main sections plus a research article. Checked narrow-screen layouts for horizontal overflow and missing loaded images. No build tools, remote fonts or JavaScript runtime are required.
