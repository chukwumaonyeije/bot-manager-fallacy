# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Project Overview

This is a Jekyll-based GitHub Pages site for "Doctors Who Code," a platform exploring AI, clinical workflows, and the future of medicine. The site uses the Minima theme and is deployed at `https://chukwumaonyeije.github.io/bot-manager-fallacy/`.

## Development Commands

### Setup
```powershell
# Install dependencies (first time only)
bundle install
```

### Local Development
```powershell
# Run Jekyll development server
bundle exec jekyll serve

# Site will be available at: http://localhost:4000/bot-manager-fallacy/
```

### Build
```powershell
# Build static site (output to _site/)
bundle exec jekyll build
```

## Architecture

### Site Structure
- **`_config.yml`**: Jekyll configuration including site metadata, theme settings, plugins, and URL structure
- **`index.md`**: Homepage with site introduction and featured content
- **`blog/`**: Blog articles directory
  - `blog/index.md`: Blog landing page listing all articles
  - `blog/*.md`: Individual blog posts (currently: `bot-manager-fallacy.md`)
- **`Gemfile`**: Ruby dependencies including `github-pages` gem and Jekyll plugins

### Key Configuration Details
- **Base URL**: `/bot-manager-fallacy` - all internal links must be relative to this base
- **Theme**: Minima (GitHub Pages compatible)
- **Plugins**: jekyll-feed, jekyll-seo-tag, jekyll-sitemap
- **Markdown**: Kramdown with GFM (GitHub Flavored Markdown) input

### Content Management

#### Adding New Blog Articles
1. Create new `.md` file in `blog/` directory
2. Include YAML front matter:
   ```yaml
   ---
   layout: post  # or 'default' depending on desired layout
   title: "Article Title"
   ---
   ```
3. Update `blog/index.md` to link to the new article
4. Internal links should use format: `/blog/article-name` (relative to baseurl)

#### Updating Site Metadata
- Modify `_config.yml` for site title, description, author info, social links
- SEO tags are automatically generated via jekyll-seo-tag plugin

### URL Routing
- Homepage: `/` → `index.md`
- Blog index: `/blog/` → `blog/index.md`
- Blog posts: `/blog/[title]` → `blog/[title].md`
- All URLs are relative to the baseurl `/bot-manager-fallacy`

### Deployment
The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch. GitHub Pages builds the site using the `github-pages` gem which ensures compatibility with GitHub's Jekyll environment.

## Platform Notes

This is a Windows development environment using PowerShell. Jekyll commands should be run with `bundle exec` prefix to ensure correct gem versions are used.
