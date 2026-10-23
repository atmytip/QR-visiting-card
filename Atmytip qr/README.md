# Atmytip — final GitHub / Vercel project

## Contents

- public/index.html — latest page with official logo, six social/website links and Call / Save to contacts / Email buttons.
- public/styles.css — white, charcoal and orange responsive styling.
- public/assets/atmytip-logo.png — official logo.
- public/jitendra-jain.vcf — downloadable contact: Jitendra Jain, Director, +91 75075 07680, jitendra3588@gmail.com, Pune, Maharashtra 411014.
- vercel.json — static site configuration, output directory public.
- .gitignore — local metadata exclusions.

## GitHub

1. Extract the ZIP.
2. Upload its contents to the repository root. Upload the files and public folder, not the ZIP itself.
3. Commit the changes to the branch connected to Vercel.

Expected structure:

vercel.json
public/
  index.html
  styles.css
  jitendra-jain.vcf
  assets/
    atmytip-logo.png

## Vercel

Keep the existing project and production domain if you want the printed QR to remain valid.

- Framework: Other
- Root Directory: the folder containing vercel.json and public/
- Output Directory: public
- Build Command: blank (do not type the words Leave empty)
- Install Command: blank (do not type the words Leave empty)
- Environment Variables: none

vercel.json already provides the build/output settings. If files are nested inside a folder in GitHub, select that folder as Root Directory.

Push the new commit and deploy it. Check the production URL on a phone. Verify all social buttons and the Save to contacts button. Depending on the browser and phone, the VCF opens a contact import screen or downloads a contact file that must be opened.

## Local preview

Open public/index.html in a browser. No installation or build is necessary.

## QR

The current card QR opens https://atmytip-qr.vercel.app/. Update that existing Vercel project rather than changing its domain. If you deploy at another URL, a new QR is required.
