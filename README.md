# Shanjid Ahmed - Portfolio Website

## Latest Updates

✅ Profile photo integrated (smaller, rounded circle style)
✅ "About My Work" section added between hero and About Me sections
✅ Contact section redesigned with horizontal layout
✅ Official LinkedIn and GitHub logos added
✅ Improved responsive design

## Setup Instructions

1. **Extract the ZIP file** to your desired location.

2. **Open `portfolio.html`** in any web browser to view your portfolio.

## Design Features

### Hero Section
- Professional rounded profile photo
- Eye-catching gradient design
- Key statistics display (3+ years, 6+ projects, 8+ certifications)

### About My Work Section
- Highlights your service offerings
- Clear value proposition
- Professional feature list

### Contact Section
- Horizontal card layout for better visual flow
- Official brand logos for LinkedIn and GitHub
- Hover effects on all elements

## How to Update Links

### Project Links
To update your project links, open `portfolio.html` in a text editor and search for the following placeholders:

**GitHub Projects:**
- Replace `https://github.com/yourusername` with your actual GitHub username
- Replace `https://github.com/yourusername/sales-analysis` with your Sales Analysis repository URL
- Replace `https://github.com/yourusername/house-price-prediction` with your House Price Prediction repository URL
- Replace `https://github.com/yourusername/financial-analysis` with your Financial Analysis repository URL

**Power BI Dashboards:**
To get your Power BI dashboard shareable link:
1. Open your dashboard in Power BI Service
2. Click File → Embed report → Publish to web
3. Get the public URL
4. Replace `https://app.powerbi.com/view?r=YOUR_REPORT_ID` with your actual dashboard URL

Update these for:
- AdventureWorks Sales Analysis dashboard
- Uber Trip Analysis dashboard

### Social Media Links
In the Contact section, update:
- `https://www.linkedin.com/in/yourusername` - Replace with your LinkedIn profile URL
- `https://github.com/yourusername` - Replace with your GitHub profile URL

## Files Included

- `portfolio.html` - Your complete portfolio website
- `profile-photo-optimized.jpg` - Your professional photo
- `README.md` - This file with instructions

## Customization Tips

### Colors
The current color scheme uses teal/cyan. To change colors, edit the CSS variables at the top of the HTML file:
```css
:root {
    --primary: #0ea5e9;
    --primary-dark: #0284c7;
    --secondary: #06b6d4;
    --accent: #8b5cf6;
}
```

### Content
You can easily update any text content directly in the HTML file. Look for the relevant section and modify the text between the HTML tags.

### Adding More Projects
To add more projects, copy one of the existing project card blocks and modify the content:
```html
<div class="project-card">
    <div class="project-image">📊</div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description</p>
        <a href="your-link" target="_blank" class="project-link">View Project →</a>
    </div>
</div>
```

## Deployment

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files
3. Enable GitHub Pages in repository settings
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)
1. Drag and drop the folder to netlify.com
2. Your site will be live instantly with a custom URL

### Option 3: Custom Domain
1. Purchase a domain from any domain registrar
2. Use any hosting service (GitHub Pages, Netlify, Vercel, etc.)
3. Point your domain to the hosting service

## Support

If you need help customizing your portfolio, feel free to reach out!

---
Created with ❤️ for Shanjid Ahmed
