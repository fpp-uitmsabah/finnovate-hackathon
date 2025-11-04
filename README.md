# FIN-novate Hackathon 2025

## Overview

FIN-novate Hackathon 2025 is an innovative event transforming traditional financial education at UiTM through AI-powered solutions and real-world problem solving. This repository contains the comprehensive analysis report and event website.

## Recent Enhancements

This PR includes significant UI and functionality improvements to the FIN-novate Hackathon website:

### New Features Added

1. **Timeline Section** - Visual event timeline showing key dates and milestones from kickoff through final submission
2. **Prizes Section** - Detailed breakdown of prizes and recognition for winning teams (1st: RM 1,000, 2nd: RM 600, 3rd: RM 400)
3. **FAQ Section** - Accordion-style frequently asked questions about participation, AI tools, evaluation, and deliverables
4. **Mobile Navigation** - Responsive hamburger menu for mobile devices with smooth transitions
5. **Skip-to-Content Link** - Accessibility enhancement for keyboard navigation

### Improvements

- **SEO & Social Media**: Added meta description and Open Graph tags for better sharing
- **Favicon**: Added custom favicon.ico file for browser tab identification
- **Image Optimization**: 
  - Replaced placeholder URLs with local images (hack1-4.png)
  - Added descriptive alt text for all challenge images
  - Implemented lazy loading for images
  - Added fallback handling for missing hero_image.png
- **Performance**: Lazy-loaded ECharts initializations with loading placeholders
- **Accessibility**: 
  - ARIA labels and roles throughout navigation
  - Enhanced keyboard focus states with visible outlines
  - Semantic HTML improvements
- **Code Cleanup**: Removed unused p5.js and Splide.js libraries
- **Styling**: 
  - Print stylesheet for professional report printing
  - Dark mode support with prefers-color-scheme
  - Improved color contrast for better readability
  - Smooth scrolling behavior

### Technical Details

- Single-page application using vanilla JavaScript
- Charts powered by ECharts with lazy initialization
- Animations using anime.js
- Responsive design with Tailwind CSS
- No build process required - pure HTML/CSS/JS

## File Structure

```
finnovate-hackathon/
├── index.html          # Main website with all sections
├── assets/
│   └── favicon.ico     # Browser favicon
├── hack1.png           # Challenge images
├── hack2.png
├── hack3.png
├── hack4.png
└── README.md          # This file
```

## Event Details

- **Target Audience**: FIN333 Students at UiTM
- **Team Size**: 5-6 members
- **Duration**: 5 weeks
- **Deliverables**: 30-slide infographic report + 10-minute pitch video
- **Total Score**: 100 points (50% report, 50% presentation)

## Challenges

The hackathon addresses 12 investment literacy challenges across three categories:

1. **Foundational Mindset** (4 challenges)
2. **Investment Vehicles** (5 challenges)
3. **Practical Barriers** (3 challenges)

## AI Integration

The event includes a comprehensive AI Accelerator Workshop covering:

- **Module 1**: AI for Analysis (using Gemini)
- **Module 2**: AI for Design (using Canva Code, image generators)
- **Module 3**: AI for Ethics (ethical AI usage and disclosure)

## Viewing the Website

Simply open `index.html` in a modern web browser. No server or build process required.

## Browser Compatibility

Tested and optimized for:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

Educational project for UiTM FIN333 course.
