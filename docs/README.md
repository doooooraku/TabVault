# Tab Vault — Landing Page (GitHub Pages ready)

This folder is a static site for the Tab Vault Chrome extension.  
Just upload the files to a GitHub repository and enable **GitHub Pages**.

## How to publish (no build tools needed)
1. Create a new **public** repository on GitHub (e.g. `tabvault-site`).
2. Upload all files from this folder **at the repository root**.
3. Go to **Settings → Pages**:
   - Either select **Deploy from a branch**: `main` branch / `/ (root)` path, or
   - Use the **GitHub Actions** default workflow for Pages if preferred.
4. Wait for deployment to finish, then open your Pages URL.

## Optional
- Replace the CTA links in `index.html` with your **Chrome Web Store** URL once published.
- Add analytics (e.g., Plausible) by inserting their script in `index.html` `<head>`.
- For custom domain, add a `CNAME` file with your domain name.
