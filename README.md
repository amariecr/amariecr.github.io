# Amarie Crawford - Portfolio Website

This is a modern, one-page portfolio website built with HTML, CSS, and JavaScript. It features smooth animations, a rich red accent color, and sections for showcasing your skills, projects, resume, and contact information.

## Features

- **Responsive Design**: Works on desktop and mobile devices
- **Modern Animations**: Fade-in effects on scroll, hover animations on project cards
- **Rich Red Accent**: #DC143C (Crimson) used throughout for visual appeal
- **One-Page Layout**: All content in a single scrollable page
- **Contact Form**: Basic form for visitors to send messages
- **GitHub Integration**: Direct link to your GitHub profile
- **Resume Section**: Placeholder for PDF resume download

## File Structure

- `index.html` - Main HTML structure
- `styles.css` - CSS styles and animations
- `script.js` - JavaScript for interactivity
- `resume.pdf` - Your resume file (add this when ready)

## Customization

### Adding More Projects

To add more projects, edit the `index.html` file and add more `<div class="project-card">` elements inside the `.projects-grid` div:

```html
<div class="project-card">
    <h3>Project Name</h3>
    <p>Project description...</p>
    <a href="https://github.com/yourusername/project-repo" target="_blank" class="project-link">View on GitHub</a>
</div>
```

### Updating Skills

Edit the skills in the `#skills` section by modifying the `.skill-item` divs.

### Changing Colors

The accent color is defined as `#DC143C`. To change it, search for this hex code in `styles.css` and replace with your preferred color.

### Adding Images

To add profile pictures or project screenshots:

1. Add image files to your project directory
2. Reference them in `index.html` using `<img>` tags
3. Style them in `styles.css`

## Deployment

To deploy this website:

1. Host the files on a web server (GitHub Pages, Netlify, Vercel, etc.)
2. Upload your `resume.pdf` file
3. Update any links or content as needed

## Technologies Used

- HTML5
- CSS3 (with animations and transitions)
- Vanilla JavaScript

## Browser Support

Works in all modern browsers that support CSS Grid and ES6+ JavaScript.