# Personal CV Website

A clean and professional CV website boilerplate created for showcasing your professional profile, experience, and achievements.

## Features

✨ **Three Main Pages:**
- **Home/Landing Page** - A welcoming introduction with key highlights
- **CV Page** - Comprehensive curriculum vitae with sections for experience, education, skills, and certifications
- **About Me Page** - Personal story, interests, values, and fun facts

🎨 **Design Features:**
- Responsive design that works on desktop, tablet, and mobile devices
- Modern, clean aesthetic with professional color scheme
- Smooth animations and transitions
- Easy to customize colors and content
- Print-friendly CV page (optimized for PDF export)

⚡ **Technical Features:**
- Pure HTML, CSS, and JavaScript (no external dependencies)
- Semantic HTML structure
- CSS Grid and Flexbox layouts
- Smooth scrolling navigation
- Active navigation link highlighting
- Intersection Observer for scroll animations

## Project Structure

```
me.com/
├── index.html          # Landing page
├── cv.html             # CV/Resume page
├── about.html          # About me page
├── css/
│   └── style.css       # All styling
├── js/
│   └── script.js       # JavaScript functionality
└── README.md           # This file
```

## Getting Started

### 1. **Customize Basic Information**
   - Replace "Your Name" with your actual name throughout all files
   - Update your professional title
   - Add your contact information (email, phone, location)

### 2. **Fill in the Landing Page (index.html)**
   - Update the hero section with your introduction
   - Modify the three key highlights with your strengths
   - Add your social media links in the footer

### 3. **Complete Your CV (cv.html)**
   - Add your professional summary
   - Fill in your work experience (company, job title, dates, responsibilities)
   - List your education details
   - Add your skills and languages
   - Include certifications and awards

### 4. **Write Your About Me Page (about.html)**
   - Share your personal story and career journey
   - Add your interests and hobbies
   - Describe your professional values and philosophy
   - Include fun facts about yourself

### 5. **Customize Colors (css/style.css)**
   - Update the CSS variables at the top of the file:
   ```css
   :root {
       --primary-color: #2c3e50;      /* Main color */
       --secondary-color: #3498db;    /* Accent color */
       --accent-color: #e74c3c;       /* Highlight color */
       /* ... other variables ... */
   }
   ```

### 6. **Add Your Photo (about.html)**
   - Replace the placeholder image with your own photo
   - Save your image in an `images/` folder (create if needed)
   - Update the image source in `about.html`

## Customization Tips

### Changing Colors
1. Open `css/style.css`
2. Modify the CSS variables in the `:root` selector
3. Common colors to try:
   - Primary: Navy `#2c3e50`, Dark Blue `#34495e`, Dark Green `#27ae60`
   - Secondary: Sky Blue `#3498db`, Teal `#1abc9c`, Orange `#e67e22`

### Adding More Sections
- Copy existing sections and modify the content
- Use the existing CSS classes for consistency
- The responsive grid system automatically adapts to new content

### Adding a Contact Form
1. Add a new `contact.html` page
2. Create a form section with fields
3. Use the existing form validation in `js/script.js`
4. Consider using a service like Formspree or EmailJS for form submissions

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- No external dependencies - fast loading
- Optimized CSS with no unused styles
- Minimal JavaScript for smooth interactions
- Mobile-first responsive design

## Deployment

This website can be easily deployed to:

- **GitHub Pages** - Free hosting directly from your repository
- **Vercel** - Zero-config deployment
- **Netlify** - Free tier with build optimization
- **Any web host** - Just upload the files via FTP

## Printing/PDF Export

The CV page is optimized for printing:
1. Open `cv.html` in your browser
2. Use Ctrl+P (or Cmd+P on Mac) to print
3. Select "Save as PDF" as the destination
4. The print styles automatically hide unnecessary elements

## Future Enhancements

Consider adding:
- [ ] Dark mode toggle
- [ ] Multi-language support
- [ ] Blog section
- [ ] Portfolio/Projects showcase
- [ ] Testimonials section
- [ ] Contact form with email integration
- [ ] Dynamic content loading
- [ ] SEO optimization

## License

Free to use and modify for personal use.

## Questions?

This boilerplate is designed to be self-explanatory. Each HTML file has comments indicating where to add your content. Start with the placeholder text and replace it with your own information.

Happy customizing! 🎉