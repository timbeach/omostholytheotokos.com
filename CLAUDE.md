# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML website (omostholytheotokos.com) focused on Orthodox Christian prayer resources and educational content. The site serves audio recordings of prayers, the psalter, and educational materials.

## Development Commands

Since this is a static HTML/CSS/JavaScript website, there are no build, test, or compilation commands. The site can be served directly by any web server.

For local development:
- Use any static file server (e.g., `python -m http.server 8000` or `npx http-server`)
- Files can be edited directly and viewed in browser

## Site Structure

### Main Pages
- `index.html` - Main landing page with prayer audio recordings and Orthodox icons
- `psalter_audio.html` - Complete psalter with 20 Kathisma audio recordings
- `tonetutor.html` - Tone 1 audio lessons for Orthodox liturgical music

### Content Directories
- `Prayers/` - Audio files for daily prayers (Morning, Evening, Before Communion, Paschal)
- `Prayers/psalter/` - 20 Kathisma MP3 files from Patristic Nectar Publications
- `OrthodoxSurvivalCourse/` - PDF lectures by Fr. Seraphim Rose with audio recordings
- `ToneTutor/TONE_01/` - Audio lessons for liturgical tone learning

### Styling
- Inline CSS in HTML files uses consistent Orthodox-themed color scheme
- `style.css` - Alternative stylesheet (appears unused in current pages)
- CSS variables: `--primary-color: #3A4D39`, `--secondary-color: #AE8612`

## Audio Sources
- Holy Cross Monastery recordings for daily prayers
- Patristic Nectar Publications for psalter recordings
- Various Orthodox educational audio content

## Navigation Pattern
- Simple HTML navigation with back links between pages
- External links to source monasteries and publications
- Responsive design for mobile and desktop viewing

## File Conventions
- HTML files use semantic structure with header, content sections, and footer
- Audio files organized by content type in subdirectories
- Images include Orthodox icons and saints
- All external links open in new tabs for educational resources
- to memorize