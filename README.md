# CHE110_Project

This project focuses on presenting educational content through multiple web pages, covering topics such as ecosystem types, benefits, hazards, prevention, and related environmental concepts. It includes SEO optimization, proper folder structure, and responsive layouts to enhance user experience.

## Live Link
- **CHE110_Project:** [View CHE110 Project](https://pr2309.github.io/CHE110_Project/)

## Development Server

To view the CHE110 Project locally:
1. Clone the repository.
2. Open the `index.html` file located **at the root** of the project in your browser.

## Project Structure
```
CHE110_Project/
│
├── index.html               # Homepage (root)
├── manifest.json            # Progressive Web App manifest
├── sitemap.xml              # Sitemap for SEO (updated 2026-01-25)
├── robots.txt               # Robots file for search engines
│
├── Pages/                   # All 22 subpages
│   ├── About.html           # About the project and authors
│   ├── Benefits.html        # Benefits of ecosystems
│   ├── Hazards.html         # Environmental hazards and threats
│   ├── Prevention.html      # Conservation and prevention methods
│   ├── Types.html           # Overview of all ecosystem types
│   ├── Key-Terms.html       # Glossary of ecosystem terms
│   ├── More.html            # Additional resources
│   │
│   |   # Terrestrial Ecosystems:
│   ├── Forest-Ecosystem.html
│   ├── Grassland-Ecosystem.html
│   ├── Desert-Ecosystem.html
│   ├── Mountain-Ecosystem.html
│   ├── Alpine-Ecosystem.html
│   ├── Tundra-Ecosystem.html
│   ├── Polar-Ecosystem.html
│   │
│   |   # Aquatic Ecosystems:
│   ├── Freshwater-Ecosystem.html
│   ├── Marine-Ecosystem.html
│   ├── Estuarine-Ecosystem.html
│   │
│   |   # Human-made Ecosystems:
│   ├── Agricultural-Ecosystem.html
│   ├── Aquaculture-Ecosystem.html
│   ├── Urban-Ecosystem.html
│   ├── Industrial-Ecosystem.html
│   └── Greenhouse-Ecosystem.html
│
├── img/                     # Images used across the project
│     ├── logo.png
│     └── ... other images
│
└── Style/                   # All CSS styling files
    ├── style.css            # Global styles
    ├── index.css            # Homepage styles
    ├── TypesPages.css       # Ecosystem pages styles
    ├── About.css            # About page styles
    ├── Benefits.css         # Benefits page styles
    ├── Hazards.css          # Hazards page styles
    ├── Prevention.css       # Prevention page styles
    ├── Types.css            # Types page styles
    └── More.css             # More page styles
```

## Features
- **23 Comprehensive Educational Pages** covering 13 different ecosystem types and related topics
- **Terrestrial Ecosystems**: Forest, Grassland, Desert, Mountain, Alpine, Tundra, Polar
- **Aquatic Ecosystems**: Freshwater, Marine, Estuarine
- **Human-made Ecosystems**: Agricultural, Aquaculture, Urban, Industrial, Greenhouse
- **Educational Sections**: Each ecosystem page includes Introduction, Climate/Features, Flora, Fauna, Threats/Impact, Conservation, Importance, Fun Facts, Conclusion, and References
- **Interactive Navigation**: Internal navigation through buttons and headers
- **Multi-page Learning Hub**: Additional pages for Benefits, Hazards, Prevention, and Key Terms
- **Responsive and Mobile-friendly Design**
- **Parallel Image and Style Folders** for maintainability
- **SEO-optimized Meta Tags** on all pages (Open Graph, Twitter Cards, Canonical URLs)
- **Sitemap Integration** (updated 2026-01-25) for better search engine crawling
- **Progressive Web App Support** with manifest.json

## How to Use
1. Open the `index.html` file located in the **root** directory in your browser.
2. Navigate through the comprehensive ecosystem education content:
   - **Home Page**: Overview and quick links to all sections
   - **Types Page**: Browse all 13 ecosystem types with descriptions
   - **Individual Ecosystem Pages**: Deep-dive into each ecosystem with detailed information like:
     - Climate/Environmental conditions
     - Flora (plant life)
     - Fauna (animal life)
     - Threats and conservation efforts
     - Importance and fun facts
     - References for further learning
   - **Benefits Page**: Understand the advantages of ecosystems
   - **Hazards Page**: Learn about environmental threats
   - **Prevention Page**: Discover conservation strategies
   - **Key Terms Page**: Access a glossary of ecosystem-related terminology
   - **About Page**: Information about the authors
3. All pages include:
   - Table of contents for easy section navigation
   - Responsive design for all devices
4. All Specific Type Pages include:
   - Back navigation button to return to Types page
   - Quick menu to jump between ecosystem pages
5. All pages except entry point are stored inside the `Pages/` folder

## SEO Enhancements Added
The project includes comprehensive search-engine-friendly improvements:
- **Canonical URL Tags**: Prevent duplicate content issues
- **Robots Meta Tag**: Guide search engine crawlers
- **Meta Descriptions & Keywords**: Optimized for each page
- **Open Graph Tags**: Social media preview optimization
- **Twitter Card Tags**: Enhanced Twitter sharing
- **Alternate hreflang Tags**: Multi-language support structure
- **Favicon Support**: Multiple device icon support (SVG, ICO, Apple Touch Icon, Safari Pinned Tab)
- **Sitemap.xml**: Complete site structure for search engines (Last updated: 2026-01-25)
- **robots.txt**: Search engine crawling guidelines
- **Manifest.json**: Progressive Web App configuration
- **Structured Metadata**: Proper meta tags on all 23 pages

These optimizations help GitHub Pages index your static site correctly and improve search engine visibility.

## Sitemap
A `sitemap.xml` has been added to the root directory containing all 23 pages with:
- Complete URL listing for all ecosystem pages and supporting content pages
- Last modification dates (updated: 2026-01-25)
- Change frequency settings
- Priority levels for search engine crawling optimization
- Helps search engines understand and crawl your site structure efficiently

## Clone This Repository
To clone this repository, use the following command:

```bash
git clone https://github.com/PR2309/CHE110_Project.git
```

## Technologies Used
- **HTML5**: For structuring all web pages with semantic markup
- **CSS3**: For responsive styling and visual design
- **SVG/WebP**: Modern image formats for optimal performance
- **JSON**: Manifest and configuration files
- **XML**: Sitemap for search engine optimization
