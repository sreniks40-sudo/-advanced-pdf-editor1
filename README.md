# Advanced PDF Editor

Mobile-friendly static web app for authorized PDF editing.

## Current features
- Open and preview PDF pages
- Add text overlays
- Add PNG/JPG images, including a signature image
- Rotate and delete pages
- Insert blank pages
- Append pages from a second PDF
- Download edited PDF

## Publish on GitHub Pages
1. Create a repository (for example `advanced-pdf-editor`).
2. Upload `index.html` and `README.md` directly; do not upload only the ZIP.
3. Commit the files.
4. Open Settings → Pages.
5. Choose `Deploy from a branch`, branch `main`, folder `/ (root)`, then Save.
6. Open the Pages URL once deployment is complete.

## Limits
This app uses PDF-Lib and PDF.js from CDN, so it requires internet access. It adds overlays but does not edit existing embedded text in place. It does not provide OCR, secure redaction, guaranteed full form support, compression, or cryptographic digital signatures. Avoid editing confidential documents on a public deployment unless you understand the privacy implications. Only edit documents you own or have permission to modify.
