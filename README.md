# Alterstate website

Static website for GitHub Pages. No build, dependencies, API keys, forms, analytics, or cookies.

## Upload

Upload the CONTENTS of this folder to your GitHub Pages repository root (including .nojekyll and CNAME). Configure Pages to publish that branch and root folder. The CNAME file names alterstate.app; domain DNS must also be configured for your GitHub Pages account. Nothing has been published or changed in DNS by this build.

## Before launch

- Supply the complete app privacy policy. privacy.html currently covers only this website and clearly says the app policy is forthcoming. Do not use this as the App Store app privacy-policy URL until the complete policy is added.
- Review Wellness & Safety against your actual session content and launch markets.
- When Apple approves the app, replace the coming-soon message in index.html with your verified App Store URL and official Apple badge.

## Edit

index.html: homepage copy and screenshots.
style.css: responsive design.
wellness.html: wellness and listening safety notice.
privacy.html: website privacy notice, awaiting separate app policy.
assets/: supplied lettering, three unchanged screenshots, favicon, and original logo banner for future use.

SEO includes semantic headings, descriptions, canonical URLs, Open Graph text, sitemap, robots.txt, descriptive alt text, and lazy loading of secondary screenshots. Search placement is not guaranteed.

Preview with python3 -m http.server 4173 from this folder, then visit http://127.0.0.1:4173.
