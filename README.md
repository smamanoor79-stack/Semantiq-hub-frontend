# SemantiQHub.ai Website

A modern, responsive website for SemantiQHub - an AI services provider, built with Bootstrap 5 and custom CSS.

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
semantichub-website/
├── index.html          # Main HTML file with Bootstrap integration
├── style.css           # Custom CSS (loads after Bootstrap)
├── assets/             # Images and logos
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
└── README.md
```

## 🔧 Installation & Setup

### Option 1: Direct Use
1. Clone or download the repository
2. Open `index.html` in a web browser
3. All Bootstrap and Font Awesome resources load via CDN

### Option 2: Local Development
```bash
# Clone the repository
git clone https://github.com/yourusername/semantichub-website.git

# Navigate to the project directory
cd semantichub-website

# Open in your preferred code editor
code .

# Open index.html with Live Server or similar tool
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

## 🚀 Deployment to GitHub

### Step 1: Initialize Git Repository
```bash
git init
git add .
git commit -m "Initial commit - Bootstrap integrated website"
```

### Step 2: Create GitHub Repository
1. Go to GitHub.com
2. Click "New Repository"
3. Name it: `semantichub-website`
4. Don't initialize with README (we already have one)
5. Click "Create Repository"

### Step 3: Push to GitHub
```bash
git remote add origin https://github.com/yourusername/semantichub-website.git
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages (Optional)
1. Go to repository Settings
2. Navigate to "Pages" section
3. Select source: "Deploy from branch"
4. Select branch: `main` and folder: `/ (root)`
5. Click Save
6. Your site will be live at: `https://yourusername.github.io/semantichub-website/`

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

Copyright © 2025 Semantiqhub - All Rights Reserved.

## 🤝 Contributing

If you'd like to contribute to this project:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

For questions or support, please contact the SemantiQHub team.

---

