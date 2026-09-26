# Rabab Okasha Portfolio

A modern, responsive portfolio website for Rabab Okasha, designed as a polished professional online resume and project showcase.

## Stack
- React
- TypeScript
- Vite
- CSS custom properties for theming

## Local setup

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the development server:
   ```bash
   npm run dev
   ```
3. Open the local URL shown in the terminal, usually:
   ```bash
   http://localhost:5173/
   ```

## Production build

```bash
npm run build
```

## Deployment
This portfolio is ready to deploy on services such as:
- Vercel
- Netlify
- GitHub Pages

After building, deploy the contents of the dist folder or configure your hosting platform to publish the built app.

## Where to update personal information
Main content is in [src/App.tsx](src/App.tsx). Update sections including:
- Hero
- About
- Profile
- Skills
- Experience
- Education
- Projects
- Contact information

## Where to replace images
Use the files in [public/images](public/images):
- profile-placeholder.svg
- project-breast-cancer.svg
- project-housing-clustering.svg
- project-placeholder.svg

Also update the browser metadata and social preview in:
- [index.html](index.html)
- [public/favicon.svg](public/favicon.svg)
- [public/og-image.svg](public/og-image.svg)

## Where to add new projects
Add or edit project objects in [src/App.tsx](src/App.tsx). Each project object includes:
- name
- description
- challenge
- solution
- role
- technologies
- features
- GitHub link
- live demo link

## Contact form integration
The form is UI-ready and validated, but it does not send emails until an integration is connected. Common options:
- Formspree
- EmailJS
- Netlify Forms
- Custom backend endpoint

## Notes
Some details such as experience dates, languages, and availability are intentionally marked as placeholders because no exact data was provided in the brief.
