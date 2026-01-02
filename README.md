# Portfolio Website

A modern, responsive portfolio website showcasing my projects, skills, and experience.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth animations and transitions
- 🎯 Easy to deploy (static HTML/CSS/JS)
- ♿ Accessible and SEO-friendly

## Tech Stack

- HTML5
- CSS3 (with CSS Variables, Flexbox, Grid)
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts (Inter)

## Project Structure

```
portfolio_site/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript for interactivity
└── README.md          # This file
```

## Deployment

This is a static website, so it can be easily deployed to various platforms:

### GitHub Pages

1. Push this repository to GitHub
2. Go to repository Settings > Pages
3. Select the branch (usually `main`) and folder (usually `/ (root)`)
4. Your site will be available at `https://yourusername.github.io/portfolio_site`

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts
4. Your site will be deployed automatically

Or use the Vercel web interface:
1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Vercel will automatically detect it's a static site and deploy it

### Netlify

1. Install Netlify CLI: `npm i -g netlify-cli`
2. Run `netlify deploy` (or `netlify deploy --prod` for production)
3. Follow the prompts

Or use drag-and-drop:
1. Go to [app.netlify.com](https://app.netlify.com)
2. Drag and drop the project folder
3. Your site will be live instantly

### Other Options

- **Surge.sh**: `surge ./ portfolio_site.surge.sh`
- **Firebase Hosting**: Use Firebase CLI
- **AWS S3 + CloudFront**: Upload files to S3 bucket
- **Any static hosting service**

## Local Development

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Or use a local server:
   - Python: `python -m http.server 8000`
   - Node.js: `npx serve`
   - VS Code: Use Live Server extension

## Customization

### Update Personal Information

Edit `index.html` to update:
- Your name and title
- About section content
- Projects and descriptions
- Skills and technologies
- Contact links (GitHub, LinkedIn)

### Change Colors

Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    /* ... other variables */
}
```

### Modify Typing Animation

Edit the `roles` array in `script.js`:
```javascript
const roles = [
    'Your Role 1',
    'Your Role 2',
    // ... add more roles
];
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This project is open source and available under the MIT License.

## Contact

- GitHub: [@AradhanaVU](https://github.com/AradhanaVU)
- LinkedIn: [aradhana-udhatya](https://www.linkedin.com/in/aradhana-udhatya/)

