# NAA Conversation Club Website

A modern, responsive website for the National Aviation Academy Conversation Club (NAACC).

## Features

- **Bilingual Content**: English and Azerbaijani language support
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Built with Tailwind CSS**: Utility-first CSS framework for rapid development
- **Sections Included**:
  - Welcome/Hero section
  - Advantages of joining
  - Benefits and gains
  - Activities showcase
  - Meeting schedule
  - Meeting highlights
  - Registration and social media links
  - Contact information

## Getting Started

Simply open `index.html` in your web browser to view the website. The site uses Tailwind CSS via CDN, so no build process is required.

## Customization

### Adding a Real QR Code
Replace the QR code placeholder in the registration section with an actual QR code image:
1. Generate a QR code for your registration link
2. Replace the `.qr-placeholder` div content with an `<img>` tag pointing to your QR code image

### Adding Instagram Link
Update the "Follow on Instagram" button with your actual Instagram URL:
```html
<a href="YOUR_INSTAGRAM_URL" class="btn btn-secondary">Follow on Instagram</a>
```

### Adding Registration Link
Update the registration buttons with your actual registration URL:
```html
<a href="YOUR_REGISTRATION_URL" class="btn btn-primary">Registration Now</a>
```

### Adding Gallery Images
Replace the placeholder gallery items with actual images:
```html
<div class="gallery-item">
    <img src="path/to/image.jpg" alt="Meeting highlight">
</div>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2024 National Aviation Academy Conversation Club. All rights reserved.

