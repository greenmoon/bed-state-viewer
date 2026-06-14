# bed-state-viewer
# bed-state-viewer


jb_A245B_how_to_gen_html_example_getting_started_V01.docx summary

Purpose
- Build a first GitHub Pages home page.
- Provide the bed-state-viewer HTML tool for easy manipulation.
- Deliver the tool to customers with a URL link for easy use.

Quick Overview
- First repo home page: create a public repo, add index.html, and enable GitHub Pages.
- bed-state-viewer tool: use the browser-based BED state curve viewer; it can read local files or repo Excel files.
- Customer delivery: send one GitHub Pages URL; the customer opens it directly in a browser.

1. Build My First Repo Home Page
1. Log in to GitHub.
2. Create a new repository.
3. Recommended repo name: bed-state-viewer.
4. Select Public and add a README file.
5. Upload or create index.html in the repository root.
6. Go to Settings -> Pages.
7. Under Build and deployment, select Deploy from a branch.
8. Select branch main and folder /root, then Save.
9. Wait for GitHub Pages deployment to finish.

Published URL example:
https://greenmoon.github.io/bed-state-viewer/

2. Use bed-state-viewer Tool
- Choose File: read the user's local .csv / .xlsx / .xlsm.
- Repo Excel: scan uploaded .xlsx / .xlsm files in the GitHub repo.
- Load repo Excel: green highlighted button that directly loads the selected repo Excel file.
- Full range: show the complete time range.
- Local window sec: control the local time window.
- Slider / Prev / Next / Play: operate the current segment.
- Mouse wheel: zoom the time axis on the plot.
- Mouse drag: horizontal pan only; y-axis state rows remain fixed.

3. Deliver to Customer With URL Link
1. Confirm index.html is uploaded to the GitHub repo root.
2. Confirm GitHub Pages has been published.
3. Send the GitHub Pages URL to the customer.
4. Customer opens the URL with Chrome / Edge / Safari.
5. For customer private data, use Choose File to load local data.
6. For demo/sample data, upload Excel to the repo and use Load repo Excel.

Cache Reminder
- GitHub Pages updates can be delayed by CDN/browser cache.
- Use a version query to avoid stale cache:
  https://greenmoon.github.io/bed-state-viewer/?v=20260614
- Change the v value after each update.

Important Notes
- Public repo means index.html and sample data in the repo are public.
- Do not upload sensitive data to a public GitHub repo.
- GitHub Pages is static hosting; it does not run Python.
- The browser runs the JavaScript inside index.html.
- If index.html uses the SheetJS CDN, Excel loading needs internet access.
- For fully offline use, bundle the library into the HTML.

