# Portfolio Website

## Overview
This is a static portfolio website for Syed Rayan (aka BMR), a Mechanical Engineering Student, Developer, and Content Creator, showcasing 3D/Three.js projects and creative work.

## Project Structure
- `index.html` - Main homepage
- `style.css` - Main stylesheet with custom CSS additions
- `main.js` - Main JavaScript file
- `portrait.png` - Profile portrait image
- `src/` - Assets directory
  - `png/` - PNG images
  - `svg/` - SVG icons
  - `webp/` - WebP images
  - `mp3/` - Audio files
  - `pdf/` - Resume PDFs
  - `ico/` - Favicon files
- Additional HTML pages: `404.html`, `comingsoon.html`, etc.

## Technology Stack
- Pure HTML/CSS/JavaScript (no build system)
- Static file serving with `serve` package
- AOS (Animate on Scroll) library via CDN

## Running the Project
The website is served using the `serve` package on port 5000:
```
cd SYEDRAYAN-PF && npx serve -l 5000 -s .
```

## Deployment
Configured as a static site deployment serving from the root directory.

## Recent Changes (December 18, 2025)
- ✅ **Removed Discord live presence** - Removed all Discord Lanyard API code and styling
- ✅ **Added navbar title** - "rayan.is-a.dev" displayed in navbar with hover effects
- ✅ **Enhanced about section styling** - Added gradient background, border, blur effect, and smooth hover animations
- ✅ **Improved project descriptions** - Replaced generic text with professional, descriptive project details:
  - BALOONS: Interactive 3D scene with particle systems
  - 3D EARTH: Rotating globe with realistic textures
  - 3D ROOM: Immersive environment with lighting
  - 3D JENGA TOWER: Physics-based game implementation
  - INTERACTIVE EXPERIENCE: Innovative 3D design
  - CREATIVE PROJECT: New 3D creation in development
- ✅ **Renamed button** - "VISIT PORTFOLIO" → "VIEW CV" with new link to cv.html
- ✅ **Updated social icons** - Replaced GitHub icon with Discord icon in footer and project cards
- ✅ **Improved about section text** - Updated with professional description of focus and skills
- ✅ **Enhanced intro box styling** - Improved spacing, proportions, and visual hierarchy with stronger glow effects
- ✅ **Created coming soon page** - Beautiful comingsoon.html with animated backgrounds, shimmer effects, progress bar, and contact links
- ✅ **Created CV page** - cv.html with professional "CV not available for everyone" message and social links
- ✅ **Updated all social media links** - Verified across index.html, comingsoon.html, and cv.html:
  - Instagram: https://www.instagram.com/bmr.ez/
  - YouTube: https://www.youtube.com/@BmrEditz-1
  - Discord: https://discord.com/invite/t6hvHaunkT
  - TikTok: https://www.tiktok.com/@bmreditz1?is_from_webapp=1&sender_device=pc
- ✅ **Enhanced navbar title styling** - Added backdrop gradient, border, rounded corners, and blur effects for premium look
- ✅ **Improved social icons** - Larger size (55px), stronger borders (2.5px), enhanced glow effects on hover with elevated transform

## UI Improvements Summary
- Social icons now feature smoother hover transitions with stronger glow effects and elevated positioning
- All pages maintain consistent dark theme with purple-cyan gradient aesthetic
- Professional animations and transitions throughout
- **Project Cards Redesigned** - Modern vertical card layout with:
  - Featured image at top (280px) with zoom/brightness hover effects
  - Properly fitted images with object-fit: cover
  - Clean text section below with title, description, and buttons
  - Smooth hover animations with radial gradient glow
  - Better visual hierarchy and spacing

## Pages Available
- `index.html` - Main portfolio homepage with projects section
- `comingsoon.html` - Professional coming soon page for pending projects
- `cv.html` - CV information page
- `404.html` - 404 error page

## Notes
- All changes maintain dark mode theme and existing design patterns
- Responsive design preserved across all screen sizes
- No breaking changes to existing functionality
- Premium glowing effects and smooth animations throughout
