# Sumit Kumar - Resume Website

A professional, responsive resume website built with HTML and CSS, ready to deploy on GitHub Pages.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Dark Mode Support**: Automatically adapts to user's system preference
- **Print-Friendly**: Print or save as PDF with optimized formatting
- **Fast Loading**: No external dependencies, pure HTML and CSS
- **Professional Layout**: Clean, modern design focused on readability

## How to Deploy to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click **New** (top left) to create a new repository
3. Name it: `resume` or `your-username.github.io`
4. Make it **Public**
5. Click **Create repository**

### Step 2: Upload Files
1. On your repository page, click **Add file** → **Upload files**
2. Drag and drop `index.html` and `README.md`
3. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. Go to repository **Settings**
2. Click **Pages** (in left sidebar under "Code and automation")
3. Under "Source", select **main** branch
4. Click **Save**
5. Wait 1-2 minutes for deployment

### Step 4: Access Your Resume
- If repository is named `resume`: `https://your-username.github.io/resume`
- If repository is named `your-username.github.io`: `https://your-username.github.io`

## Making Updates

To update your resume:
1. Edit `index.html` directly in GitHub (click the pencil icon)
2. Make changes and commit
3. Changes appear live within seconds

Or clone locally:
```bash
git clone https://github.com/your-username/resume.git
cd resume
# Edit index.html
git add index.html
git commit -m "Update resume"
git push
```

## Customization

### Change Colors
Open `index.html` and look for color definitions in the `<style>` section:
- `#0066cc` is the primary blue accent color
- Change to any hex color you prefer

### Add Custom Domain
1. In repository Settings → Pages
2. Under "Custom domain", enter your domain (e.g., `resume.yourname.com`)
3. Follow the DNS setup instructions

### Add Social Links
In the `<header>` section, add more contact items:
```html
<div class="contact-item">
    <span>🔗</span>
    <a href="https://linkedin.com/in/yourprofile">LinkedIn</a>
</div>
```

## Browser Support

Works on all modern browsers (Chrome, Firefox, Safari, Edge). Print styling optimized for PDF export.

## Tips

- **SEO**: Add your name to the title tag for better search visibility
- **Meta Description**: Add `<meta name="description" content="...">` for better social sharing
- **Analytics**: Add Google Analytics or similar tracking service if desired
- **Testing**: Check how it looks on mobile using Chrome DevTools (F12 → Ctrl+Shift+M)

---

Built with ❤️ using clean HTML and CSS
