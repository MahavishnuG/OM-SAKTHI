Omsakthi Wood Carving - Website Package
Files:
- index.html
- style.css
- favicon.ico
- images are referenced via your Google Drive direct links.

How to preview locally:
- Open index.html in a browser (no server needed).

Netlify (recommended):
1. Go to https://app.netlify.com/drop
2. Drag and drop the folder 'omsakthi_website' (or upload the zip).
3. Site will be deployed automatically.
4. To add custom domain (www.omsakthiwoodcarving.com):
   - In Netlify dashboard, go to Site Settings → Domain Management → Add custom domain.
   - Add 'www.omsakthiwoodcarving.com' and follow prompts.
   - At your domain registrar, create a CNAME record:
       Host: www
       Value: <your-netlify-site>.netlify.app
   - Save and wait for DNS propagation (usually < 30 min).

GitHub Pages (backup):
1. Create a repository on GitHub (e.g., omsakthi-woodcarving).
2. Upload all files to repo root (index.html, style.css, favicon.ico).
3. Go to Settings → Pages → Deploy from main branch.
4. Your site will be available at: https://<username>.github.io/omsakthi-woodcarving/

Notes:
- Images are loaded from Google Drive direct links (uc?export=view&id=...). For production performance, consider uploading images to Cloudinary or a CDN.
- If any image stops loading due to Drive access, ensure folder/file permissions are 'Anyone with the link - Viewer'.