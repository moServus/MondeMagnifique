# De beaux Voyages 🏴󠁧󠁢󠁥󠁮󠁧󠁿 Wonderful Trips

## Les statuts 🏴󠁧󠁢󠁥󠁮󠁧󠁿 Status
🏋🏼‍♂️ travail en cours

## Voyage prévu 🏴󠁧󠁢󠁥󠁮󠁧󠁿 Planned journey
🏋🏼‍♂️ [Mein Wien DE 🇩🇪](./wikiViennaAT/abstracts/ViennaDE.md) Recherché le début Samedi, 20.Juin le matin. Départ 15.Août e Retour 17.

# Open Source "Monde 🌍 Magnifique 🤩" Instructions

## Directory Structure

```
MondeMagnifique/
├── README.md
├── CLAUDE.md
├── index.md
├── Gemfile
├── _config.yml
├── wikiViennaDE.md
├── assets/
│   └── css/
│       └── style.css
├── _layouts/
│   └── default.html
├── .github/
│   └── workflows/
│       └── pages.yml
└── wikiViennaAT/
    └── abstracts/
        ├── ViennaDE.md
        └── picsWien/
            └── flag.png
```

## Files Summary

### Root Level

| File | Purpose |
|------|---------|
| [README.md](README.md) | Project overview with travel status. Documents planned Vienna trip and open-source project structure (work in progress) |
| [CLAUDE.md](CLAUDE.md) | Development guide for Claude Code. Contains project overview, setup instructions, conventions, and custom command definitions (/abstract, /readme) |
| [wikiViennaDE.md](wikiViennaDE.md) | Source list of 7 German Wikipedia links covering Vienna attractions (city, cemetery, Schönbrunn Palace, Kaisergruft, Secession, Hundertwasserhaus, Heuriger) |

### wikiViennaAT/abstracts/

| File | Purpose |
|------|---------|
| [ViennaDE.md](wikiViennaAT/abstracts/ViennaDE.md) | Comprehensive Vienna abstract for tourists covering: **History** (Roman Vindobona → Habsburg Empire → WWI), **Tourism** (Schönbrunn, St. Stephen's Cathedral, Hofburg Palace), **Fun Facts** (100+ museums, UNESCO coffee culture, Ferris wheel, wine production) |
| [picsWien/flag.png](wikiViennaAT/abstracts/picsWien/flag.png) | Vienna city emblem/flag image |

## GitHub Pages Setup

✅ **Jekyll Configuration** (`_config.yml`)
- Site title, description, and metadata
- Theme and plugin configuration
- Auto-generated sitemap for SEO

✅ **Landing Page** (`index.md`)
- Beautiful homepage with Vienna information
- Quick facts table
- Links to your travel guides
- Trip planning section

✅ **Custom Styling** (`assets/css/style.css`)
- Professional design with Austrian flag colors
- Responsive mobile-friendly layout
- Hover effects and modern typography

✅ **Custom Layout** (`_layouts/default.html`)
- Header with navigation
- Footer with links
- Open Graph meta tags for social sharing

✅ **Automated Deployment** (`.github/workflows/pages.yml`)
- Automatically builds and deploys on every push to `main`
- Uses GitHub Actions (free for public repos)

✅ **Dependencies** (`Gemfile`)
- All Ruby/Jekyll dependencies managed properly

### Access Your Site
Visit: **https://moservus.github.io/MondeMagnifique**

## Project Purpose

A documentation-based travel guide for Vienna, Austria ("Mein Wien" / My Vienna) with Wikipedia sources analyzed into tourist-friendly abstracts.
