# 3-column-responsive-layout-using-flexbox-or-grid
Enhanced Responsive 3-Column Layout

A modern, responsive 3-column layout implementation using both Flexbox and CSS Grid with animations and enhanced styling.

🚀 Features

· Dual Layout Implementation: Built with both Flexbox and CSS Grid
· Fully Responsive: Adapts to all screen sizes
· Modern Animations: Smooth hover effects and transitions
· Enhanced Typography: Google Fonts integration
· Professional Design: Modern color scheme and visual elements
· Cross-browser Compatible: Works on all modern browsers

🛠️ Technologies Used

· HTML5
· CSS3 (Flexbox & Grid)
· Google Fonts (Poppins & Montserrat)
· CSS Animations & Transitions
· CSS Variables for consistent theming

🎨 Design Features

Color Scheme

· Primary Color: #0b9ebc
· Secondary Color: #ff6b6b
· Accent Color: #4ecdc4
· Dark Color: #222
· Light Background: Gradient background

Typography

· Headings: Montserrat (700 weight)
· Body Text: Poppins (300, 400, 600 weights)
· Code Elements: Courier New

Animations

· Fade-in animations for content loading
· Hover effects with transform and shadow changes
· Gradient accent animations
· Smooth transitions throughout

📱 Responsive Breakpoints

· Desktop: 992px and above
· Tablet: 768px - 991px
· Mobile: 480px - 767px
· Small Mobile: Below 480px

🏗️ Project Structure

```
index.html
├── Header Section
│   ├── Animated background
│   └── Title with fade effects
├── Flexbox Layout Section
│   ├── 3 responsive columns
│   └── Flexbox properties
├── CSS Grid Layout Section
│   ├── 3 responsive columns
│   └── Grid properties
└── Footer Section
```

💻 Code Highlights

CSS Variables

```css
:root {
  --primary-color: #0b9ebc;
  --secondary-color: #ff6b6b;
  --accent-color: #4ecdc4;
  --shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
  --transition: all 0.3s ease;
}
```

Flexbox Implementation

```css
.flex-container {
  display: flex;
  flex-wrap: wrap;
  gap: 25px;
  justify-content: center;
}
```

CSS Grid Implementation

```css
.grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 25px;
}
```

Key Animations

```css
@keyframes fadeInDown {
  from { opacity: 0; transform: translateY(-20px); }
  to { opacity: 1; transform: translateY(0); }
}

.column:hover {
  transform: translateY(-10px);
  box-shadow: 0 12px 20px rgba(0, 0, 0, 0.15);
}
```

🎯 Browser Compatibility

· Chrome 50+
· Firefox 45+
· Safari 10+
· Edge 12+
· Opera 40+

📄 License

This project is open source and available under the MIT License.

👨‍💻 Author

Divyansh Raj

· B.Tech CSE
· CGC University, Mohali
· © 2025

🔧 Installation & Usage

1. Clone or download the project files
2. Open index.html in your web browser
3. No additional dependencies required

🌟 Key Learning Outcomes

· Modern CSS layout techniques
· Responsive design principles
· CSS animations and transitions
· Flexbox vs Grid comparison
· CSS variables for theming
· Cross-browser compatibility

📞 Support

For any queries or suggestions, please contact the author.
