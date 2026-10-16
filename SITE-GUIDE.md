# Luke Chipman portfolio

A plain HTML site: `index.html`, `resume.pdf` and an `images/` folder. No build step.

## Add your photos
Drop photos into `images/` using the filenames below (or change the filenames in the
`projects` list near the bottom of `index.html`). Any missing photo shows a striped
placeholder with the filename it expects, so you can see what is still needed.

Tips: use JPGs about 1600–2000 px wide and under ~500 KB each (squoosh.app works well).
The first photo of each project is the big one.

| Project | Filenames |
|---|---|
| Hero (top of page) | hero.jpg |
| Automatic tool changer | tool-changer-1.jpg, tool-changer-2.jpg, tool-changer-3.jpg, printer-install-1.jpg |
| SAE Aero UAV | sae-aero-1.jpg, sae-aero-2.jpg |
| AIAA DBF UAV | dbf-1.jpg … dbf-4.jpg |
| Canadian Engineering Competition | cec-1.jpg, cec-2.jpg |
| MechMania | mechmania-1.jpg |
| 7-axis concrete printing | concrete-1.jpg … concrete-3.jpg |
| Woodworking attachments | woodworking-1.jpg |
| Lunar greenhouse end effector | lunar-1.jpg, lunar-2.jpg |
| Architectural models | arch-1.jpg, arch-2.jpg |
| Cinema filter frames | filter-1.jpg |
| 3D printed props | props-1.jpg, props-2.jpg |

Add more photos to any project by adding lines to its `images` list. Add or reorder
projects by editing the `projects` list; the order there is the order on the page.

## Put it online with GitHub Pages
1. Create a GitHub account. The username becomes your free URL: `username.github.io`.
2. Create a new public repository named exactly `username.github.io`.
3. Click "Add file" > "Upload files" and drag in `index.html`, `resume.pdf` and the `images` folder. Commit.
4. Wait a minute, then visit `https://username.github.io`.

To update later, upload the changed files again.

## Optional: your own domain (e.g. lukechipman.com)
1. Buy the domain from a registrar (Cloudflare, Namecheap, Porkbun, etc.).
2. In the repo: Settings > Pages > Custom domain, enter the domain, save, and tick "Enforce HTTPS" once available.
3. At the registrar, add the DNS records GitHub's Pages docs list for an apex domain (four A records) plus a CNAME for `www` pointing to `username.github.io`.
