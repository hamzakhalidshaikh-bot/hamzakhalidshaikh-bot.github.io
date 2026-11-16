# Hamza — Mechanical Engineering Portfolio

This is a ready-to-publish, responsive professional portfolio website intended for **GitHub Pages**. No paid hosting or software is required.

## What's inside

- `index.html`: homepage with projects, academic background, industrial placements, skills, and contact information.
- `projects/*.html`: individual engineering case-study pages.
- `assets/*.svg`: **original conceptual illustrations**, not simulation results or facility photographs.
- `assets/styles.css`, `assets/app.js`: website styling and mobile navigation.
- `Hamza-CV.pdf`: a copy of the source CV supplied to create the starter.

## Preview before publishing

Open `index.html` in any web browser. The website works without installation or building. An internet connection allows the optional Google Fonts to load; system fonts will be used if offline.

## Publish to GitHub Pages for free

1. Create a free account at https://github.com if you do not already have one.
2. Create a new **public** repository named `YOUR-USERNAME.github.io` (replace `YOUR-USERNAME` with your exact GitHub username).
3. Upload the **contents of this folder** to the repository root. Do not upload the ZIP file alone; upload `index.html`, the `projects` and `assets` directories, and any other files you want online.
4. On GitHub, go to **Settings → Pages → Build and deployment → Deploy from a branch**. Choose `main` and `/(root)`, then **Save**. If the repository was created with a ready-made Pages workflow, follow the settings shown by GitHub instead.
5. Visit `https://YOUR-USERNAME.github.io/` after GitHub reports that publishing is complete.

Official documentation: https://docs.github.com/en/pages/quickstart

## Important: update before sharing with recruiters or universities

1. **Replace placeholders with evidence.** Each project page has four labeled evidence slots. Replace the relevant `<div class="evidence-slot"> ... </div>` with a `<figure>` containing your own screenshot and a precise caption, for example:

   ```html
   <figure>
     <img src="../assets/gshp-hap-model.png" alt="HAP model of mixed-use building" loading="lazy">
     <figcaption>HAP thermal zoning model developed for the GSHP feasibility study.</figcaption>
   </figure>
   ```

   Upload the corresponding image to `assets/`, and add a CSS style if needed. The grid already constrains image widths.
2. **Confirm academic/project status.** GSHP appears in the supplied CV as the final-year design project; the LPG vessel is labeled an additional design study because it does not appear in that CV. Update any labels if the academic status is different.
3. **Verify technical claims and outcomes.** Do not call a design safe or optimized without verified calculations. Avoid presenting simulation predictions as measured savings.
4. **Protect confidential information.** Remove proprietary vessel specifications, facility photographs without permission, internal reports, sensitive plant measurements, personal contact details not intended to be public, etc. The illustrations are intentionally generic.
5. **Review public contact information.** The website publishes email and LinkedIn, not a phone number, but the attached CV PDF contains a phone number. Replace or omit the CV before publishing if you do not want it public.
6. **Correct the existing CV if necessary.** The source CV uses some abbreviated training terminology; check accuracy before publishing.

## Editing quick guide

- Headline or introduction: edit the relevant text in `index.html`.
- Colors and typography: edit CSS variables at the top of `assets/styles.css`.
- Projects: edit the three project files inside `projects/`.
- Replace the concept images only if you have suitable public-approved artwork or screenshots.
- Email: search and replace `hamzakhalidshaikh@gmail.com`.
- LinkedIn: search and replace `engrhamzashaikh`.

## Design notes

This site intentionally avoids displaying invented technical results. The visual concept diagrams are decorative aids, and the case studies can be supplemented with actual evidence. Site HTML, SVG, CSS, and JavaScript are directly editable; no proprietary website builder is required.
