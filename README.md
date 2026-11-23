# KaryaGrid MVP prototype

This is a mobile-friendly Progressive Web App prototype for manufacturing teams and automobile workshops.

## Included
- Responsive dashboard
- Create work requests
- Work order list and status updates
- Sample team directory
- Activity counts and CSV export
- Interface labels in English, Kannada, Hindi, Tamil, Telugu, Malayalam, Marathi and Bengali
- Basic offline caching after first successful load

## Important limitations
This is a prototype, not a production multi-user business system.
- Data is stored only in the current browser/device using localStorage.
- There is no secure login, shared cloud database, role-based access, file upload, push notification, billing or AI integration.
- Do not enter real confidential, employee or customer information.
- Local browser storage can be cleared by the device/browser.

## Publish free with GitHub Pages
1. Create a new public GitHub repository named `karyagrid`.
2. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
3. Open repository Settings -> Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Choose `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. Open the URL shown there.
7. On Android Chrome, open the URL menu and choose Install app or Add to Home screen if offered.

## Next production milestones
1. Add a secure backend and authentication.
2. Add owner/supervisor/employee permissions.
3. Add server-side validation and backups.
4. Add privacy policy, terms, data deletion and security review.
5. Pilot with a small business before charging customers.
