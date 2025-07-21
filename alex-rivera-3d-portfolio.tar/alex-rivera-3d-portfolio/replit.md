# Alex Rivera - 3D Design Portfolio

## Overview

This is a personal portfolio website for Alex Rivera, a 3D designer and digital artist. The project features an immersive 3D navigation interface with rotating cards that serve as portals to different portfolio sections. Built entirely with vanilla HTML, CSS, and JavaScript, the site emphasizes innovative 3D interactions and visual depth to showcase creative digital art expertise.

## User Preferences

Preferred communication style: Simple, everyday language.
Design preference: Emphasis on 3D design elements and interactive card-based navigation.

## System Architecture

**Frontend-Only Multi-Page Architecture**: This is a static website built entirely on the client-side using vanilla web technologies with separate pages for different sections. No backend server or database is required for the core functionality.

**Technology Stack**:
- HTML5 for structure and semantic markup
- CSS3 for styling, animations, responsive design, and 3D effects
- Vanilla JavaScript for interactivity and dynamic behavior
- External CDNs for fonts (Google Fonts) and icons (Font Awesome)

**Page Structure**:
- `index.html` - Immersive 3D homepage with rotating navigation cards and floating background elements
- `about.html` - About section with personal information and stats
- `portfolio.html` - Portfolio showcase with project cards and modals
- `skills.html` - Skills and expertise display with progress bars
- `contact.html` - Contact form and information

## Key Components

### 1. 3D Navigation System
- **Interactive rotating cards** that flip on hover and navigate on click
- **3D spatial navigation** with perspective and depth effects
- **Immersive background** with floating spheres, cubes, and particles
- **Touch and keyboard navigation** support for accessibility

### 2. User Interface Elements
- **Modal system** for project details (referenced in JavaScript)
- **Contact form** with client-side handling
- **Intersection Observer** for scroll-triggered animations
- **Mobile-first responsive design**

### 3. Interactive Features
- **3D card rotation** with hover and click animations
- **Mouse parallax effects** that respond to cursor movement
- **Loading screen** with 3D spinning cube animation
- **Page transitions** with smooth 3D effects between sections
- **Performance optimization** for lower-end devices

## Data Flow

**Static Content Flow**:
1. HTML provides the structure and content
2. CSS handles all visual presentation and responsive behavior
3. JavaScript adds interactivity and dynamic behavior
4. External CDNs provide fonts and icons

**User Interaction Flow**:
1. User navigates between pages via navbar links
2. JavaScript handles mobile hamburger menu toggle
3. Contact form submissions handled client-side (contact.html)
4. Project modals display additional portfolio details (portfolio.html)
5. Animated 3D background effects provide visual depth

## External Dependencies

### CDN Resources
- **Google Fonts**: Inter font family (weights 300-700)
- **Font Awesome 6.4.0**: Icon library for UI elements

### Browser APIs
- **Intersection Observer API**: For scroll-triggered animations
- **Scroll behavior**: For smooth navigation transitions

## Deployment Strategy

**Static Hosting Compatible**: This project can be deployed on any static hosting platform since it requires no server-side processing:

- **Recommended platforms**: Netlify, Vercel, GitHub Pages, or any static file hosting
- **Requirements**: Only needs to serve HTML, CSS, JavaScript, and any image assets
- **Performance**: Optimized for fast loading with minimal external dependencies
- **Scalability**: Inherently scalable as a static site with CDN delivery

The site is designed to be lightweight and performant, with all assets loading from reliable CDNs and minimal JavaScript for optimal user experience across devices.