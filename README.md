# SMACIRCLE S1 E-Bike Landing Page

A responsive, modern landing page showcasing the SMACIRCLE S1 Ultra-light E-bike. This project demonstrates clean HTML5 structure, CSS3 styling, and responsive design principles.

## 🚴 Project Overview

This landing page promotes the SMACIRCLE S1, the world's smallest and lightest e-bike. The site features product information, key features, and a contact form for potential customers to get in touch.

## ✨ Features

### Website Components
- **Responsive Navigation**: Smooth navigation menu with hover effects
- **Product Features Section**: Grid layout showcasing three key features
- **About Section**: Detailed product description with pricing and product image
- **Contact Form**: Comprehensive form with multiple input types
- **Mobile Responsive**: Adapts to different screen sizes (desktop, tablet, mobile)

### Design Features
- Clean, modern interface with cornflowerblue accent color
- SVG icon integration in the header
- Smooth hover animations and transitions
- Card-based layout for features
- Form validation with required fields
- Focus states for accessibility

## 📁 File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS stylesheet
└── assets/
    └── smacircle.jpg   # Product image
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **SVG**: Scalable vector graphics for icons
- **Responsive Design**: Mobile-first approach with media queries

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.) for modifications

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/smacircle-landing-page.git
```

2. Navigate to the project directory:
```bash
cd smacircle-landing-page
```

3. Open `index.html` in your web browser:
```bash
# On macOS
open index.html

# On Windows
start index.html

# On Linux
xdg-open index.html
```

Or simply double-click the `index.html` file.

## 📱 Responsive Breakpoints

The website adapts to different screen sizes:

- **Desktop**: 993px and above (3-column feature grid)
- **Tablet**: 769px - 992px (2-column feature grid)
- **Mobile**: 768px and below (single column layout, stacked navigation)

## 🎨 Color Scheme

- **Primary Color**: Cornflowerblue (#6495ED)
- **Hover Color**: #337ab7
- **Background**: White (#fff)
- **Text**: Dark gray (#333)
- **Borders**: Light gray (#ccc, #ddd, #eee)

## 📋 Form Fields

The contact form includes:
- **Text Input**: Full name (required)
- **Email Input**: Email address (required)
- **Radio Buttons**: Model selection (N6, N1)
- **Checkboxes**: Feature preferences (Custom Color, Extra Battery, 4 Year Warranty)
- **Dropdown**: How did you hear about us
- **Textarea**: Custom message
- **Submit Button**: Form submission

## 🌟 Key CSS Features

### Grid Layout
```css
.features-grid {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 20px;
}
```

### Hover Effects
```css
.feature-card:hover {
    transform: scale(1.05);
    box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}
```

### Flexbox Navigation
```css
header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
```

## 🎯 Product Specifications

**SMACIRCLE S1 Features:**
- Weight: 17 pounds
- Range: 12 miles per charge
- Speed: 12 mph
- Charging Time: 3 hours
- Price: $1,399
- Folds in 5 quick steps
- Fits in a backpack

## 🔧 Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
/* Change primary color */
background-color: cornflowerblue; /* Replace with your color */
```

### Adding New Sections
Follow the semantic HTML structure:
```html
<section id="new-section">
    <div class="container">
        <h2>Section Title</h2>
        <!-- Content here -->
    </div>
</section>
```

### Modifying the Form
Add new form fields in `index.html` within the form element, following the existing structure.

## 📸 Image Requirements

Place product images in the `assets/` folder. Recommended specifications:
- Format: JPG or PNG
- Max width: 600px (will be responsive)
- Aspect ratio: 16:9 or 4:3 recommended

## ♿ Accessibility Features

- Semantic HTML5 elements
- Form labels properly associated with inputs
- Focus states for keyboard navigation
- Alt text for images
- Sufficient color contrast ratios

## 🌐 Browser Compatibility

Tested and compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

Created as a web development project demonstrating HTML5, CSS3, and responsive design principles.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

### How to Contribute
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Future Enhancements

- [ ] Add JavaScript for form validation
- [ ] Implement smooth scrolling for navigation
- [ ] Add product gallery/carousel
- [ ] Include customer testimonials section
- [ ] Add animations on scroll
- [ ] Integrate with backend API for form submission
- [ ] Add product comparison table
- [ ] Include video demonstration
- [ ] Add shopping cart functionality
- [ ] Implement newsletter signup
