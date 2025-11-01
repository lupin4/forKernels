# forKernels Website

> Official website for forKernels - High-performance Fortran HPC libraries for modern computing

## Overview

forKernels is a suite of high-performance Fortran libraries optimized for modern HPC, AI, and signal-processing workloads. Each module delivers near-bare-metal speed through easy Python bindings.

This repository contains the source code for the forKernels organization website, built as a static site using HTML5, CSS3, and vanilla JavaScript.

## Features

- **Responsive Design**: Mobile-first approach with seamless adaptation to all screen sizes
- **Performance Optimized**: Lightweight static site with no build dependencies
- **SEO Friendly**: Comprehensive metadata for search engine optimization
- **Accessible**: WCAG 2.1 compliant design patterns
- **GitHub Pages Ready**: Deploy directly to GitHub Pages without build steps

## Structure

```
forKernels/
├── index.html          # Main website file
├── styles.css          # Stylesheet with responsive design
├── script.js           # JavaScript for interactivity
├── _config.yml         # GitHub Pages configuration
├── .gitignore          # Git ignore rules
├── .github/
│   └── copilot-instructions.md  # Copilot development guidelines
└── README.md           # This file
```

## Local Development

To view the website locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/lupin4/forKernels.git
   cd forKernels
   ```

2. Open `index.html` in your web browser:
   ```bash
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   
   # On Windows
   start index.html
   ```

Alternatively, use a local web server:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Then visit http://localhost:8000
```

## Deployment

### GitHub Pages

This site is configured for GitHub Pages deployment:

1. Go to repository Settings > Pages
2. Select the branch (e.g., `main` or `gh-pages`)
3. Select root directory as the source
4. Save and wait for deployment

The site will be available at: `https://lupin4.github.io/forKernels/`

### Netlify

For Netlify deployment:

1. Connect your GitHub repository to Netlify
2. Set build command: (leave empty - no build needed)
3. Set publish directory: `/` (root)
4. Deploy

## Libraries Showcased

- **forMath**: Mathematical operations and linear algebra
- **forAI**: AI and machine learning primitives
- **forDSP**: Digital signal processing kernels
- **for3D**: 3D graphics and geometry operations
- **forCUDA**: CUDA acceleration interfaces
- **forQuant**: Quantitative computing and finance

## Contributing

When contributing to this website:

1. Review `.github/copilot-instructions.md` for guidelines
2. Maintain responsive design principles
3. Test across multiple browsers and devices
4. Validate HTML and CSS
5. Do not add build dependencies
6. Keep the site lightweight and fast

## Content Guidelines

- Focus on product features and benefits
- Never disclose internal algorithms or source code
- Maintain professional, technical tone
- Emphasize performance and practical applications
- Include factual, verifiable performance claims

## Technologies

- HTML5
- CSS3 (with CSS Custom Properties)
- Vanilla JavaScript (ES6+)
- No frameworks or build tools required

## Browser Support

- Chrome/Edge (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

© 2025 forKernels. All rights reserved.

## Links

- [GitHub Organization](https://github.com/forKernels)
- [Documentation](https://github.com/forKernels)
- Website: Coming soon on GitHub Pages
