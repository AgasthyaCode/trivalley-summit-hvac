# Deployment Options

This website is a static site, so it can be hosted almost anywhere. You only need to upload `index.html`, `styles.css`, `script.js`, and the `assets` folder.

## Option 1: Netlify

Best for a simple drag-and-drop launch.

1. Go to https://app.netlify.com/drop.
2. Drag this whole project folder into the page.
3. Netlify gives you a live URL.
4. Add a custom domain in Netlify under **Domain management**.

Good for: fastest launch, free SSL, simple form support.

## Option 2: Vercel

Best if you want a clean developer workflow with GitHub.

1. Push the project to GitHub.
2. Go to https://vercel.com/new.
3. Import the repository.
4. Leave build settings blank because this is a static site.
5. Deploy and connect your domain.

Good for: Git-based updates, previews, strong performance.

## Option 3: GitHub Pages

Best for a free basic website.

1. Create a GitHub repository.
2. Upload the project files.
3. Open repository **Settings**.
4. Go to **Pages**.
5. Choose the main branch and root folder.
6. Save and wait for GitHub to publish the site.

Good for: free hosting, simple static sites.

## Option 4: Traditional Web Hosting

Best if you already have hosting through GoDaddy, Bluehost, Hostinger, cPanel, or similar.

1. Open your host file manager or FTP tool.
2. Upload all files into the public website folder, often called `public_html`.
3. Make sure `index.html` is at the top level of that folder.
4. Visit your domain to confirm the site is live.

Good for: existing hosting accounts and email/domain bundles.

## Option 5: Cloudflare Pages

Best for speed, security, and free global hosting.

1. Push the project to GitHub.
2. Go to Cloudflare Pages.
3. Connect the repository.
4. Leave build command empty.
5. Set output directory to `/` or leave it blank.
6. Deploy and connect your domain.

Good for: free SSL, fast CDN, DNS management.

## Before Going Live

- Replace the company name, phone number, email address, and license number.
- Replace sample service areas with real cities.
- Replace reviews with real customer testimonials.
- Update pricing and financing details.
- Connect the contact form to Netlify Forms, Formspree, HubSpot, Jobber, ServiceTitan, Housecall Pro, or your own backend.
- Compress the images if you want faster loading.
- Add Google Analytics, Google Search Console, and your Google Business Profile link.
- Add a privacy policy if you collect customer information.

## Recommended Path

For most HVAC businesses, use Netlify first because it is the fastest path to a professional live site. If you plan to keep editing through GitHub, use Vercel or Cloudflare Pages.
