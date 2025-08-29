# Link-in-Bio Website - Dark Mode

![Preview](https://image2url.com/images/1756478108443-4f5916b3-8e80-4c9e-83c6-3c0e0ac3d918.png)

A modern, responsive link-in-bio website built with HTML and CSS, featuring a sleek dark theme design.

## About This Project

This project is based on the Udemy course **"Learn HTML & CSS by creating a real website you can use and share"** by Andrew Tyranowski. The original tutorial teaches how to build a light-themed link-in-bio website, but this implementation has been customized with a sophisticated dark mode design.

### Course Information
- **Instructor**: Andrew Tyranowski (Software Developer and Instructor)
- **Rating**: 5.0/5 (3 ratings)
- **Students**: 1,132
- **Duration**: 40 minutes total
- **Level**: Beginner
- **Focus**: Practical, project-based learning of HTML & CSS fundamentals

## What You'll Learn From This Project

- How to structure a webpage with semantic HTML
- Modern CSS styling techniques for responsive design
- Adding social media icons, buttons, and contact links
- Layout, typography, and visual hierarchy principles
- Responsive design with CSS media queries for mobile optimization

## Dark Mode Customizations

This implementation significantly enhances the original tutorial design with the following dark mode modifications:

### 🎨 Background & Color Scheme
**Original (Light Mode):**
```css
background: linear-gradient(135deg, #e0f7fa, #fce4ec);
```

**Dark Mode Enhancement:**
```css
background: radial-gradient(1000px 600px at 20% 10%, #0b3a3f 0%, rgba(11,58,63,0) 60%),
            radial-gradient(900px 500px at 90% 80%, #3b0f1f 0%, rgba(59,15,31,0) 60%),
            #0f1517;
color: #e7ecef;
```
- **Upgrade**: Complex multi-layered radial gradients instead of simple linear gradient
- **Enhancement**: Rich dark teal and burgundy color palette with sophisticated depth

### 🃏 Card Design
**Original:**
```css
background-color: rgb(255, 255, 255);
border-radius: 16px;
box-shadow: 0 12px 30px rgba(0, 0, 0, 0.1);
```

**Dark Mode Enhancement:**
```css
background: #11181c;
border-radius: 18px;
box-shadow: 0 20px 60px rgba(0, 0, 0, 0.35), inset 0 1px 0 rgba(255,255,255,0.02);
```
- **Upgrade**: Dual-layer shadow system with inset highlight
- **Enhancement**: Deeper shadows for more dramatic depth effect

### 👤 Avatar Styling
**Original:**
```css
border: 3px solid white;
box-shadow: 0 0 10px rgba(0, 0, 0, 0.15);
```

**Dark Mode Enhancement:**
```css
border: 3px solid #1d2a2e;
box-shadow: 0 0 0 4px rgba(0, 0, 0, 0.4), 0 8px 20px rgba(0,0,0,0.35);
```
- **Upgrade**: Multi-layer shadow system with border ring effect
- **Enhancement**: More sophisticated depth and dimensionality

### 🎯 Typography Improvements
**Original:**
```css
h1 { font-size: 32px; color: #222; }
.bio { color: #555; }
.tagline { color: #888; }
```

**Dark Mode Enhancement:**
```css
h1 { font-size: 34px; color: #f3f6f8; }
.bio { color: #9fb0b7; }
.tagline { color: #7f8d93; }
```
- **Upgrade**: Larger heading size and carefully selected dark mode color palette
- **Enhancement**: Better contrast and readability in dark theme

### 🔗 Interactive Link Buttons
**Original:**
```css
background-color: #e0f7fa;
color: #00796b;
font-weight: 600;
transition: all 0.2s ease;
```

**Dark Mode Enhancement:**
```css
background-color: #0b3f43;
color: #d8f3f0;
font-weight: 700;
letter-spacing: 0.2px;
border: 1px solid rgba(0,0,0,0.4);
box-shadow: inset 0 1px 0 rgba(255,255,255,0.04), 0 6px 18px rgba(0,0,0,0.35);
transition: transform 0.15s ease, background-color 0.15s ease, box-shadow 0.15s ease;
```
- **Upgrade**: Advanced shadow system with inset highlights and borders
- **Enhancement**: Improved typography with letter spacing and heavier font weight
- **Feature**: More sophisticated hover animations with transform effects

### ✨ Advanced Hover Effects
**Original:**
```css
.links a:hover {
  background-color: #b2ebf2;
  color: #004d40;
}
```

**Dark Mode Enhancement:**
```css
.links a:hover {
  background-color: #0e5a60;
  color: #ffffff;
  transform: translateY(-1px);
  box-shadow: inset 0 1px 0 rgba(255,255,255,0.05), 0 10px 24px rgba(0,0,0,0.45);
}
```
- **New Feature**: Subtle lift animation with `translateY(-1px)`
- **Enhancement**: Dynamic shadow changes on hover for depth perception

### 🎨 Icon Styling & Updates
**Original:**
```css
.links a i {
  margin-right: 8px;
}
```

**Dark Mode Enhancement:**
```css
.links a i {
  margin-right: 10px;
  color: #b9f2ea;
}
```
- **Enhancement**: Dedicated icon color for better visual hierarchy
- **Improvement**: Increased spacing for better visual balance
- **Update**: Upgraded Font Awesome from v6.4.0 to v7.0.0 for latest icons and features

### ♿ Accessibility Features
**New Addition:**
```css
.links a:focus, .links a:focus-visible {
  outline: 2px solid #2dd4bf;
  outline-offset: 2px;
}
.links a:active {
  transform: translateY(0);
  background-color: #0c4a4e;
}
```
- **New Feature**: Enhanced focus states for keyboard navigation
- **Enhancement**: Active state feedback for better user interaction

## Key Improvements Over Tutorial

1. **Visual Sophistication**: Transformed simple gradients into complex multi-layered backgrounds
2. **Advanced Shadows**: Implemented multi-layer shadow systems for realistic depth
3. **Enhanced Interactivity**: Added smooth animations and hover effects
4. **Better Typography**: Improved font weights, sizing, and letter spacing
5. **Accessibility**: Added proper focus and active states
6. **Color Theory**: Applied professional dark mode color palette with proper contrast ratios
7. **Updated Dependencies**: Upgraded Font Awesome from v6.4.0 to v7.0.0 for latest features

## Technologies Used

- **HTML5**: Semantic structure and accessibility
- **CSS3**: Advanced styling with modern features
  - CSS Grid and Flexbox for layout
  - CSS Custom Properties (variables)
  - Advanced gradients and shadows
  - Smooth transitions and animations
  - Responsive design with media queries

## Getting Started

### 🌟 Give it a Star!
If you find this project helpful or inspiring, please consider giving it a ⭐ on GitHub! It helps others discover this enhanced version of the tutorial.

### 📥 Clone & Run
```bash
# Clone the repository
git clone https://github.com/tusharbasak97/link-in-bio-website-dark.git

# Navigate to the project directory
cd link-in-bio-website-dark

# Option 1: Open directly in browser
# Simply double-click index.html or drag it to your browser

# Option 2: Serve locally (recommended)
python3 -m http.server 8000
# Then visit http://localhost:8000 in your browser
```

## Course Completion

This project demonstrates mastery of the core concepts taught in the Udemy course while showcasing advanced CSS techniques and design principles that go beyond the tutorial scope.

---

*Based on the Udemy course "Learn HTML & CSS by creating a real website you can use and share" by Andrew Tyranowski, enhanced with advanced dark mode styling and modern web design principles.*
