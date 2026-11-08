# Nexus — GitHub Pages Website

This is a static website built with HTML, CSS and JavaScript. It can be hosted for free with GitHub Pages.

## Files
- `index.html` — all page content and all seven Nexus branches
- `styles.css` — layout, colors, typography and responsive design
- `script.js` — mobile navigation, current year and contact email form

## Publish with GitHub Pages

1. Sign in to GitHub and create a new repository. A good name is `nexus-website`.
2. Set the repository to **Public** if you are using the free GitHub Pages option.
3. Upload `index.html`, `styles.css` and `script.js` to the top/root of the repository.
4. Open the repository's **Settings**.
5. Select **Pages** in the left sidebar.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch `main` and folder `/ (root)`, then click **Save**.
8. Wait a few minutes. GitHub will show your website address in the Pages section.

## Customize your site

### Change the contact email
Search in both `index.html` and `script.js` for:
`nexus-btgz46@polsia.io`

Replace it with the email address you want visitors to use.

### Change a branch status
In `index.html`, each branch has a line like:
`<span>In development</span>`

Change it to a status that accurately describes that branch, for example:
- Planned
- In development
- Active
- Temporarily unavailable

The contact form uses `mailto:`. It does not store submissions or send messages through a server; it opens the visitor's email application so they can review and send the message themselves.

## Updating the website
Edit the files in GitHub and commit your changes. GitHub Pages will publish the updated site automatically.
