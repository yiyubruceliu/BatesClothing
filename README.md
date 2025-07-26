# Bates Clothing LTD - Single Page Website

A modern, responsive single-page website for Bates Clothing LTD, trading as Bates Workwear. This website features a sleek design with smooth scrolling navigation and comprehensive information about the company's products and services.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Scrolling**: Single-page navigation with smooth scroll effects
- **Modern UI**: Clean design with black, grey, and red color scheme
- **Interactive Elements**: Hover effects, animations, and form validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional quote request form with validation
- **Supplier Showcase**: Display of trusted supplier partnerships

## File Structure

```
BatesClothing/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # This file
├── img/
│   ├── logo.png        # Company logo
│   ├── logo2.png       # Company logo with slogan
│   └── suppliers/      # Supplier logos
│       ├── TriCorp-Logo_zwart.png
│       ├── payperwear logo.png
│       ├── ralawise logo.png
│       └── sticker logo.svg
└── clientDoc/          # Client documentation
```

## Sections

1. **Home**: Hero section with company introduction and call-to-action buttons
2. **About Us**: Company information and key statistics
3. **Products & Services**: Detailed service offerings including:
   - Workwear supply
   - Customized uniforms
   - Safety gear selection
   - In-house embroidery
   - Heat press services
   - Timely delivery
4. **Suppliers**: Showcase of trusted supplier partnerships
5. **Contact**: Contact information and quote request form

## Color Scheme

- **Primary Color**: Black (#000000)
- **Secondary Color**: Grey (#666666)
- **Accent Color**: Red (#dc2626)
- **Light Grey**: #f5f5f5
- **Dark Grey**: #333333

## Customization

### Changing Colors
Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #000000;
    --secondary-color: #666666;
    --accent-color: #dc2626;
    --light-grey: #f5f5f5;
    --dark-grey: #333333;
    --white: #ffffff;
    --border-radius: 0px;
}
```

### Updating Content
1. **Company Information**: Edit the content in `index.html`
2. **Contact Details**: Update phone numbers, emails, and addresses
3. **Supplier Information**: Modify supplier links and descriptions
4. **Services**: Add or modify service offerings

### Adding New Sections
1. Add the HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Update navigation menu if needed

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized images
- Smooth animations
- Lazy loading effects
- Responsive design
- Fast loading times

## Form Handling

The contact form includes:
- Input validation
- Email format checking
- Required field validation
- Success/error messaging

**Note**: The form currently shows a success message. For production use, you'll need to integrate with a backend service or email service like:
- Formspree
- Netlify Forms
- EmailJS
- Custom backend API

## Deployment

To deploy this website:

1. **Static Hosting** (Recommended):
   - Netlify
   - Vercel
   - GitHub Pages
   - AWS S3

2. **Traditional Hosting**:
   - Upload all files to your web server
   - Ensure proper file permissions
   - Configure domain settings

## SEO Optimization

The website includes:
- Semantic HTML structure
- Meta tags (add more as needed)
- Alt text for images
- Proper heading hierarchy
- Fast loading times

## Maintenance

Regular maintenance tasks:
- Update contact information
- Refresh supplier information
- Monitor form submissions
- Check for broken links
- Update content as needed

## Support

For technical support or customization requests, contact the development team.

## License

This website is created for Bates Clothing LTD. All rights reserved.

---

**Bates Clothing LTD**  
Hidden River Lodge, Garrison road, Mooretown Great, Ballymitty, Co. Wexford, Y35RW71  
Phone: 085 839 6069 | Email: sales@batesworkwear.ie  
Website: www.batesworkwear.ie 