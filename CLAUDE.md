# CLAUDE.md - Development Guide for Untold Garden Website

## Build Commands
- Build site: `bundle exec jekyll build`
- Run development server: `bundle exec jekyll serve`
- Run with live reload: `bundle exec jekyll serve --livereload`

## Project Structure
- `_projects/`: Collection of project markdown files (displayed on the projects page)
- `_layouts/`: HTML templates for different page types
- `assets/`: Static files (CSS, images, fonts)

## Style Guidelines
- **Markdown**: Use consistent heading levels (# for title, ## for sections)
- **Front Matter**: Include layout, title, description, permalink, og_image, og_image_width, og_image_height
- **Images**: Use WebP format, placed in assets/images/
- **CSS**: Follow existing BEM-like naming conventions
- **Indentation**: 4 spaces

## Content Formatting
- Use blockquotes (>) for highlighted text/quotes
- Use italic (*text*) for emphasis
- For embedded videos, use the provided `.vimeo` or `.vimeo-square` containers
- Image captions: Use `.video-caption` or `.caption` classes