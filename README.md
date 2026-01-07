# Professional Portfolio Website

A modern, responsive portfolio website with a clean and professional design.

## Features

- **Fixed Navigation Bar** - Always accessible with smooth scrolling to sections
- **Logo** - Links back to home page from any page
- **Header Section** - Features a circular headshot photo and introduction
- **About Section** - Personal introduction and background
- **Skills Section** - Showcase your expertise in different areas
- **Recent Work Section** - Display your projects and writing with links to detailed pages
- **Footer** - Contact links and copyright information
- **Responsive Design** - Works beautifully on desktop, tablet, and mobile devices

## File Structure

```
portfolio-website/
├── index.html          # Main homepage
├── styles.css          # All styling
├── script.js           # Smooth scrolling and animations
├── project-1.html      # Sample project detail page
├── project-2.html      # Sample project detail page
├── project-3.html      # Sample project detail page
└── README.md           # This file
```

## Customization

### 1. Personal Information
- Update your name in `index.html` (header section)
- Replace the placeholder headshot image URL with your own photo
- Customize the "About Me" section with your personal story
- Update the footer with your actual social media links

### 2. Skills
- Edit the skill cards in the Skills section
- Update skill names and descriptions to match your expertise

### 3. Projects
- Modify the project cards in the Recent Work section
- Update project titles, descriptions, and links
- Customize the project detail pages (`project-1.html`, `project-2.html`, etc.)
- Add or remove project entries as needed

### 4. Logo
- Replace the "LOGO" placeholder with your actual logo image or text
- The logo is styled in the `.logo-placeholder` class in `styles.css`

### 5. Colors
- Customize the color scheme by modifying CSS variables in `styles.css`:
  ```css
  :root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    /* ... other colors */
  }
  ```

## Usage

1. Open `index.html` in a web browser to view the portfolio
2. All project links open in new tabs as specified
3. The logo always links back to the home page
4. Navigation links smoothly scroll to their respective sections

## Browser Support

This website uses modern CSS features and works best in:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Notes

- The headshot image currently uses a placeholder. Replace the `src` attribute in the `<img>` tag with your actual photo URL or local file path.
- All project detail pages include a "Back to Recent Work" link that returns to the main page.
- The navigation bar is fixed at the top and remains visible while scrolling.

