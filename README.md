# Harman Sodha — Static Website Package

This version is **frontend-only** so it can be uploaded to GitHub Pages or extracted from Google Drive and opened on another laptop without Python, FastAPI, Node, or a database.

## Included
- HTML/CSS/JavaScript frontend
- Home, Projects, Build and Book pages
- Book form asks for **name, phone number, request type and requirements**
- Book submissions are sent to **Harmansodha7@gmail.com** through the external FormSubmit service; no custom backend is included
- Submitted request is also saved locally in the browser so the visitor can edit/delete their local copy
- Contact section includes phone and email links
- Build page links to official Wix sign-in and Wix AI Website Builder
- `style.css` is in the root, so the HTML paths work from GitHub Pages and from a normal extracted folder

## GitHub Pages
1. Create/open a GitHub repository.
2. Upload all files in this folder to the repository root.
3. Keep `index.html` in the repository root.
4. Enable GitHub Pages from repository Settings → Pages.
5. Publish from the main branch/root.

## Google Drive / another laptop
1. Download the ZIP.
2. Extract it.
3. Open `index.html` in a browser.
4. The static pages work without installing a backend.

## Booking email
The Book page uses FormSubmit's public form endpoint to send booking details to Harmansodha7@gmail.com. On first use, FormSubmit may require a one-time confirmation of the receiving email address. No SMTP password is stored in this project.

## Wix sign-in
The Build page opens Wix's official sign-in page and Wix AI Website Builder. Wix documents Google/Facebook sign-in for Wix accounts. Direct GitHub-to-Wix authentication is a custom identity-provider flow that requires backend support, so it is not implemented in this backend-free package.

## Structure
```
index.html
projects.html
build.html
book.html
style.css
js/script.js
README.md
```

No backend, secrets, `.env`, SMTP credentials, or server code are included.
