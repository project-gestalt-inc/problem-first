# Problem First — Prompt Second

Project Gestalt static website and workshop downloads. Prepared 4 November 2026. Status: files prepared for GitHub Pages; deployment and DNS have not been performed or verified as part of this package.

## Fixed addresses

- Page: https://problem-first.projectgestalt.com/
- Editable log: https://problem-first.projectgestalt.com/resources/landscape-exploration-log.docx
- Tool guide: https://problem-first.projectgestalt.com/resources/landscape-review-tool-guide.pdf
- Workshop slides: https://problem-first.projectgestalt.com/resources/ua-nov2026-presentation.pdf

## Upload to GitHub

1. Download this folder from Drive, or download and extract the accompanying ZIP.
2. Open the `project-gestalt-inc/problem-first` repository on GitHub.
3. Select **Add file → Upload files**.
4. Drag the contents of this folder into GitHub: `index.html`, `styles.css`, `CNAME`, `.nojekyll`, `README.md`, the `assets` folder and the `resources` folder. Do not upload an enclosing `problem-first` folder or the ZIP itself. The repository's top level must contain `index.html`.
5. Commit to `main`. If `.nojekyll` is hidden by your computer, create an empty file named `.nojekyll` directly through GitHub's **Add file → Create new file**.
6. In **Settings → Pages**, select **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
7. Set **Custom domain** to `problem-first.projectgestalt.com` and save. The supplied CNAME file does not replace this settings step.
8. At the domain's DNS provider, create a CNAME record with host `problem-first` and target `project-gestalt-inc.github.io` (no repository path).
9. Enable **Enforce HTTPS** when available. Check the page and all three downloads in a signed-out browser, including on a phone.

## Files and maintenance

`index.html` contains the page text. `styles.css` controls the responsive layout. `assets/project-gestalt.png` is the existing PG wordmark. `resources/` holds public copies of the participant materials.

Replace downloads at the same paths to preserve links in the distributed presentation. Keep dates and versions inside the documents. Preserve the exact distributed editions in the workshop node. This folder is the current website handoff package; once GitHub is established, use its repository as the website's authoritative working copy and avoid editing two website copies independently.

The public page distinguishes the reusable Frame → Select → Apply → Evaluate → Adapt cycle from the landscape-review method. The digital-twin example is explicitly illustrative. UA institutional-resource guidance is left to the relevant UA materials and SD's presentation.

## Source and edition record

- Editorial starting point: `2026-11-02_1715Z_ChatGPT_PFPS-Page-Wireframe_v1.md`, Drive ID `13q7AFvdf92Obmykm4xCK3wK3zfbETD4K`.
- Log: byte-for-byte copy of `PG-UA-Landscape-Exploration-Log-Nov2026.docx`, Drive ID `1Z7OVgKWAHSjIVI-okOsLz2C5vIzCJMjT`, modified 4 November 2026 at 10:47 UTC, from `materials/to UA Immersive Week Site/`.
- Slides: byte-for-byte copy of the PDF sent to UA, Drive ID `1WtGDb7xBxyLas45N-STOkNMl06RaQKEl`, modified 4 November 2026 at 10:36 UTC. 28 pages. No slide edits or re-export.
- Tool guide: PDF conversion of `PG-UA-Landscape-Exploration-Tools Grid-Nov2026.docx`, Drive ID `1sEh7MfUTsIDpKbM1WWZjka7eDyCWnD5n`, modified 4 November 2026 at 10:48 UTC, from the same UA folder. No content edits. Export-only paragraph spacing was tightened in the landscape-method section to remove an orphan page; the source DOCX is unchanged.
- PG wordmark extracted without modification from that tool-guide document.
- Week and session names follow Neil's explicit wording: “Doctoral 1st immersive week, November 2026” and “AI-based Systematic literature review”.

Prepared with AI assistance. Source documents remain in their existing locations.
