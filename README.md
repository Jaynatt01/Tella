# Resin and Craft Supplies - Landing Page

A modern, responsive landing page for your resin and craft supplies business in Lagos, Nigeria.

## Features

### 🎨 Design Features
- **Modern Design**: Clean, professional layout with brand colors (red/coral and black)
- **Responsive Layout**: Works perfectly on all devices (desktop, tablet, mobile)
- **Brand Integration**: Designed to complement your brand logo and product images
- **Beautiful Animations**: Smooth scroll animations and hover effects
- **Professional Typography**: Inter font family for modern, clean text

### 🛠 Functionality
- **Sticky Navigation**: Header stays visible while scrolling
- **Mobile Menu**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Seamless navigation between sections
- **Contact Form**: Functional contact form with validation
- **WhatsApp Integration**: Direct WhatsApp contact button
- **Scroll-to-Top**: Easy navigation back to top
- **Interactive Elements**: Hover effects and clickable product categories

### 📱 Sections Included
1. **Header/Navigation**: Logo and menu
2. **Hero Section**: Main headline and call-to-action
3. **About Section**: Why choose your business
4. **Products Section**: Product categories with images
5. **Services Section**: Your business services
6. **Contact Section**: Contact form and business details
7. **Footer**: Additional links and information

## Setup Instructions

### 1. Image Requirements
You need to add the following images to your project:

#### Required Images:
```
logo.png - Your brand logo (45x45px recommended)
hero-product-1.jpg - Main hero image (600x400px)
hero-product-2.jpg - Secondary hero image (300x200px)
hero-product-3.jpg - Third hero image (300x200px)
resin-molds.jpg - Resin and gypsum molds category (400x350px)
craft-supplies.jpg - Craft essentials category (400x350px)
safety-gear.jpg - Safety equipment category (400x350px)
finished-products.jpg - Ready-made items category (400x350px)
```

#### Based on your provided images, use:
- **Logo**: The circular Resin Craft Supplies logo
- **Hero Images**: The beautiful resin trays and finished products
- **Product Categories**:
  - Resin Molds: Use the decorative trays and molds images
  - Craft Supplies: Use the colorful craft materials and jump rings
  - Safety Gear: Use the respirator mask image
  - Finished Products: Use the candle holders and vases

### 2. Contact Information Update
Update the following in `index.html`:

```html
<!-- Update phone number -->
<p>+234 XXX XXX XXXX</p>

<!-- Update WhatsApp number in script.js -->
const whatsappNumber = '2348000000000'; // Replace with actual number
```

### 3. Social Media Links
Update social media links in the footer and contact section:

```html
<a href="#" class="social-link"><i class="fab fa-facebook"></i></a>
<a href="#" class="social-link"><i class="fab fa-instagram"></i></a>
<a href="#" class="social-link"><i class="fab fa-whatsapp"></i></a>
<a href="#" class="social-link"><i class="fab fa-twitter"></i></a>
```

### 4. Email Configuration
To make the contact form functional, integrate with:
- **EmailJS**: For client-side email sending
- **Formspree**: Simple form handling service
- **Netlify Forms**: If hosting on Netlify
- **Your backend**: PHP, Node.js, or other server solution

## File Structure

```
resin-craft-supplies/
├── index.html          # Main HTML file
├── styles.css          # All CSS styling
├── script.js           # JavaScript functionality
├── README.md           # This file
└── images/             # Create this folder for your images
    ├── logo.png
    ├── hero-product-1.jpg
    ├── hero-product-2.jpg
    ├── hero-product-3.jpg
    ├── resin-molds.jpg
    ├── craft-supplies.jpg
    ├── safety-gear.jpg
    └── finished-products.jpg
```

## Customization

### Colors
The design uses CSS custom properties for easy color changes:

```css
:root {
    --primary-color: #e74c3c;    /* Your brand red */
    --primary-dark: #c0392b;     /* Darker red for hover */
    --secondary-color: #2c3e50;  /* Dark blue-gray */
    --text-dark: #2c3e50;        /* Dark text */
    --text-light: #7f8c8d;       /* Light text */
}
```

### Content
Easily update:
- Business name and tagline
- Product descriptions
- Service offerings
- Contact information
- About section content

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## Performance Features

- **Optimized CSS**: Efficient selectors and minimal unused code
- **Responsive Images**: Proper sizing for different screen sizes
- **Smooth Animations**: Hardware-accelerated transitions
- **Fast Loading**: Minimal external dependencies

## SEO Features

- **Meta Tags**: Proper title and description
- **Semantic HTML**: Proper heading structure
- **Alt Text**: Image descriptions for accessibility
- **Schema Markup**: Ready for structured data implementation

## Hosting Options

This static website can be hosted on:
- **Netlify** (recommended - free with forms)
- **Vercel** (free hosting)
- **GitHub Pages** (free)
- **Traditional web hosting**
- **CDN services**

## Next Steps

1. **Add Your Images**: Replace placeholder image references with your actual product photos
2. **Update Contact Info**: Add your real phone number, email, and social media
3. **Test Contact Form**: Set up email handling for the contact form
4. **SEO Optimization**: Add more specific keywords and meta descriptions
5. **Analytics**: Add Google Analytics or other tracking
6. **Domain**: Connect to your custom domain

## Support

For customizations or technical support, the code is well-commented and follows modern web development practices. Key features like the mobile menu, contact form, and animations are modular and easy to modify.

## License

This landing page template is created specifically for Resin and Craft Supplies business. Feel free to modify and use as needed for your business.

---

**Resin and Craft Supplies**  
4 Obisanya Street, Mafoluku, Oshodi, Lagos  
Your premier destination for quality resin and craft supplies in Lagos.