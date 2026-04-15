# SemantiQHub.Website

From Design to Reality :
This project was developed by translating a high-fidelity Figma design into clean, responsive HTML/CSS using Bootstrap 5
A modern, responsive website for SemantiQHub - an AI services provider, built with Bootstrap 5 and custom CSS.


📸 A visual representation of the Semantiqhub Landing Page.


![desktop-semantiqhub](https://github.com/user-attachments/assets/4a8703b7-1908-4098-8059-2c7f4f933b9d)


## 🚀 Features

- **Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Bootstrap 5 Integration** - Utilizes Bootstrap's grid system and components
- **Custom Styling** - Preserves original Figma design with custom CSS
- **Interactive Navigation** - Collapsible mobile menu with dropdown support
- **Modern UI Components** - Cards, buttons, and sections with hover effects
- **Cross-browser Compatible** - Works on all modern browsers

## 📋 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with Flexbox and Grid
- **Bootstrap 5.3.2** - Responsive grid system and components
- **Font Awesome 6.5.0** - Icon library

## 🎨 Bootstrap Integration

### What's Included:

1. **Grid System**
   - Responsive layouts using Bootstrap's 12-column grid
   - Container-fluid for full-width sections with custom padding
   - Row and column classes for proper alignment

2. **Components**
   - Navbar with collapse functionality for mobile
   - Dropdown menus
   - Cards for feature and blog sections
   - Buttons with custom styling
   - Navigation components in footer

3. **Utilities**
   - Spacing utilities (mb-3, py-5, gap-4, etc.)
   - Display utilities (d-flex, d-block, etc.)
   - Text utilities (text-center, text-lg-end, etc.)
   - Alignment utilities (align-items-center, justify-content-between, etc.)

### Custom Overrides:

The custom CSS (`style.css`) overrides Bootstrap defaults to maintain the original Figma design:
- Custom color scheme (#0A6190 primary blue, #E7FAFB light blue)
- Specific spacing and padding values
- Custom font sizes and weights
- Unique hover effects and transitions

## 📁 File Structure

```
semantiqhub-website/
├── assets/           # Images and logos
│   ├── semantiqhublogo.png
│   ├── ai-illustrations.png
│   ├── ourmethod.png
│   ├── searchicon.png
│   ├── governicon.png
│   ├── talkicon.png
│   ├── humans1.png - humans4.png
│   ├── blogs1.png - blogs3.png
│   ├── googlecloudpartner.png
│   ├── azurecloudpartner.png
│   ├── aws.png
│   ├── twitter.png
│   ├── instagram.png
│   └── github.png
├── index.html          # Main HTML file with Bootstrap integration
├── style.css           # Custom CSS (loads after Bootstrap)
└── README.md

```

## 🌐 CDN Links Used

- **Bootstrap CSS**: `https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css`
- **Bootstrap JS**: `https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js`
- **Font Awesome**: `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css`

## 📱 Responsive Breakpoints

The website is fully responsive with the following breakpoints:

- **Extra Large Desktop**: 1920px and above
- **Large Desktop**: 1440px - 1919px (default)
- **Medium Desktop**: 1200px - 1439px
- **Small Desktop**: 1024px - 1199px
- **Tablet Landscape**: 768px - 1023px
- **Tablet Portrait**: 481px - 767px
- **Mobile**: 360px - 480px
- **Small Mobile**: Below 360px

## 🎯 Sections

1. **Navigation Bar** - Sticky header with dropdown menus and CTA button
2. **Hero Section** - Main banner with heading, description, and partner logos
3. **Our Method** - Three-column grid explaining the methodology
4. **Made For Humans** - Feature cards showcasing AI capabilities
5. **Problems We Solve** - Two-column layout with problem categories
6. **Blog Section** - Featured and side blog posts
7. **Footer** - Links, social media icons, and copyright info

## 🎨 Color Scheme

- **Primary Blue**: #0A6190
- **Light Blue Background**: #E7FAFB
- **Dark Text**: #1A1B1D
- **Gray Text**: #555, #666
- **Footer Background**: #000a12
- **White**: #FFFFFF

## 🔄 Future Enhancements

- [ ] Add smooth scroll behavior
- [ ] Implement form validation for demo requests
- [ ] Add blog post filtering functionality
- [ ] Integrate actual dropdown menu content
- [ ] Add loading animations
- [ ] Implement dark mode toggle
- [ ] Add accessibility improvements (ARIA labels)
- [ ] Optimize images for web

## 📝 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 👨‍💻 Development Notes

- Custom CSS is loaded **after** Bootstrap to ensure proper overrides
- Container-fluid is used with custom padding for precise control
- Bootstrap's responsive utilities are used alongside custom media queries
- Mobile navigation uses Bootstrap's collapse component
- All images should be placed in the `assets/` folder

## 📄 License

This project is for portfolio purposes. The code is open for educational use, but the design rights belong to the original creator.

## 🤝 Contributing

"This is a personal portfolio project. 
While I am not currently looking for contributions, feel free to 
fork the repository to explore the code or use it as a reference for your own learning."


