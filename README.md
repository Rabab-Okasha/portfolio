# Rabab Okasha: Portfolio

Static site. No install or build step needed.

## Folder structure
Put these files in the SAME folder as index.html:

- index.html
- RababMohamed_photo.jpeg
- Rabab Mohamed Newest CV.pdf
- ChatGPT Image Oct 7, 2026, 01_52_49 PM.png  (Breast Cancer project)
- ChatGPT Image Oct 7, 2026, 01_47_45 PM.png  (Housing Clustering project)
- ChatGPT Image Oct 7, 2026, 01_44_36 PM.png  (Material Classification project)

## Run locally
Option 1: double-click index.html.
Option 2 (local server): run `python -m http.server 8000` in this folder, then open http://localhost:8000

## Edit content
Open index.html in VS Code.
- Placeholders: search for `[ADD` and replace each one.
- Projects: edit the `const P=[...]` list in the script at the bottom.
- Colors: edit the variables at the top of the `<style>` block.
- Contact form: connect Formspree or EmailJS in the submit handler (currently opens your email app).

## Deploy (free)
Upload the folder to GitHub Pages, Netlify or Vercel.
