# Modern Integrations

A modern, full-stack AI automation agency landing page featuring an interactive hero section, animated components, and a sleek dark theme with an aura background effect.

## Features

- **Interactive Hero Section** - Animated slides showcasing AI automation workflows
- **Aura Background** - Dynamic background component powered by UnicornStudio
- **Responsive Design** - Fully responsive layout optimized for all devices
- **Modern UI/UX** - Glass-morphism cards, smooth animations, and gradient effects
- **Performance Dashboard** - Interactive tabs showing agents, workflows, and ROI metrics
- **Integration Showcase** - Grid display of supported platforms (OpenAI, Anthropic, Make, Zapier, HubSpot, and custom solutions)

## Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Vanilla JavaScript** - No framework dependencies
- **Iconify** - Icon library for brand icons
- **UnicornStudio** - Aura background component
- **Google Fonts** - Inter font family

## Project Structure

```
ModernIntegrations/
├── Index.html          # Main HTML file
├── README.md          # This file
└── vercel.json        # Vercel deployment configuration
```

## Local Development

1. **Clone or download the repository**
   ```bash
   cd ModernIntegrations
   ```

2. **Open the HTML file**
   - Simply open `Index.html` in your browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. **View in browser**
   - Navigate to `http://localhost:8000` (or the port you specified)

## Deployment to Vercel

### Option 1: Vercel CLI (Recommended)

1. **Install Vercel CLI**
   ```bash
   npm i -g vercel
   ```

2. **Login to Vercel**
   ```bash
   vercel login
   ```

3. **Deploy**
   ```bash
   vercel
   ```

4. **For production deployment**
   ```bash
   vercel --prod
   ```

### Option 2: GitHub Integration

1. **Push your code to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin <your-github-repo-url>
   git push -u origin main
   ```

2. **Import to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Vercel will automatically detect the configuration and deploy

### Option 3: Vercel Dashboard

1. Go to [vercel.com/dashboard](https://vercel.com/dashboard)
2. Click "Add New Project"
3. Drag and drop the `ModernIntegrations` folder
4. Vercel will automatically deploy

## Configuration

The `vercel.json` file is configured to:
- Serve `Index.html` as the main entry point
- Handle all routes by serving the index file (for SPA-like behavior)
- Set appropriate headers for caching and security

## Customization

### Updating Content

- Edit `Index.html` directly to modify text, sections, or styling
- All styles are inline using Tailwind CSS classes
- JavaScript for animations is embedded in the HTML file

### Changing Colors

The color scheme uses Tailwind's color palette:
- Primary: Indigo (`indigo-500`, `indigo-400`)
- Background: Dark grays (`#030303`, `#0f0f0f`, `#121212`)
- Text: White and gray shades

### Modifying the Aura Background

The aura background is controlled by the UnicornStudio component:
```html
<div data-us-project="cqcLtDwfoHqqRPttBbQE" class="fixed top-0 left-0 -z-10 w-full h-full"></div>
```

To change the aura effect, update the `data-us-project` attribute with your UnicornStudio project ID.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- All external resources are loaded via CDN
- No build process required
- Optimized for fast initial load times

## License

This project is proprietary and confidential.

## Support

For questions or issues, please contact the development team.

---

Built with ❤️ for Modern Integrations

