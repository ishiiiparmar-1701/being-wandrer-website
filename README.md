# BEING WANDRER static website

Static HTML, CSS and vanilla JS. Flight-only enquiry site; no Bus, payment, booking or ticket issue.

## Important
The flight search interface is not connected to live Travinus data yet. Confirm the provider's authentication and CORS/browser access first. Never put a private ClientSecret in public JavaScript. If server-side authentication is required, a secure backend/proxy is needed.

Contact form uses FormSubmit as a sample static form service. It may require inbox activation and should be tested before launch. Tailor the legal pages to actual business practices and applicable law.

## Images
Add your own banner/logo/destination image files under `assets/images` and update CSS/page paths. This archive does not include the images you previously uploaded.

## Netlify
Import the GitHub repository. Build command: leave blank. Publish directory: `.`. Ensure index.html is in the repository root.

## Hostinger
Upload project contents to `public_html`; index.html must sit directly in that folder.
