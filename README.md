# DEX Portfolio

A modern, single-page developer portfolio built with plain HTML, CSS, and JavaScript.

## Overview

This project is a responsive personal portfolio website with smooth scrolling navigation, animated UI sections, skill progress bars, project cards, and a contact form interaction.

It also includes an interactive mouse-proximity background effect that reacts to cursor movement for a more dynamic visual experience.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Font Awesome (CDN)
- Google Fonts (Poppins)

## Project Structure

- `index.html` - Page structure and content sections
- `styles.css` - Layout, styling, responsive design, and visual effects
- `script.js` - Navigation behavior, animations, typing effect, and interactive background logic
- `wallpaper.jpg` - Image asset used in profile/about/projects sections

## Features

- Fixed header with section-based active navigation state
- Smooth scroll navigation
- Typing animation for role text
- Scroll-reveal section animations
- Animated skill progress bars
- Project hover overlays
- Contact form submit interaction
- Responsive layout for desktop, tablet, and mobile
- Mouse-proximity interactive background glow/grid effect

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/Nana-Kofi-Agyin/DEX-Portfolio.git
   ```

2. Open the project folder:

   ```bash
   cd DEX-Portfolio
   ```

3. Run locally:

   - Open `index.html` directly in your browser, or
   - Use a local server (recommended), for example:

   ```bash
   python -m http.server 5500
   ```

4. Visit:

   ```
   http://localhost:5500
   ```

## Customization

- Update personal text and links in `index.html`
- Replace `wallpaper.jpg` with your own image
- Change theme colors using CSS variables in `styles.css` (`:root`)
- Edit typed roles in `script.js` (`typedText` array)

## Accessibility and Motion

- Includes support for reduced-motion preferences for the interactive background transitions.
- Ensure social/project links are updated from placeholders (`#`) before production use.

## Deployment

You can deploy this as a static site using:

- GitHub Pages
- Netlify
- Vercel

No build step is required.

## License

This project is open for personal and educational use. Add a formal license file if you plan to distribute or open-source it publicly.
