# Ayush Kumar Ubnare — Portfolio

Static portfolio site (HTML, CSS, JavaScript). No build step, no server, so it runs free on GitHub Pages.

## Publish on GitHub Pages (5 minutes)
1. Create a new **public** repository on GitHub, e.g. `portfolio`.
2. Upload everything in this folder (drag and drop on the repo page → *Commit changes*).
3. Go to **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)` → Save.
4. After about a minute your site is live at `https://YOUR-USERNAME.github.io/portfolio/`.
   (Name the repo `YOUR-USERNAME.github.io` to get the shorter `https://YOUR-USERNAME.github.io/`.)

## After it is live — replace the placeholder URL
Search for `YOUR-USERNAME` and replace it with your real address in:
`index.html` (canonical, og:image, og:url, JSON-LD), `sitemap.xml`, `robots.txt`.
Otherwise the LinkedIn/WhatsApp share preview image will not show.

## Updating content (no coding)
Everything (text, skills, experience, projects, blog posts) lives in **`js/content.js`**.
On GitHub open the file → pencil icon → edit → *Commit changes*. Live in ~1 minute.
Replace the resume with a new PDF using the same file name in `assets/`.
Replace the photo with `assets/photo.jpg` (portrait 4:5, ~800×1000).

## Contact form
Without setup the form opens the visitor's email app. For a real form: create a free form at formspree.io (or web3forms.com), paste the endpoint in `formEndpoint` in `js/content.js`.
Spam protection: hidden honeypot field + Formspree/Web3Forms spam filtering.

## Analytics
Free and privacy-friendly: create an account at goatcounter.com and put your code in `goatCounter` in `js/content.js`.

## Google Search Console
1. Open search.google.com/search-console → add your site URL.
2. Choose the *HTML tag* method, copy the tag, uncomment the `google-site-verification` line in `index.html` and paste your code.
3. Submit `sitemap.xml`.

## Custom domain (optional, ~₹800/year)
Buy a domain, then Settings → Pages → Custom domain, and add the DNS records GitHub shows. HTTPS is automatic.

## Honesty rule
Keep every claim real. Add new skills, certificates and project results only when you can show or explain them in an interview.
