# EPFL Safe AI Lausanne Website

This is the Jekyll-based website for EPFL Safe AI Lausanne (SAIL).

## Development

### Local Setup

1. Install Ruby and Bundler
2. Install dependencies: `bundle install`
3. Run locally: `bundle exec jekyll serve`
4. Visit: `http://localhost:4000`

### Updating Content

#### Events
Edit `_data/events.yml` to add/modify events. The calendar will automatically update.

#### Projects  
Edit `_data/projects.yml` to add new SAIL projects or update MLO lab opportunities.

#### Pages
Regular pages are in the root directory (about.html, projects.html, etc.)

### GitHub Pages

This site is configured to work with GitHub Pages automatically. Just push to the main branch and it will deploy.

## Structure

- `_layouts/default.html` - Main site template
- `_data/` - YAML files with content data
- `assets/` - Images and static files
- Root `.html` files - Individual pages

## Features

- Responsive design
- Event calendar (both list and calendar views)
- Dynamic content from YAML files
- SEO optimized with Jekyll SEO Tag
- Automatic sitemap generation