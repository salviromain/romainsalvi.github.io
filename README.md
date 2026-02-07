# Personal Portfolio Website

A modern, responsive portfolio website template designed for Computer Science and Data Science students to showcase their projects and skills.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Clean and professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, navigation effects, and scroll animations
- **Project Showcase**: Dedicated section to display your projects with descriptions and links
- **Skills Section**: Organized display of your technical skills and technologies
- **Contact Form**: Functional contact form for visitors to reach out
- **SEO Friendly**: Semantic HTML and meta tags for better search engine visibility

## 📁 File Structure

```
romainsalvi.github.io/
├── index.html          # Main HTML file with all sections
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript for interactions and animations
└── README.md          # This file
```

## 🚀 Quick Start

1. **Clone or download** this repository
2. **Open `index.html`** in your browser to view the website
3. **Customize** the content with your personal information

## ✏️ Customization Guide

### Personal Information

Open `index.html` and update the following:

1. **Title and Meta Tags** (lines 5-6):
   ```html
   <title>Your Name | CS & Data Science Student</title>
   ```

2. **Hero Section** (around line 29):
   - Replace "Your Name" with your actual name
   - Update the subtitle and description

3. **About Section** (around line 49):
   - Write your personal bio
   - Update the stats (years coding, number of projects, etc.)

4. **Skills Section** (around line 77):
   - Add or remove programming languages
   - Update frameworks and tools you know
   - Customize skill categories

5. **Projects Section** (around line 116):
   - Replace placeholder projects with your actual projects
   - Update project descriptions
   - Add your GitHub repository links
   - Link to live demos if available

6. **Contact Section** (around line 243):
   - Update email address
   - Add your LinkedIn profile URL
   - Update GitHub profile URL

7. **Footer** (around line 286):
   - Replace "Your Name" with your actual name

### Social Media Links

Update all instances of:
- `https://github.com/yourusername` → Your GitHub profile
- `https://linkedin.com/in/yourusername` → Your LinkedIn profile
- `your.email@example.com` → Your email address

### Profile Picture

The template currently uses a placeholder icon. To add your photo:

1. Add your image file to the project folder
2. In `index.html`, find the `.image-placeholder` div (around line 66)
3. Replace it with:
   ```html
   <img src="your-photo.jpg" alt="Your Name" class="profile-image">
   ```
4. In `styles.css`, add:
   ```css
   .profile-image {
       width: 300px;
       height: 300px;
       border-radius: 50%;
       object-fit: cover;
       box-shadow: var(--shadow-lg);
   }
   ```

### Color Scheme

To change the color scheme, update the CSS variables in `styles.css` (lines 8-17):

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --secondary-color: #1e40af;    /* Darker shade */
    --accent-color: #3b82f6;       /* Accent color */
    /* ... */
}
```

## 🎨 Sections Overview

1. **Navigation**: Fixed top navigation bar with smooth scroll
2. **Hero**: Eye-catching introduction with call-to-action buttons
3. **About**: Personal introduction with stats
4. **Skills**: Categorized display of technical skills
5. **Projects**: Portfolio of your best work
6. **Contact**: Contact form and social media links
7. **Footer**: Copyright and additional links

## 📱 Responsive Breakpoints

- Desktop: 1200px and above
- Tablet: 768px - 1199px
- Mobile: Below 768px
- Small Mobile: Below 480px

## 🌐 Deployment

### GitHub Pages

1. Make sure your repository is named `yourusername.github.io`
2. Push your code to the `main` branch
3. Go to repository Settings → Pages
4. Select `main` branch as source
5. Your site will be live at `https://yourusername.github.io`

### Other Hosting Options

- **Netlify**: Drag and drop your folder or connect your Git repository
- **Vercel**: Import your GitHub repository
- **Cloudflare Pages**: Connect your repository

## 🔧 Customization Tips

- **Fonts**: The template uses system fonts. To add custom fonts, include Google Fonts in the `<head>` section
- **Icons**: Using Font Awesome for icons. Can replace with other icon libraries
- **Contact Form**: Currently shows an alert. Integrate with:
  - [Formspree](https://formspree.io/)
  - [EmailJS](https://www.emailjs.com/)
  - [Netlify Forms](https://www.netlify.com/products/forms/)
  - Your own backend API

## 📄 License

This template is free to use for personal and commercial projects.

## 🤝 Contributing

Feel free to fork this project and customize it for your needs!

## 📞 Support

If you have questions or need help customizing your portfolio, feel free to reach out!

---

**Made with ❤️ for CS & Data Science students**
