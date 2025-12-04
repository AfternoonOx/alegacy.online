# ASHEN LEGACY - Vintage Story Server Website

The official website for ASHEN LEGACY, a Russian Vintage Story game server.

🌐 **Live Site**: [https://alegacy.online](https://alegacy.online)

## About

This website provides information about the ASHEN LEGACY Vintage Story server, including:

- Server connection details and instructions
- Required mods and installation guides
- Server rules and guidelines
- News and updates
- Alloy calculator utility
- Articles and guides for players

## Tech Stack

- **Build Tool**: [Vite](https://vitejs.dev/)
- **Language**: Vanilla JavaScript (ES Modules)
- **Styling**: Custom CSS

## Project Structure

```
├── public/                    # Static assets
│   ├── images/                # Image files
│   ├── icon.png               # Favicon
│   ├── robots.txt             # SEO robots file
│   └── sitemap.xml            # Sitemap for search engines
├── src/
│   ├── components/            # Reusable UI components
│   │   ├── ArticlesList.js    # Article listing component
│   │   ├── CustomRangeSlider.js # Custom slider input
│   │   ├── Footer.js          # Site footer
│   │   ├── Header.js          # Site header/navigation
│   │   ├── ModGrid.js         # Mod grid display
│   │   └── NewsList.js        # News listing component
│   ├── pages/                 # Page components
│   │   ├── AlloyCalculatorPage.js # Alloy calculator utility
│   │   ├── ArticlePage.js     # Single article view
│   │   ├── ArticlesPage.js    # Articles listing page
│   │   ├── HomePage.js        # Home page
│   │   ├── ModsPage.js        # Mods listing page
│   │   ├── NewsPage.js        # News page
│   │   └── RulesPage.js       # Server rules page
│   ├── data/                  # Static data files
│   │   ├── articles/          # Article content
│   │   │   ├── index.js       # Article exports
│   │   │   ├── karma-system.js
│   │   │   ├── server-guide.js
│   │   │   ├── test-article.js
│   │   │   └── winter-rescue.js
│   │   ├── mods.js            # Server mods data
│   │   └── news.js            # News items data
│   ├── utils/                 # Utility functions
│   │   ├── animations.js      # Animation helpers
│   │   ├── copyableIPs.js     # IP copy functionality
│   │   └── router.js          # Client-side router
│   ├── alloy.css              # Alloy calculator styles
│   ├── articles.css           # Article page styles
│   ├── custom-range-slider.css # Slider component styles
│   ├── main.js                # Application entry point
│   └── styles.css             # Main stylesheet
├── index.html                 # HTML entry point
├── package.json
└── README.md
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Flajakay/alegacy.online.git
   cd alegacy.online
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Development

Start the development server:
```bash
npm run dev
```

The site will be available at `http://localhost:5173` (or the next available port).

### Building for Production

Build the project:
```bash
npm run build
```

The output will be in the `dist` directory.

### Preview Production Build

Preview the production build locally:
```bash
npm run preview
```

## Features

- **Server Information**: Connection details and IPs for the Vintage Story server
- **Mods Page**: List of required mods with download links
- **Rules Page**: Server rules and guidelines
- **News Section**: Server announcements and updates
- **Articles**: Guides and tutorials for players
- **Alloy Calculator**: Interactive utility for calculating alloy compositions in Vintage Story
- **Responsive Design**: Works on desktop and mobile devices
- **Copy-to-Clipboard**: Easy IP copying with click

## License

This project is private and proprietary.
