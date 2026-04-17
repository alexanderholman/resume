# Alexander Holman website

## Chosen stack

This site uses plain HTML, CSS, and a small amount of vanilla JavaScript.

The choice is deliberate: the site is fully static, simple to maintain, easy to deploy over basic hosting or FTP, and does not require a framework build step.

## How to run locally

Because the site is static, you can open `index.html` directly in a browser.

For a cleaner local workflow, run a simple local server from the repository root:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## How to edit the content later

- Main page content is in `index.html`
- Styling is in `resources/style/default.css`
- Small navigation behaviour is in `resources/script/default.js`
- The downloadable CV text file is `cv-20260417233906.txt`

### Typical content updates

- Update section copy directly in `index.html`
- Update contact links in the hero and contact section
- Replace the CV file and update its filename in `index.html` if you want a new timestamped version
- Adjust colours, spacing, or typography in `resources/style/default.css`

## Deployment

This site can be deployed as static files to basic web hosting, GitHub Pages, or FTP-based hosting.
