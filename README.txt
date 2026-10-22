CERTIFICATE VERIFICATION WEBSITE — STARTER

Files:
- index.html: public verification website
- certificates.js: provider name and issued certificate records

PERSONALIZE:
1. Open certificates.js in a text editor.
2. Replace HIIGSI DATA & STATISTICAL INSTITUTE with your real training center name.
3. Replace the DEMO-2026-001 example with certificates you have already issued.
4. Each record uses: id, name, course, issueDate, status.
5. Use status: "valid" for a certificate that was genuinely issued. Keep IDs unique.

Example:
{
  id: "EXCEL-2026-0001",
  name: "Learner Full Name",
  course: "Excel Pivot Tables & Data Analysis",
  issueDate: "2026-10-20",
  status: "valid"
}

TEST:
Open index.html in a browser and search for DEMO-2026-001.

FREE DEPLOYMENT WITH GITHUB PAGES:
1. Create/sign in to https://github.com/
2. Create a public repository, e.g. certificate-verification.
3. Upload index.html and certificates.js to the repository root.
4. Open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select branch main and folder /(root), then Save.
7. Open the URL shown in Settings > Pages. It will look like:
   https://YOUR-USERNAME.github.io/certificate-verification/

Official guide: https://docs.github.com/en/pages/quickstart

IMPORTANT LIMITATIONS:
- The certificate register is public and included in certificates.js. Visitors can inspect the records. Only publish minimum information you intend to be public.
- Adding/removing records requires editing and re-uploading certificates.js.
- This starter has no private admin login or database. Do not store sensitive personal data.
- GitHub Pages hosts static files; it does not provide a private backend database.
- A free github.io address is available. A custom domain such as yourcenter.com normally costs money.
