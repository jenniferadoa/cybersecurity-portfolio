# Jennifer Addo — Cybersecurity Project Portfolio

A project-first cybersecurity portfolio designed for free deployment with **GitHub Pages**.

## What is included

- `index.html` — project-focused homepage
- `projects/` — four detailed cybersecurity case studies
- `styles.css` — responsive dark cybersecurity design
- `script.js` — mobile navigation, subtle scroll reveals, sticky-header behaviour
- `assets/favicon.svg` — lightweight site favicon
- `404.html` — GitHub Pages-friendly fallback page

There is **no build step**, package manager or framework dependency.

## Deploy for free with GitHub Pages

1. Create a new public GitHub repository, for example `cybersecurity-portfolio`.
2. Upload all files and folders from this project **without changing the folder structure**.
3. Commit the files to the `main` branch.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
6. Save. GitHub will provide your public site URL once Pages is enabled.

If your repository is named `YOUR-USERNAME.github.io`, the site will be available at:

`https://YOUR-USERNAME.github.io/`

Otherwise it will usually be:

`https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

The site uses relative links, so either option works.

## Before publishing

### 1. Add your real project repository links
The supplied CV confirms that some projects are documented in GitHub, but no repository URLs were provided. The public-facing site therefore does **not** invent any links.

Once you have the URLs, useful places to add them are:
- the relevant project case-study page,
- the project card on the homepage,
- or a small “View repository” button inside each case study.

### 2. Add real screenshots only
The portfolio intentionally does not fabricate screenshots or evidence. Add genuine screenshots from:
- your incident-response lab,
- phishing evidence folder,
- Autopsy investigation,
- Wireshark captures.

A simple pattern is:

```html
<figure class="case-panel">
  <img src="../assets/your-screenshot.png" alt="Describe exactly what the screenshot shows">
  <figcaption>Short explanation of why this evidence matters.</figcaption>
</figure>
```

### 3. Add your LinkedIn / GitHub profile
Only an email address was available from the supplied CV. Add your exact profile URLs when ready.

## Design intent

This is intentionally **not a CV website**. Employment history, long education lists and resume-style timelines are omitted. The homepage prioritises:
1. real projects,
2. investigation method,
3. evidence quality,
4. tools used,
5. what was learned.

## Customisation

The main colours are CSS variables at the top of `styles.css`. You can change the site accent without editing every component.

The site also respects `prefers-reduced-motion` for users who disable animations at operating-system level.

## Recommended next upgrade

The strongest improvement would be to add **real project screenshots** and direct GitHub repository links. That would turn the portfolio from a strong written case-study site into a stronger evidence portfolio.
