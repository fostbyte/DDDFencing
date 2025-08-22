# DDD Fencing - Professional Fencing Solutions

## Overview

DDD Fencing is a static HTML/CSS website for a professional fencing company offering comprehensive fencing solutions for residential, commercial, and industrial clients. The site serves as a digital brochure showcasing various fencing services including chain link, vinyl, security, and commercial fencing options. Built as a multi-page website with dedicated service detail pages, the site emphasizes professional presentation, easy navigation, and clear calls-to-action for quote requests.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
The website follows a traditional multi-page static site architecture with semantic HTML5 structure and modern CSS styling. Each page maintains consistent navigation and branding while providing specialized content for different services.

**Key Design Decisions:**
- **Static HTML/CSS approach**: Chosen for simplicity, fast loading times, and easy hosting on platforms like GitHub Pages
- **Multi-page structure**: Separate dedicated pages for each major service (residential, commercial, chain link, vinyl, security fencing) to provide detailed information and improve SEO
- **Responsive design patterns**: CSS Grid and Flexbox layouts ensure compatibility across devices
- **Component-based CSS**: Modular CSS classes for reusable UI elements like buttons, cards, and navigation

### Typography and Styling System
- **Primary fonts**: Inter for body text (modern, readable sans-serif) and Roboto Slab for headings (professional serif)
- **Icon system**: Font Awesome 6.4.0 for consistent iconography
- **Color scheme**: Professional blue/gray palette appropriate for construction/service industry
- **CSS organization**: Single stylesheet approach with logical section organization

### Navigation Structure
- **Fixed header navigation**: Consistent across all pages with active state indicators
- **Mobile-responsive menu**: Hamburger toggle for mobile devices
- **Cross-page linking**: Smart navigation between main site sections and individual service pages
- **Breadcrumb-style navigation**: Clear hierarchy between main site and service detail pages

### Content Architecture
- **Hero-driven homepage**: Large hero section with clear value proposition and call-to-action buttons
- **Service showcase**: Grid-based service listings on homepage linking to detailed service pages
- **Dedicated contact page**: Separate contact page for lead generation and customer inquiries
- **Service detail pages**: Individual pages for each fencing type with detailed descriptions and specifications

### Performance Considerations
- **Font optimization**: Preconnect directives for Google Fonts to improve loading performance
- **External resource management**: Minimal external dependencies (Google Fonts and Font Awesome CDN)
- **Image optimization**: SVG logo format for crisp scaling and fast loading

## External Dependencies

### CDN Resources
- **Google Fonts**: Inter and Roboto Slab font families for typography
- **Font Awesome**: Version 6.4.0 for icons and visual elements

### Hosting Compatibility
- **GitHub Pages ready**: Static HTML/CSS structure designed for easy deployment on GitHub Pages
- **No server-side requirements**: Pure frontend implementation requiring no backend infrastructure

### Browser Support
- **Modern CSS features**: Uses Flexbox and CSS Grid for layouts
- **Progressive enhancement**: Graceful degradation for older browsers while optimizing for modern web standards

### Development Tools
- **CSS preprocessing**: Single CSS file approach without build tools for simplicity
- **Version control**: Git-friendly structure with organized file hierarchy