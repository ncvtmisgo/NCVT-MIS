# ITI QR Student Record Page (GitHub Pages)

This is an independent static website template. It displays records from `students.json` when someone scans a QR code containing a URL such as:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/?id=DEMO-1001`

## Publish on GitHub
1. Create a new public GitHub repository.
2. Upload `index.html` and `students.json` to the repository root.
3. Edit `students.json` and replace the sample record with information you are authorized to publish.
4. Open repository **Settings → Pages**.
5. Select **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
6. After GitHub Pages publishes the site, test the URL with `?id=DEMO-1001`.
7. Make a QR code for each record URL, replacing the ID with that student's unique record ID.

## Important
- This does NOT connect to NCVT/DGT or fetch official NCVT data.
- It is NOT an official government verification service and must not be presented as one.
- Official NCVT verification requires an authorized official facility, API, or data access from the issuing authority.
- GitHub Pages is public. Anyone can view the JSON data. Do not publish Aadhaar numbers, phone numbers, addresses, signatures, dates of birth, or other sensitive data.
- Use only genuine records and obtain permission before publishing student information.
