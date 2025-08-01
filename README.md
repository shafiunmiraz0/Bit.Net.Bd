# Bit.Net.Bd

# TechBit - Enterprise IT Solutions

![TechBit Logo](images/logo.jpg)

A modern, professional website for TechBit, showcasing enterprise IT infrastructure, cloud solutions, and digital transformation services.

## Table of Contents

- [Features](#features)
- [Pages](#pages)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Customization](#customization)
- [Responsive Design](#responsive-design)
- [Theme System](#theme-system)
- [JavaScript Functionality](#javascript-functionality)
- [License](#license)

## Features

✅ **Professional Design**  
✅ **Dark/Light Mode Toggle**  
✅ **Fully Responsive Layout**  
✅ **Interactive Elements**  
✅ **Animated Statistics**  
✅ **Testimonial Slider**  
✅ **Contact Form**  
✅ **Team Showcase**  
✅ **Blog System**  
✅ **Service Catalog**  

## Pages

1. **Homepage (`index.html`)**
   - Hero section with call-to-action
   - Services overview
   - Statistics counter
   - Team preview
   - Blog highlights
   - Testimonials
   - Contact CTA

2. **Services (`service.html`)**
   - Detailed service cards
   - Feature lists for each service
   - Process timeline visualization
   - Service icons

3. **Blog (`blog.html`)**
   - Article cards with categories
   - Search functionality
   - Category filtering
   - Popular posts sidebar
   - Newsletter signup

4. **Team (`team.html`)**
   - Leadership section
   - Team member cards with skills
   - Interactive filtering
   - Social links
   - Career CTA

5. **Contact (`contact.html`)**
   - Multiple contact methods
   - Interactive form with validation
   - Google Maps integration
   - Emergency support notice

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with variables
- **JavaScript** - Interactive elements
- **Font Awesome** - Icon library
- **Google Fonts (Inter)** - Modern typography
- **Google Maps API** - Location display

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/techbit-website.git
   ```

2. Navigate to the project directory:
   ```bash
   cd techbit-website
   ```

3. Open any HTML file in your browser or deploy to your preferred hosting service.

## Customization

### Content Changes

1. **Team Members**:
   - Update `team.html` with your team information
   - Add team member images to `images/` folder

2. **Services**:
   - Modify `service.html` to reflect your offerings
   - Update icons in the services section

3. **Blog Posts**:
   - Add articles in `blog.html`
   - Include featured images in `images/` folder

### Styling Changes

Edit the CSS variables in the `<style>` section of each HTML file:

```css
:root {
  --primary: #2563eb;
  --primary-dark: #1d4ed8;
  --secondary: #10b981;
  --dark: #0f172a;
  --light: #f8fafc;
  /* ... other variables ... */
}
```

### Images

Replace placeholder images in the `images/` folder with your own:
- `logo.svg` - Your company logo
- `team1.jpg`, `team2.jpg`, etc. - Team member photos
- `blog1.jpg`, `blog2.jpg`, etc. - Blog post images
- `client1.svg`, `client2.svg`, etc. - Client logos

## Responsive Design

The website is fully responsive and includes:
- Mobile-friendly navigation
- Adaptive grid layouts
- Responsive typography
- Mobile-optimized forms

Breakpoints:
- Desktop: 992px and up
- Tablet: 768px - 991px
- Mobile: 767px and below

## Theme System

The site features a dark/light mode toggle that:
- Uses CSS variables for easy theming
- Saves user preference in localStorage
- Provides smooth transitions between themes

To modify themes:
```css
[data-theme="light"] {
  --dark: #f8fafc;
  --dark-light: #e2e8f0;
  --light: #0f172a;
  /* ... other light theme variables ... */
}
```

## JavaScript Functionality

Key interactive features:

1. **Theme Toggler**:
   - Switches between dark/light modes
   - Persists user preference

2. **Mobile Navigation**:
   - Hamburger menu for small screens
   - Smooth animations

3. **Testimonial Slider**:
   - Auto-rotating testimonials
   - Dot navigation controls

4. **Counter Animation**:
   - Animated statistics on scroll

5. **Contact Form**:
   - Basic form validation
   - Submission handling

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**TechBit** - Empowering your digital infrastructure with cutting-edge IT solutions.