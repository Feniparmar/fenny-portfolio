# My Portfolio Website

A professional, fully responsive portfolio website built with HTML5, CSS3, Bootstrap 5, and JavaScript.

## 📋 What's Included

### 1. **Navigation Bar**
   - Sticky navigation with smooth scrolling
   - Mobile responsive hamburger menu
   - Active link highlighting

### 2. **Hero Section**
   - Eye-catching gradient background
   - Call-to-action buttons
   - Animated entrance effects

### 3. **About Section**
   - Profile picture placeholder
   - Personal introduction
   - Social media links (GitHub, LinkedIn, Twitter)

### 4. **Skills Section**
   - 4 skill cards with icons
   - Visual progress bars
   - Hover animations
   - **Customize:** Add your own skills and proficiency levels

### 5. **Projects Section**
   - 3 project showcase cards
   - Project descriptions and badges
   - Hover effects and animations
   - **Customize:** Add links to your GitHub projects

### 6. **Contact Section**
   - Functional contact form with validation
   - Contact information display
   - Form validation (email, required fields)

### 7. **Footer**
   - Social media links
   - Copyright information

---

## 🎨 How to Customize

### **1. Update Personal Information**
Edit `index.html`:
- Line 26: Change "Fenny" to your name
- Line 27: Update your title/profession
- Line 46: Add your portfolio items count or tagline

### **2. Update About Section**
- Line 84: Replace placeholder image URL with your photo
  ```html
  <img src="path-to-your-image.jpg" alt="Profile" class="img-fluid rounded-circle shadow">
  ```
- Lines 87-92: Edit your bio and background information
- Lines 93-99: Update social media links

### **3. Customize Skills**
Edit the skill cards (lines 114-151):
- Change skill names (HTML & CSS, JavaScript, etc.)
- Update descriptions
- Modify proficiency percentages (95%, 90%, etc.)
- Change icon colors by updating the class

### **4. Add Your Projects**
Replace project cards (lines 168-218):
- Change image URLs to your project screenshots
- Update project titles and descriptions
- Add technology badges
- Link to GitHub repositories

### **5. Update Contact Information**
- Line 237: Add your email address
- Line 238: Add your phone number
- Lines 258-260: Update social media links

### **6. Change Colors**
Edit `style.css` (lines 8-16):
```css
:root {
    --primary-color: #0d6efd;      /* Main button color */
    --secondary-color: #6c757d;
    --dark-color: #212529;
    --light-color: #f8f9fa;
}
```

### **7. Change Hero Gradient**
Edit `style.css` (line 92):
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
/* Change these color codes to your preferred colors */
```

---

## 🚀 Features

✅ **Fully Responsive** - Works on desktop, tablet, and mobile  
✅ **Modern Design** - Clean, professional appearance  
✅ **Smooth Animations** - Fade-in effects and hover states  
✅ **Form Validation** - Client-side validation for contact form  
✅ **Bootstrap Framework** - Fast development with Bootstrap 5  
✅ **Font Awesome Icons** - 1000+ icons included  
✅ **SEO Friendly** - Proper HTML5 semantic tags  
✅ **Fast Loading** - CDN resources for quick performance  

---

## 📱 Responsive Breakpoints

- **Desktop:** 1024px and above
- **Tablet:** 768px to 1023px
- **Mobile:** Below 768px

---

## 🎯 JavaScript Features

- **Smooth Scrolling** - Click navigation links for smooth page scroll
- **Form Validation** - Email validation and required field checks
- **Intersection Observer** - Fade-in animations when scrolling into view
- **Active Link Highlighting** - Navigation highlights current section
- **Scroll-to-Top Button** - Easy return to top of page
- **Mobile Menu Auto-close** - Menu closes after clicking a link

---

## 📦 Required Files

```
Fenny Portfolio/
├── index.html       (Main HTML file)
├── style.css        (Styling)
├── script.js        (JavaScript functionality)
└── README.md        (This file)
```

---

## 🔗 External Resources Used

- **Bootstrap 5:** https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/
- **Font Awesome:** https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/
- **Google Fonts:** (Optional - can be added)

---

## 💡 Tips for Enhancement

1. **Add Google Analytics** - Track visitor analytics
2. **Add Email Backend** - Use services like Formspree, Netlify Forms
3. **Deploy Online** - Use GitHub Pages, Netlify, or Vercel
4. **Add More Projects** - Keep updating your project section
5. **Optimize Images** - Compress images for faster loading
6. **Add Dark Mode** - Toggle between light and dark themes
7. **SEO Optimization** - Add meta descriptions and keywords

---

## 🛠️ How to Host for Free

### **Option 1: GitHub Pages**
1. Create a GitHub account
2. Create new repository named `username.github.io`
3. Upload your portfolio files
4. Access at `https://username.github.io`

### **Option 2: Netlify**
1. Sign up at netlify.com
2. Connect your GitHub repository
3. Auto-deploys on every push
4. Free custom domain option

### **Option 3: Vercel**
1. Sign up at vercel.com
2. Import your repository
3. Automatic deployment
4. Fast CDN worldwide

---

## 📝 Next Steps

1. ✅ Replace placeholder images with your photos
2. ✅ Update all text with your information
3. ✅ Add your projects with live links
4. ✅ Update social media profiles
5. ✅ Test on mobile devices
6. ✅ Deploy to a hosting service
7. ✅ Share your portfolio with potential employers

---

## 📄 License

This template is free to use and modify for personal purposes.

---

**Created:** March 2026  
**Version:** 1.0.0  
**Status:** Ready to customize

Enjoy building your portfolio! 🚀
