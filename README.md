# Sanjoy Kumar - Academic Portfolio

A simple, academic-style portfolio website hosted on GitHub Pages.

## Structure

- `index.html` - Main page with bio, education, and recent news
- `research.html` - Research experience, publications, reports, and books
- `experiences.html` - Professional experience, teaching, entrepreneurship, and service
- `achievement.html` - Awards, honors, skills, and technical contributions

## Deployment

This site is designed to run on GitHub Pages at `https://imsanjoykb.github.io`

### Setup

1. Ensure all files are committed to the repository
2. Go to repository Settings > Pages
3. Set Source to "Deploy from a branch"
4. Select branch: `main` (or `master`)
5. Set folder: `/ (root)`
6. Click Save

The site will be automatically deployed to `https://imsanjoykb.github.io`

## Local Testing

To test locally:

```bash
# Using Python 3
python3 -m http.server 8000

# Then open http://localhost:8000 in your browser
```

Or simply open `index.html` directly in your browser.

## Customization

### Update Contact Information

Edit the following placeholders in `index.html`:
- `[PHONE]` - Your phone number
- `[EMAIL]` - Your email address

### Update Profile Picture

Replace `./img/propic.jpg` with your photo (recommended size: 400x400px)

### Update CV

Replace `Sanjoy_Kumar_CV.pdf` with your latest CV

## Technologies

- HTML5
- CSS3
- Bootstrap 3.4.1
- Font Awesome 5.8.1
- Academicons
- jQuery 3.3.1

## Style

This portfolio follows a minimalist, academic design similar to those used by professors and PhD students, with:
- Clean typography
- Simple navigation
- Focus on content over design
- Responsive layout for mobile devices
- No backend required

## License

See LICENSE file for details.
