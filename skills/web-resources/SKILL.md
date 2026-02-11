---
name: web-resources
description: Find, download, and organize free commercially-usable web resources (images, audio, videos, icons, fonts, animations) from reputable sources. Use when users request resources for web development like "I need button click sound effects", "Find me free images for my website", "Download free icons", or when given a file to analyze for missing resources. Automatically downloads and organizes resources by type into appropriate directories.
---

# Web Resources

A curated collection of free, commercially-usable web development resources including icons, images, audio, animations, and code templates.

## Quick Start

1. **Identify need**: Determine resource type (icon, image, audio, animation, template)
2. **Select source**: Pick appropriate source from [resources.md](references/resources.md)
3. **Fetch/Generate**: Use GitHub raw URLs, APIs, or generate code directly

## Resource Categories

### Icons (SVG)
Direct GitHub access - read SVG source code directly:
- **Heroicons**: `https://raw.githubusercontent.com/tailwindlabs/heroicons/master/src/24/outline/{name}.svg`
- **Remix Icon**: `https://raw.githubusercontent.com/Remix-Design/RemixIcon/master/icons/{category}/{name}.svg`
- **Tabler Icons**: `https://raw.githubusercontent.com/tabler/tabler-icons/main/icons/outline/{name}.svg`

### Images & Video (API)
Require API keys - guide user to obtain:
- **Pexels API**: Search photos/videos, returns direct download URLs
- **Pixabay API**: Millions of royalty-free images and vectors
- **Unsplash API**: High-quality photography

### Audio (API)
- **Freesound API**: Sound effects searchable by keyword (click, ui, ambient)
- **Tosound**: Chinese CC0 audio, URL pattern: `https://www.tosound.com/search/{keyword}`

### Animations
- **Lottie JSON**: Parse and embed JSON animations directly
- **CSS Loaders**: Extract pure CSS loading animations from css-loaders.com
- **Anime.js**: Generate timeline-based JS animations

### Code Templates (GitHub)
Clone or read directly:
- **Tabler**: Bootstrap dashboard UI kit
- **Flowbite**: Tailwind CSS components
- **Cruip**: Landing page templates

## Common Workflows

### Finding an Icon
```
1. Search icon name in Heroicons/Remix/Tabler GitHub repos
2. Fetch raw SVG content via GitHub raw URL
3. Inline SVG or save to assets folder
```

### Getting Stock Images
```
1. User provides Pexels/Pixabay API key (or guide to obtain free key)
2. Search via API with keywords
3. Download from returned URLs to project assets
```

### Adding Loading Animation
```
1. Browse css-loaders.com for desired style
2. Extract CSS code for the animation
3. Integrate into project stylesheet
```

## Full Resource List

See [references/resources.md](references/resources.md) for complete URLs, API documentation links, and detailed usage instructions for each resource.
