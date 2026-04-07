# Copilot Instructions for Circular Material Futures Website

## Project Overview
This project is a static website for "Circular Material Futures," showcasing the transformation of discarded materials into architectural elements. The site includes multiple pages, animations, and a modern design.

### Key Files
- **HTML Files**: Define the structure of the website (e.g., `index.html`, `materials.html`).
- **CSS File**: `style.css` contains the styling for the website.
- **JavaScript File**: `script.js` implements scroll animations.
- **Assets**: Images are stored in the `img/` directory.

## Development Guidelines

### HTML
- Use semantic HTML tags for better accessibility and SEO.
- Maintain consistency in class naming conventions.

### CSS
- Use the defined CSS variables (e.g., `--main`, `--dark`) for consistent theming.
- Follow the mobile-first approach for responsive design.
- Avoid inline styles; use classes instead.

### JavaScript
- Use modern ES6+ syntax.
- Keep JavaScript modular and reusable.
- Ensure animations are smooth and performant.

## Common Tasks

### Adding a New Page
1. Create a new `.html` file in the root directory.
2. Link the `style.css` and `script.js` files.
3. Add the page link to the navbar in `index.html`.

### Updating Styles
1. Modify or add styles in `style.css`.
2. Use existing variables for colors and fonts.
3. Test changes across all pages for consistency.

### Implementing Animations
1. Add the appropriate class (`fade-up`, `fade-in`, `slide-left`) to the HTML element.
2. Ensure the `IntersectionObserver` in `script.js` is applied.

## Testing
- Open the website in a browser and test responsiveness.
- Verify animations work as expected.
- Check for broken links and console errors.

## Notes
- The project uses Google Fonts (Inter).
- Ensure all external links open in a new tab.

## Example Prompts
- "Add a new page for 'Sustainability' with a hero section."
- "Update the navbar to include a dropdown menu."
- "Add a fade-in animation to the hero section on the 'About' page."