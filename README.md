# Nourhan Wael - Modern Feminine Portfolio Website

A beautiful, modern, and feminine portfolio website for frontend developer and UI designer **Nourhan Wael**. This multi-page website features a soft color palette, elegant design, and responsive layout.

## 🌟 Features

### **Design & Aesthetics**
- **Feminine Color Palette**: Soft pinks, dusty purples, mint greens, and warm neutrals
- **Modern Typography**: Inter font for body text, JetBrains Mono for code
- **Glassmorphism Effects**: Frosted glass cards with backdrop blur
- **Gradient Elements**: Soft gradient backgrounds, text, and borders
- **Animations**: Floating elements, glow effects, and smooth transitions
- **Responsive Design**: Fully responsive across all device sizes

### **Multi-Page Structure**
1. **Home** (`index.html`) - Landing page with hero section, featured skills, and projects
2. **About** (`pages/about.html`) - Bio, journey timeline, skills, and design philosophy
3. **Projects** (`pages/projects.html`) - Portfolio showcase with filtering by category
4. **Contact** (`pages/contact.html`) - Contact form, information, and social links

### **Interactive Elements**
- Mobile-responsive navigation with hamburger menu
- Project filtering system (Web Apps, UI/UX Design, Responsive Websites)
- FAQ accordion on contact page
- Contact form with validation
- Back-to-top button with smooth scrolling
- Active navigation highlighting
- Hover effects on cards and buttons

## 🎨 Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Soft Pink | `#F2C6D4` | Primary accent, buttons, highlights |
| Dusty Rose | `#E6C3C3` | Secondary accent, decorative elements |
| Dusty Purple | `#9D6B9E` | Primary color, navigation, text |
| Soft Mint | `#A8E6CF` | Accent color, backgrounds |
| Deep Plum | `#5D3C8B` | Dark text, accents |
| Soft Beige | `#F9F7F7` | Main background |
| Warm Ivory | `#F5F0E6` | Section backgrounds |
| Charcoal | `#2D3748` | Body text |

## 📁 Project Structure

```
project/
├── index.html              # Home page
├── pages/
│   ├── about.html         # About page
│   ├── projects.html      # Projects page
│   └── contact.html       # Contact page
├── vite.config.ts         # Build configuration
├── README.md              # This file
└── dist/                  # Built files
    ├── index.html
    └── pages/
        ├── about.html
        ├── projects.html
        └── contact.html
```

## 🚀 Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Vanilla JavaScript** - No React dependencies
- **Font Awesome** - Icons
- **Google Fonts** - Inter and JetBrains Mono fonts
- **Vite** - Build tool and development server

## 📱 Responsive Breakpoints

- **Mobile**: < 768px (single column layout, mobile menu)
- **Tablet**: 768px - 1024px (grid layouts, responsive adjustments)
- **Desktop**: > 1024px (full layouts, side-by-side sections)

## ✨ Special Features

1. **Custom Animations**:
   - Floating profile avatar
   - Glowing elements
   - Smooth hover transitions
   - Scroll-triggered animations

2. **Accessibility**:
   - Semantic HTML structure
   - Keyboard navigable
   - ARIA labels where appropriate
   - Color contrast compliance

3. **Performance**:
   - Minimal JavaScript
   - CDN-hosted libraries
   - Optimized images (SVG/icon-based)
   - Efficient CSS with Tailwind

## 🛠️ Building the Project

The project uses Vite for building. To build:

```bash
npm run build
```

Built files will be placed in the `dist/` directory.

## 📄 Pages Details

### **Home Page**
- Hero section with introduction
- Featured skills with progress bars
- Preview of featured projects
- Call-to-action buttons
- Social media links

### **About Page**
- Profile section with circular avatar
- Professional journey timeline
- Technical skills with proficiency levels
- Design & tools showcase
- Design philosophy statement

### **Projects Page**
- Filterable project grid (6 projects)
- Project cards with category tags
- GitHub and live demo links
- Empty state for filtered results
- Call-to-action for new projects

### **Contact Page**
- Contact information cards
- Working hours display
- Social media links
- Contact form with validation
- FAQ accordion section

## 🔗 Navigation Flow

All pages feature consistent navigation:
- **Logo** links to Home
- **Navigation Menu** with active page highlighting
- **Mobile Hamburger Menu** for small screens
- **Footer** with social links and copyright

## 🎯 Design Philosophy

This portfolio embodies a feminine yet professional aesthetic, balancing soft colors with clean typography and modern UI patterns. The design focuses on:

1. **Simplicity** - Clean layouts with ample white space
2. **Elegance** - Sophisticated color combinations and typography
3. **Functionality** - Intuitive navigation and user experience
4. **Personality** - Reflecting Nourhan's creative and technical skills

## 📞 Contact

The contact form is a demonstration. In a production environment, it would be connected to a backend service or email service provider.

---

*Crafted with ❤️ and code for Nourhan Wael - Frontend Developer & UI Designer*