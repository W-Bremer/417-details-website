# 417 Details Website

A modern, responsive website for 417 Details auto detailing service.

## Project Structure

```
├── index.html          # Main homepage
├── about.html          # About page
├── services.html       # Services page
├── contact.html        # Contact page
├── css/               # Stylesheets
├── js/                # JavaScript files
├── images/            # Image assets
├── product/           # Product pages
├── services/          # Service detail pages
└── category/          # Category pages
```

## Quick Deploy Instructions (For W-Bremer)

### Step 1: Create New Repository
1. Go to [GitHub](https://github.com/W-Bremer)
2. Click the "+" icon in the top right
3. Select "New repository"
4. Name it "417-details-website"
5. Make it "Public"
6. Don't initialize with README
7. Click "Create repository"

### Step 2: Upload Files
1. Open Terminal
2. Navigate to your website folder:
   ```bash
   cd /Users/williambremer/Downloads/carisma-template
   ```
3. Initialize Git repository:
   ```bash
   git init
   ```
4. Add all files:
   ```bash
   git add .
   ```
5. Commit the files:
   ```bash
   git commit -m "Initial website upload"
   ```
6. Connect to your GitHub repository:
   ```bash
   git remote add origin https://github.com/W-Bremer/417-details-website.git
   ```
7. Push your files:
   ```bash
   git push -u origin main
   ```

### Step 3: Deploy on Netlify
1. Go to [Netlify](https://app.netlify.com)
2. Sign in with your GitHub account
3. Click "Add new site"
4. Select "Import an existing project"
5. Choose "Deploy with GitHub"
6. Select "417-details-website" repository
7. Configure build settings:
   - Build command: leave empty
   - Publish directory: "/"
8. Click "Deploy site"
9. Your site will be live at `https://417-details-website.netlify.app`

## Local Development

To run the site locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/W-Bremer/417-details-website.git
   ```
2. Open the folder in your code editor
3. Open index.html in your browser
4. Or use a local server:
   ```bash
   python -m http.server
   ```
   Then open `http://localhost:8000` in your browser

## Features

- Responsive design
- Mobile-friendly
- Optimized images
- Fast loading
- SEO optimized
- Contact form integration
- Service booking system

## Netlify Configuration

The site uses the following Netlify configuration:
- Static file serving
- Client-side routing support
- Automatic HTTPS
- Global CDN

## Troubleshooting

If you encounter issues:
1. Check that all files are properly committed to GitHub
2. Verify the publish directory is set to "/" in Netlify
3. Check the deployment logs in Netlify dashboard
4. Ensure all file paths in your HTML files are relative
5. Contact Netlify support if problems persist 