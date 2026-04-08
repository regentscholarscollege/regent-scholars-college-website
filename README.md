# Regent Scholars College Website

Static admissions website for Regent Scholars College.

## Files

- `index.html`
- `styles.css`
- `script.js`
- `rsc-logo.jpg`

## Publish Options

### Option 1: Netlify

1. Create a new GitHub repository and upload these files.
2. Log in to Netlify.
3. Choose `Add new site` -> `Import an existing project`.
4. Connect your GitHub repository.
5. Netlify should detect a static site automatically.
6. Publish with:
   - Build command: leave blank
   - Publish directory: `.`

### Option 2: Vercel

1. Create a new GitHub repository and upload these files.
2. Log in to Vercel.
3. Choose `Add New...` -> `Project`.
4. Import the GitHub repository.
5. Vercel should detect a static site automatically.
6. Deploy without a build command.

### Option 3: Shared Hosting / cPanel

1. Open your hosting control panel.
2. Upload `index.html`, `styles.css`, `script.js`, and `rsc-logo.jpg` into `public_html` or the domain root.
3. Visit your domain to confirm the website is live.

## Domain Setup

If you want to use a custom domain such as `regentscholarscollege.co.uk`:

- In Netlify or Vercel, add the domain in project settings.
- Update your domain DNS records at your domain registrar.
- The host will tell you the exact records to add.

## Notes

- `preview-out/` and `ql-out/` are local preview/generated files and should not be published.
- The website is fully static, so no backend server is required.
