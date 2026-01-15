# KIDS SCHOOL - AMF English School Website

A modern, responsive single-page website for KIDS SCHOOL (AMF English School redesign) built with HTML, CSS, TailwindCSS, and JavaScript.

## Features

- **Responsive Design**: Works perfectly on all devices (mobile, tablet, desktop)
- **Modern UI**: Clean, professional design with TailwindCSS
- **Interactive Elements**: Smooth scrolling, mobile menu, hover effects
- **Fast Loading**: Optimized with TailwindCSS CDN
- **SEO Friendly**: Proper semantic HTML structure

## Sections

1. **Header/Navbar**: Logo, navigation menu, and login button
2. **Hero Section**: Main call-to-action with image grid
3. **Why Choose Us**: Trust-building section
4. **Features**: 4 benefit cards (Safe Environment, Experienced Faculty, Digital Classrooms, Co-curricular Activities)
5. **Activities Gallery**: Visual showcase of school activities
6. **Call-to-Action**: Enrollment encouragement section
7. **Footer**: Contact information and social links

## Technologies Used

- **HTML5**: Semantic structure
- **TailwindCSS**: Utility-first CSS framework
- **JavaScript**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Typography (via Tailwind)

## How to Run

### Option 1: Using Python (if available)
```bash
python -m http.server 8000
```

### Option 2: Using Node.js
```bash
npx serve . -p 8000
```

### Option 3: Using any local server
Open `index.html` directly in a web browser (some features may not work due to CORS)

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Color Scheme

- **Primary**: #FF6B35 (Orange)
- **Secondary**: #1E3A8A (Blue)
- **Accent**: #F59E0B (Amber)

## File Structure

```
/
├── index.html          # Main HTML file
└── README.md          # This file
```

## Customization

### Changing Colors
Edit the Tailwind config in the `<script>` tag within `index.html`:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#YOUR_COLOR',
                secondary: '#YOUR_COLOR',
                accent: '#YOUR_COLOR'
            }
        }
    }
}
```

### Adding New Sections
Add new sections between existing sections in the HTML file.

### Modifying Content
Update text, images, and links directly in the HTML file.

## Images

The website uses Unsplash images for demonstration. Replace with your actual school images:

- Hero section images
- Activity gallery images
- Feature icons

## Contact

For customization or questions, contact the development team.