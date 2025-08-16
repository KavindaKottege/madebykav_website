# Cricket Counter Support Website

A professional, mobile-responsive website providing comprehensive support information and privacy policy for the Cricket Counter iOS/watchOS app.

## 🌟 Features

- **Modern Design**: Clean, dark theme matching the Cricket Counter app aesthetic
- **Mobile-Responsive**: Optimized for all screen sizes from mobile to desktop
- **Comprehensive Support**: Detailed FAQ, troubleshooting, and getting started guides
- **Privacy Compliant**: Full privacy policy meeting App Store and GDPR requirements
- **Fast Performance**: Optimized CSS and minimal dependencies
- **Accessible**: WCAG compliant with proper semantic markup

## 📁 File Structure

```
cricket-counter-website/
├── index.html          # Main support page with FAQ and troubleshooting
├── privacy.html        # Comprehensive privacy policy
├── styles.css          # Responsive stylesheet with Cricket Counter branding
├── assets/             # Directory for images and other assets
└── README.md           # This file
```

## 🚀 Deployment Options

### Option 1: GitHub Pages (Recommended)
1. Create a new GitHub repository
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch" > "main" > "/ (root)"
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Netlify
1. Create an account at [Netlify](https://netlify.com)
2. Drag and drop the `cricket-counter-website` folder to Netlify
3. Your site will be deployed instantly with a custom URL
4. Optional: Configure a custom domain

### Option 3: Vercel
1. Create an account at [Vercel](https://vercel.com)
2. Import the GitHub repository or upload files directly
3. Deploy with zero configuration
4. Get automatic HTTPS and global CDN

### Option 4: Traditional Web Hosting
1. Upload all files to your web hosting provider via FTP/SFTP
2. Ensure `index.html` is in the root directory
3. Configure your domain to point to the hosting directory

## 🛠️ Customization

### Colors and Branding
The CSS uses CSS custom properties (variables) for easy theming:

```css
:root {
  --primary-bg: #000000;      /* Main background */
  --secondary-bg: #1a1a1a;    /* Card backgrounds */
  --accent-color: #32D74B;    /* Cricket Counter green */
  --text-primary: #ffffff;    /* Main text */
  --text-secondary: rgba(255, 255, 255, 0.7); /* Secondary text */
}
```

### Content Updates
- **Support Information**: Edit `index.html` to update FAQ, troubleshooting steps
- **Privacy Policy**: Modify `privacy.html` as needed for legal compliance
- **Contact Information**: Update email addresses throughout both files
- **App Store Links**: Replace placeholder links with actual App Store URLs

### Adding Images
1. Add images to the `assets/` directory
2. Reference them in HTML: `<img src="assets/your-image.png" alt="Description">`
3. Optimize images for web (WebP format recommended)

## 📱 Testing

### Local Testing
1. Open `index.html` in a web browser
2. Test all navigation and FAQ interactions
3. Verify responsive design by resizing browser window
4. Check privacy policy navigation and content

### Browser Compatibility
- ✅ Safari (iOS/macOS)
- ✅ Chrome (all platforms)
- ✅ Firefox (all platforms)
- ✅ Edge (Windows/macOS)

### Mobile Testing
- Test on actual iOS devices (iPhone/iPad)
- Use browser developer tools to simulate different screen sizes
- Verify touch targets are appropriately sized
- Check that all content is readable without zooming

## 🔧 Technical Details

### Performance
- **Pure HTML/CSS/JavaScript**: No frameworks or dependencies
- **Optimized Assets**: Minimal CSS and JavaScript for fast loading
- **Responsive Images**: Uses appropriate sizing for different screen densities
- **Progressive Enhancement**: Works with JavaScript disabled

### SEO Optimization
- Semantic HTML5 markup
- Meta descriptions and keywords
- Proper heading hierarchy (h1-h4)
- Alt text for images
- Structured navigation

### Accessibility Features
- Proper ARIA labels and roles
- Keyboard navigation support
- High contrast text and colors
- Screen reader compatible
- Focus indicators for interactive elements

## 📋 Pre-Launch Checklist

### Content Review
- [ ] All placeholder text replaced with actual content
- [ ] Email addresses updated to real support addresses
- [ ] App Store links point to actual app listing
- [ ] Legal information reviewed by appropriate team
- [ ] FAQ addresses real user questions

### Technical Testing
- [ ] All links work correctly
- [ ] FAQ accordion functionality works
- [ ] Smooth scrolling navigation works
- [ ] Mobile responsive design verified
- [ ] Cross-browser compatibility tested
- [ ] Page load speed optimized

### SEO and Analytics
- [ ] Meta descriptions and titles optimized
- [ ] Google Analytics or similar tracking added (if desired)
- [ ] Sitemap created and submitted to search engines
- [ ] Social media preview images configured

## 🔗 App Store Connect Integration

When submitting Cricket Counter to the App Store:

1. **Privacy Policy URL**: Use the URL of your deployed `privacy.html` page
2. **Support URL**: Use the URL of your deployed `index.html` page
3. **Marketing URL**: Can also use the main support page URL

Example URLs (replace with your actual domain):
- Privacy Policy: `https://cricketcounter.com/privacy.html`
- Support: `https://cricketcounter.com/`

## 🚨 Important Notes

### Privacy Policy Compliance
- Review the privacy policy with legal counsel before publishing
- Update the privacy policy when app functionality changes
- Ensure compliance with GDPR, CCPA, and other applicable regulations
- Keep the "Last Updated" date current

### Regular Maintenance
- Update FAQ based on user questions
- Keep troubleshooting steps current with app versions
- Monitor support email for common issues to add to FAQ
- Review and update privacy policy annually or when app changes

## 📞 Support

If you need help with the website:
1. Check this README for common solutions
2. Verify all files are uploaded correctly
3. Test in different browsers and devices
4. Contact web development support if needed

## 📄 License

This website template is created specifically for Cricket Counter and should be customized appropriately for your use case. The design and structure can be adapted for similar app support websites.

---

**Last Updated**: January 2025  
**Compatible With**: Cricket Counter v1.0+  
**Supported Browsers**: Safari, Chrome, Firefox, Edge (latest versions)