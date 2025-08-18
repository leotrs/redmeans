# red means

An art photography project exploring color, meaning, and perception through monochrome images with selective red elements.

## About the Project

Each photograph captures a subject, partially or completely red, isolated in a
monochrome world. The literal (a tomato, a traffic pole) becomes abstract (patience,
decorative). Red means what we decide it means.

## Photography Process

### Equipment
- **Camera**: Android smartphone (no professional equipment)
- **Editing**: Android mobile apps (e.g. Snapseed, no Photoshop)

## Technical Setup

1. Image Hosting: Cloudinary
2. Web Deployment: Netlify

### Development Workflow

1. **Local Development**:
   ```bash
   # Simple local server for testing
   python -m http.server 8000
   # or
   npx serve .
   ```

2. **Image Updates**:
   - Upload new images to Cloudinary
   - Copy the generated URLs
   - Update HTML with new Cloudinary URLs
   - Deploy updated HTML to Netlify

3. **Performance**:
   - Images automatically optimized by Cloudinary
   - Static HTML/CSS served by Netlify CDN
   - No build process required

## Project Structure

```
redmeans/
├── index.html          # Main gallery website
├── README.md          # This documentation
└── assets/            # Local assets (if any)
```

## Typography

- **Headers/Titles**: Manrope (Google Fonts)
- **Numbers**: JetBrains Mono (Google Fonts)
- **Body Text**: Manrope (Google Fonts)

## Color Palette

```css
--ink-black: #0f1419    /* Background */
--charcoal: #2a3441     /* Secondary elements */
--steel: #475569        /* Muted text */
--off-white: #fafafa    /* Primary text */
```

## Features

- **Responsive Design**: Works on mobile and desktop
- **Gallery View**: Large format browsing
- **Grid View**: Overview of all pieces
- **Lightbox**: Full-size image viewing
- **About Panel**: Project information sidebar
- **Keyboard Navigation**: ESC to close modals
- **Optimized Images**: Fast loading via Cloudinary

## Location

Leipzig, Germany

---

*An artsy fartsy project by [leotrs](https://leotrs.com)*
