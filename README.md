# Tech Badgers — Cybersecurity Portfolio

A responsive, static HTML/CSS/JavaScript portfolio website for Tech Badgers, with cybersecurity as the primary focus and enterprise IT experience as supporting credibility.

## Files

- `index.html` — page content and navigation
- `styles.css` — responsive styling and teal/grey/white design system
- `script.js` — mobile navigation, current year, and email-based contact form
- `assets/` — reserved for a future professional headshot, logo, and project visuals

## Preview locally

Open `index.html` in a browser. For a local server, from this folder run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

1. Sign in to GitHub and create a new **public** repository, for example `tech-badgers-portfolio`.
2. Upload `index.html`, `styles.css`, `script.js`, this README, and the `assets` folder to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish. The site URL will appear in Settings → Pages.

If you want a URL like `https://YOUR-USERNAME.github.io/`, name the repository exactly `YOUR-USERNAME.github.io`. Otherwise, a project site will usually be at `https://YOUR-USERNAME.github.io/tech-badgers-portfolio/`.

## Before launch

- Add a real professional portrait only when ready; no fabricated portrait is included.
- Confirm all dates, role titles, and credential details.
- Add sanitized project details and evidence when ready; project cards are placeholders by design.
- The contact form opens a pre-filled email to `info@techbadgers.com`; it does not store or submit data to a server. Test it on devices with a configured email application.
- Add a real LinkedIn URL when ready.
- If using `techbadgers.com` as a custom domain, configure the domain in GitHub Pages and update DNS records at your domain provider. GitHub Pages custom-domain setup and HTTPS can take some time to propagate.
- Consider adding a privacy policy and analytics only if needed.

## Accuracy note

Cybersecurity project descriptions are intentionally general until project details can be verified and safely shared. VAPT is described as authorized and scope-limited. CISA is shown as pursuing, not as an earned designation.
