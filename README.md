# Touchline — GitHub Pages deployment

This package publishes the current Touchline 0.1 prototype as a static website. No build command, API key, or dependency installation is needed.

## Publish with manual GitHub uploads
1. Unzip this download on your computer.
2. Create a new GitHub repository (a public repository works with GitHub Free).
3. Use Add file → Upload files. Upload index.html and README.md directly to the repository root, not inside another folder. Do not upload the ZIP itself. Commit to main.
4. Open Settings → Pages. Under Build and deployment, select Deploy from a branch.
5. Choose main and / (root), then Save.
6. Wait for GitHub Pages to finish deployment. Open the website link displayed in Settings → Pages.

If main is not offered yet, commit the files first and refresh Settings → Pages. If publication is restricted by your account or organization, follow GitHub's displayed requirements. No custom domain is needed.

Official setup instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## What this deploys
Team setup, age-specific session generation, editable diagrams, adaptation, saved sessions, field timer, basic seasons, and browser print/PDF layouts. The bundled index.html includes all JavaScript and styling.

Sessions are stored in each visitor's browser, not in GitHub. They do not synchronize across devices or coaches. Use Club → Export workspace backup regularly. Moving from the downloaded HTML to the hosted site does not carry local data automatically; export then restore through Club. No real student or child personal information is needed.

## Status and limitations
This is a first working prototype, not the complete production platform. AI services, shared club accounts, document uploads, and director publishing are not connected. Build and engine checks passed. Browser interaction, responsive appearance, and actual PDF page breaks were not verified because preview access was denied.

## Updating
Replace index.html with a later deployment build and commit. Keep the same repository/site address. Store the editable source project separately; this is the compiled deployment package.
