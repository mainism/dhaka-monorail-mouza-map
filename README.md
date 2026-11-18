# Dhaka Monorail — Proposed Four-Route GIS Map

An interactive, public-facing **pre-feasibility** map of four proposed Dhaka monorail alignments (MR5, MR6, MR8 and MR13). The website includes buffered alignment/station/depot footprints, RAJUK RS plot layers, DAP planning attributes and search/click details.

## View the website

After publishing with GitHub Pages, open `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/`.

## Publish to GitHub Pages

1. Create a new **Public** repository in GitHub (e.g. `dhaka-monorail-map`), and **do not** select any optional starter files (README, .gitignore or license).
2. On the empty repository page, click **uploading an existing file** (or **Add file > Upload files**).
3. **Extract the downloaded ZIP first**. Drag the extracted `index.html`, `.nojekyll`, and `README.md` to the upload page, then select **Commit changes**. If hidden `.nojekyll` is not visible in Windows, you may upload `index.html` and `README.md` only; `.nojekyll` is included for compatibility, but a simple `index.html` generally does not require it.
4. Open **Settings > Pages** (left sidebar).
5. Under **Build and deployment**, choose **Deploy from a branch** > `main` > `/(root)` > **Save**.
6. In **Settings > Pages**, use **Visit site** after publication; or try `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/`.

**Important:** Do not upload the ZIP itself to the repository expecting the web page to publish. GitHub will not automatically unzip it. `index.html` must be in the repository root.

## Notes

- The website is a self-contained HTML file; there is **no API key** required for its offline cadastral background.
- Optional Esri Street and Satellite basemaps require an internet connection and depend on the external provider's access and usage policies; they cannot be guaranteed.
- All embedded GIS content becomes publicly accessible when the repository is made public. Review public-release rights for RAJUK-derived cadastral/planning attributes before distribution.
- This map provides **proposed alignment / pre-feasibility screening**, not survey-certified boundary or land acquisition records. Original RS khatian land class and legally relevant acquisition data must be verified separately.
- Method: 15 m on either side of the route centreline, 100 m station radius and 50 m outward depot polygon buffer, with overlaps avoided in the footprint calculations.

## Source acknowledgement

Map contains data compiled from the user-supplied Dhaka monorail proposed route KML, RAJUK DAP / RS plot exports, and Bangladesh census mouza mapping. These inputs may have conditions on redistribution; no license is asserted over third-party data.
