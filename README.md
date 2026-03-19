# Portfolio Website

A minimal, clean portfolio website.

## Setup

1. **Customize the content:**
   - Edit `index.html` with your name, bio, projects, and writing
   - Update social links (email, GitHub, LinkedIn, Twitter)
   - Add your own projects and articles

2. **Deploy to GitHub Pages:**
   ```bash
   # Create a new repository on GitHub named: yourusername.github.io
   # Then run:
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. **Custom Domain (optional):**
   - Create a file named `CNAME` in the root directory
   - Add your domain (e.g., `yourdomain.com`)
   - Configure DNS settings with your domain provider:
     - Add an A record pointing to GitHub Pages IPs:
       - 185.199.108.153
       - 185.199.109.153
       - 185.199.110.153
       - 185.199.111.153
     - Or add a CNAME record pointing to `yourusername.github.io`

4. **Enable GitHub Pages:**
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Save

Your site will be live at `https://yourusername.github.io` (or your custom domain)

## Local Development

Simply open `index.html` in your browser, or use a local server:

```bash
# Python 3
python -m http.server 8000

# Node.js (if you have npx)
npx serve

# Or use any other local server
```

Then visit `http://localhost:8000`

## Customization

- Colors: Edit CSS variables in `:root` in `style.css`
- Fonts: Change the `font-family` in `body` selector
- Layout: Adjust `.container` max-width and padding
- Sections: Add or remove sections in `index.html`
