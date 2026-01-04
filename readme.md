# Nikki Shukla - Personal Portfolio

A modern, responsive personal portfolio website showcasing my skills, projects, and experience as a MERN Stack Developer and Computer Science Engineering student.

![Portfolio Preview](image.png)

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works perfectly on all devices
- **Smooth Animations**: CSS animations and JavaScript-powered interactions
- **Interactive Elements**:
  - Mobile-friendly hamburger menu
  - Animated skill progress bars
  - Certificate slider with auto-play
  - Typing effect in hero section
  - Smooth scroll navigation
- **Contact Form**: Integrated EmailJS for direct messaging
- **Modern UI/UX**: Clean design with gradient backgrounds and hover effects
- **Performance Optimized**: Fast loading with optimized assets

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript (ES6+)**: Interactive functionality and DOM manipulation
- **EmailJS**: Contact form integration
- **Font Awesome**: Icons and social media links

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── image.png           # Profile photo
├── readme.md           # Project documentation
└── certificates/       # Certificate images
    ├── certi1.png
    ├── certi2.png
    ├── certi3.png
    ├── certi4.png
    └── certi5.png
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software required - this is a static website

### Installation

1. **Clone or Download** the project files to your local machine

2. **Navigate** to the project directory:
   ```bash
   cd portfolio
   ```

3. **Open** `index.html` in your web browser:
   - Double-click the file, or
   - Right-click and select "Open with" your preferred browser, or
   - Use a local server (optional but recommended for better functionality)

### Local Server (Optional)

For the best experience, especially for the contact form functionality, run the project on a local server:

- **Using Python** (if installed):
  ```bash
  python -m http.server 8000
  ```
  Then visit `http://localhost:8000`

- **Using Node.js** (if installed):
  ```bash
  npx serve .
  ```

## 📖 Usage

### Navigation
- Use the navigation menu to jump to different sections
- On mobile devices, tap the hamburger menu (☰) to access navigation

### Sections Overview

1. **Home/Hero**: Introduction with profile photo and call-to-action buttons
2. **About**: Personal information, education, and current status
3. **Skills**: Technical skills categorized by frontend, backend, and tools
4. **Projects**: Showcase of featured projects with links and tech stacks
5. **Certificates**: Interactive slider displaying certifications
6. **Experience**: Timeline of education and work experience
7. **Contact**: Contact form and social media links

### Contact Form
- Fill out the contact form to send a direct message
- The form uses EmailJS for backend functionality
- Form validation ensures all fields are properly filled

## 🎨 Customization

### Personal Information
Edit the following in `index.html`:
- Name, title, and description in the hero section
- About section content
- Skills and their proficiency levels
- Project details and links
- Experience timeline
- Contact information and social media links

### Styling
Modify `styles.css` to:
- Change color scheme (update CSS variables at the top)
- Adjust animations and transitions
- Modify layout and spacing
- Customize fonts and typography

### Functionality
Update `script.js` to:
- Add new interactive features
- Modify animation timings
- Update EmailJS configuration
- Add new sections or effects

### Images
Replace the following files:
- `image.png`: Your profile photo
- `certificates/*.png`: Your certificate images

## 📧 Contact Form Setup

The contact form uses EmailJS. To set it up:

1. Sign up at [EmailJS](https://www.emailjs.com/)
2. Create a new email service and template
3. Update the service ID, template ID, and user ID in `script.js`:
   ```javascript
   emailjs.init("YOUR_USER_ID");

   emailjs.sendForm(
     "YOUR_SERVICE_ID",
     "YOUR_TEMPLATE_ID",
     this
   )
   ```

## 🌐 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings → Pages
3. Select "main" branch as source
4. Your portfolio will be live at `https://yourusername.github.io/repository-name`

### Other Platforms
- **Netlify**: Drag and drop the project folder
- **Vercel**: Connect your GitHub repository
- **Firebase**: Use Firebase Hosting
- **Traditional Hosting**: Upload files to any web server

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Nikki Shukla**
- Email: nikkishukla95100@gmail.com
- LinkedIn: [Nikki Shukla](https://www.linkedin.com/in/nikki-shukla-69840a319/)
- GitHub: [nikkishukla123](https://github.com/nikkishukla123)

---

⭐ **Star this repo** if you found it helpful!

*Built with ❤️ by Nikki Shukla*
