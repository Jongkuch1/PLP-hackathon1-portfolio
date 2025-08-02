# Jongkuch Isaac Chol Anyar - Personal Portfolio

A modern, responsive personal portfolio website showcasing the skills, projects, and professional background of Jongkuch Isaac Chol Anyar, a Software Engineering student at African Leadership University.

## 🌟 Features

- **HTML, CSS & JavaScript**: Lightweight with minimal JavaScript for popup functionality
- **Animated Background**: Moving background photo with smooth pan and zoom effects
- **Professional Color Scheme**: Navy blue accents with sky blue sections for modern appeal
- **Responsive Design**: Mobile-first approach that works on all devices
- **CSS-Only Navigation**: Hamburger menu using pure CSS
- **Animated Elements**: CSS keyframe animations and transitions
- **Contact Form**: HTML form ready for backend integration
- **Downloadable CV**: Direct link to download resume/CV
- **Interactive Popup**: Personal information displayed in modal popup
- **Profile Integration**: Personal information, skills, and projects

## 📋 Sections

1. **Hero**: Animated background with introduction and "Learn More" popup trigger
2. **Programming Languages**: Visual skill bars (JavaScript 90%, Python 65%, HTML/CSS 95%, React 88%)
3. **Educational Background**: African Leadership University degree and certifications
4. **Interests**: Full-stack development interests with icons
5. **Projects**: Featured projects including School Website, e-Governance App, and E-Commerce Store
6. **Contact**: Contact form and personal information (Kigali, Rwanda)
7. **About Popup**: Personal story and professional summary with profile photo (triggered by "Learn More")

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Basic text editor (VS Code, Sublime Text, etc.)

### Installation

1. Clone or download the repository
2. Open `index.html` in your web browser
3. Customize the content with your personal information

## 📁 Project Structure

```
My Portfolio/
│
├── index.html          # Main HTML file with personal content
├── style.css           # CSS styles with animations and sky blue theme
├── background.jpg      # Animated background image for hero section
├── Profile. pic.jpg    # Profile photo for about section
├── CV.pdf             # Downloadable resume/CV
└── README.md          # Project documentation
```

## 🎨 Customization Guide

### 1. Personal Information
Replace placeholder content in `index.html`:

**Hero Section:**
```html
<h1>Hello, I'm <span class="highlight">Your Name</span></h1>
<p>Your Title/Role</p>
```

**About Popup:**
- Update the popup content with your story
- Replace profile placeholder with your photo
- Customize the "Who I Am", "What I Do", "My Mission", and "My Values" sections

**Programming Languages:**
- Modify skill percentages in the `style` attributes
- Add/remove languages as needed

**Education:**
- Update university name, degree, and years
- Modify certifications list

**Projects:**
- Replace project titles, descriptions, and links
- Update technology tags

**Contact:**
- Update email, phone, location, and LinkedIn
- Configure form action for backend processing

### 2. Current Color Scheme

**Professional Navy & Sky Blue Theme:**
```css
/* Primary navy blue */
.highlight { color: #1E3A8A; }

/* Sky blue sections */
.bg-light { background-color: #87CEEB; }

/* Animated hero background */
.hero {
    background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), url('background.jpg');
    animation: backgroundMove 20s ease-in-out infinite;
}
```

**Fonts:**
```css
body {
    font-family: 'Your-Font', sans-serif;
}
```

### 3. Adding Your Photo
1. Add your profile photo to the project folder
2. Replace the placeholder:
```html
<div class="about-image">
    <img src="your-photo.jpg" alt="Your Name" class="profile-image">
</div>
```

3. Add CSS for the image:
```css
.profile-image {
    width: 250px;
    height: 250px;
    border-radius: 50%;
    object-fit: cover;
}
```

### 4. Project Images
Replace project placeholders with actual screenshots:
```html
<div class="project-image">
    <img src="project1-screenshot.jpg" alt="Project Name">
</div>
```

## 🌐 Deployment Options

### GitHub Pages
1. Create a GitHub repository
2. Upload your files
3. Go to Settings > Pages
4. Select source branch (main/master)
5. Your site: `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to Netlify
2. Or connect your GitHub repository
3. Automatic deployments on every push

### Vercel
1. Import your GitHub repository
2. Deploy with zero configuration
3. Custom domain support available

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox, Grid, and animations
- **JavaScript**: Minimal JavaScript for popup modal functionality
- **CSS Variables**: For easy theme customization
- **CSS Animations**: Smooth transitions and keyframe animations
- **Responsive Design**: Mobile-first approach with media queries

## ✨ CSS Features

### Animated Background
- Moving background photo with pan and zoom effects
- 20-second loop with smooth transitions
- Dark overlay for text readability

### Professional Color Palette
- Navy blue (#1E3A8A) for headers and accents
- Sky blue (#87CEEB) for section backgrounds
- Off-white (#FAFAFA) for main background
- Dark gray (#111827) for readable text

### Interactive Elements
- Modal popup for personal information
- JavaScript-powered show/hide functionality
- Smooth popup animations and transitions

### Pure CSS Navigation
- Hamburger menu without JavaScript
- CSS checkbox hack for mobile toggle
- Smooth transitions and animations

### CSS Animations
- Fade-in animations on page load
- Hover effects on cards and buttons
- Animated skill bars with CSS keyframes
- Background motion animation

### Responsive Grid Layouts
- CSS Grid for complex layouts
- Flexbox for component alignment
- Mobile-first responsive design

## 🎯 Performance

- **Lightweight**: Minimal JavaScript, no external dependencies
- **Fast Loading**: Optimized HTML/CSS/JS loads quickly
- **SEO Friendly**: Semantic HTML structure
- **Accessible**: Proper heading hierarchy and alt texts
- **Interactive**: Smooth popup modal for enhanced user experience

## 📝 Form Integration

The contact form is ready for backend integration. Popular options:

**Formspree:**
```html
<form action="https://formspree.io/f/your-form-id" method="POST">
```

**Netlify Forms:**
```html
<form name="contact" method="POST" data-netlify="true">
```

**EmailJS:**
Add EmailJS script and configure form submission

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

If you have questions or need help customizing your portfolio:
- Open an issue on GitHub
- Check the documentation
- Review the code comments

## 👨‍💻 About the Developer

**Jongkuch Isaac Chol Anyar**
- Software Engineering Student at African Leadership University
- Location: Kigali, Rwanda
- Email: j.anyar@alustudent.com
- Phone: +250 794411361
- GitHub: [jongkuch1](https://github.com/jongkuch1)
- LinkedIn: [jongkuch-anyar](https://www.linkedin.com/in/jongkuch-anyar-36535131b/)

## 🎯 Portfolio Highlights

- **School Website**: Built for Promised Land Secondary School using HTML, CSS, JavaScript
- **e-Governance App**: Developing web application for South Sudanese citizens
- **E-Commerce Store**: Online shop with cart functionality and admin dashboard
- **Skills**: JavaScript (90%), HTML/CSS (95%), React (88%), Python (65%)

## 🙏 Acknowledgments

- African Leadership University for educational support
- CSS Grid and Flexbox layouts
- Modern CSS animation techniques
- Responsive design best practices
- Accessibility guidelines

---

⭐ **Star this repository if you found it helpful!**

Happy coding! 🚀