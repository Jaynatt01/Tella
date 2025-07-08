# Resin & Craft Supplies Landing Page

A beautiful, modern landing page for resinandcraftsupplies featuring responsive design and smooth animations.

## 🖼️ Adding Your Logo

### Method 1: Replace the Logo Placeholder (Recommended)

1. **Save your logo file** in the same folder as `index.html`
   - Supported formats: JPG, PNG, SVG, WebP
   - Recommended size: 200x50px to 300x75px
   - Name your file: `logo.png` (or `logo.jpg`, `logo.svg`, etc.)

2. **Update the HTML** - Find this section in `index.html`:
   ```html
   <div class="logo">
       <div class="logo-placeholder">RC</div>
       <h1>Resin & Craft Supplies</h1>
   </div>
   ```

3. **Replace with**:
   ```html
   <div class="logo">
       <img src="logo.png" alt="Resin & Craft Supplies Logo" class="logo-image">
       <h1>Resin & Craft Supplies</h1>
   </div>
   ```

4. **Add CSS styling** - Find the `.logo-placeholder` section and add:
   ```css
   .logo-image {
       height: 50px;
       width: auto;
       object-fit: contain;
   }
   ```

### Method 2: Using Online Logo URL

If your logo is hosted online, you can use the direct URL:
```html
<img src="https://your-website.com/path/to/logo.png" alt="Resin & Craft Supplies Logo" class="logo-image">
```

### Method 3: Base64 Embedded Logo

For very small logos, you can embed them directly in the HTML. Convert your logo to base64 and use:
```html
<img src="data:image/png;base64,YOUR_BASE64_CODE_HERE" alt="Resin & Craft Supplies Logo" class="logo-image">
```

## 🎨 Customizing Colors

The landing page uses CSS custom properties (variables) for easy color customization:

```css
:root {
    --primary-color: #6B46C1;   /* Purple */
    --secondary-color: #EC4899; /* Pink */
    --accent-color: #F59E0B;    /* Amber */
    --dark-color: #1F2937;      /* Dark gray */
    --light-color: #F9FAFB;     /* Light gray */
}
```

To match your brand colors, simply update these values in the CSS.

## 📱 Testing Your Changes

1. Open `index.html` in your web browser
2. Check that the logo displays correctly
3. Test on mobile devices or use browser dev tools to check responsiveness

## 🚀 Going Live

To publish your website:

1. **GitHub Pages**: Upload to a GitHub repository and enable GitHub Pages
2. **Netlify**: Drag and drop your files to netlify.com
3. **Web Hosting**: Upload files to your hosting provider's public_html folder

## 📞 Contact Information

Update the contact section with your actual:
- Phone numbers
- Email addresses
- Social media links
- Business hours

## 🛠️ File Structure

```
your-project/
├── index.html          # Main landing page
├── logo.png           # Your logo file (add this)
└── README.md          # This file
```

## 📝 Notes

- The page is fully responsive and mobile-friendly
- All icons are from Font Awesome (loaded via CDN)
- Contact form includes basic JavaScript validation
- Smooth scrolling is implemented for navigation links