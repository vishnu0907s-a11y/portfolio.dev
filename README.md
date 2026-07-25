# 🚀 Shan — Personal Portfolio & Creative Developer

A modern, high-performance, fully responsive personal portfolio website built for **Shan**, Digital Designer & Creative Web Developer.

![vishnu's portfolio Badge](assets/images/logo/logo-secendary.png)

---

## 📌 Table of Contents
- [📖 Overview](#-overview)
- [✨ Key Features & Website Sections](#-key-features--website-sections)
- [🛠️ Technology Stack](#️-technology-stack)
- [📁 Project Architecture & File Directory](#-project-architecture--file-directory)
- [🚀 How to Use & Run Locally](#-how-to-use--run-locally)
  - [Method 1: Direct File Open](#method-1-direct-file-open)
  - [Method 2: VS Code Live Server](#method-2-vs-code-live-server)
  - [Method 3: Terminal Local HTTP Server](#method-3-terminal-local-http-server)
- [🌐 How to Deploy / Host Online](#-how-to-deploy--host-online)
  - [Deploying to GitHub Pages](#deploying-to-github-pages)
  - [Deploying to Vercel or Netlify](#deploying-to-vercel-or-netlify)
- [⚙️ How to Customize Every Detail](#️-how-to-customize-every-detail)
  - [1. Changing Your Name & Personal Branding](#1-changing-your-name--personal-branding)
  - [2. Updating Logos](#2-updating-logos)
  - [3. Updating Experience Counter (e.g. 2+ Years)](#3-updating-experience-counter-eg-2-years)
  - [4. Editing Images (About, Services, Portfolio)](#4-editing-images-about-services-portfolio)
  - [5. Updating Social Media Links](#5-updating-social-media-links)
  - [6. Configuring Contact Info & Email](#6-configuring-contact-info--email)
- [🔧 Troubleshooting & FAQ](#-troubleshooting--faq)
- [📄 License](#-license)

---

## 📖 Overview

This portfolio serves as a complete digital showcase of **Shan's** work, services, and creative design capabilities. It combines smooth motion graphics, custom GSAP animations, interactive UI elements, and a tailored dark aesthetic to deliver a state-of-the-art web experience.

---

## ✨ Key Features & Website Sections

1. **Header & Brand Navigation**:
   - Custom badge logo (**SHAN**) with vibrant gradient icons.
   - Quick navigation links (`Home`, `About Me`, `Portfolio`, `Services`, `Contact`).
   - "LET'S CONNECT" call-to-action button and offcanvas mobile menu toggle.

2. **Hero / Banner Section**:
   - Dynamic greeting (`Hello! I'm Shan, a digital designer and creative developer.`).
   - Core skills checklist (Web Development, Branding & Identity, Creative Strategy, UI/UX Design, Digital Marketing).
   - Dynamic counter badges showcasing **Projects Launched** and **Global Clients**.

3. **About Section**:
   - Highlighted biography and design philosophy.
   - Interactive **2+ Years of Experience** circular badge button.
   - Custom portrait/thumbnail image (`assets/images/thumbs/about-three-thumb.png`).

4. **Services Showcase**:
   - Accordion and card layout detailing digital design, custom frontend development, and branding packages.

5. **Portfolio / Work Gallery**:
   - Grid showcase of featured client work, web designs, and mobile app UI demos with hover animations.

6. **Testimonials Slider**:
   - Interactive client feedback slider powered by **Swiper JS** with video preview modals (Magnific Popup).

7. **Contact & Footer Section**:
   - Direct email link (`shan@gmail.com`) and phone contact.
   - Working contact message form.
   - Large centered branding heading (**SHAN**) and copyright declaration.

---

## 🛠️ Technology Stack

| Component | Technology Used | Description |
| :--- | :--- | :--- |
| **Core Structure** | HTML5 | Semantic structure and SEO-optimized markup |
| **Styles & Layout** | Vanilla CSS3 & Bootstrap 5 | Custom CSS variables, dark theme tokens, Bootstrap grid |
| **Animations** | GSAP 3 (GreenSock) | ScrollTrigger, ScrollSmoother, SplitText animations |
| **Scroll Revealing** | AOS.js (Animate On Scroll) | Smooth entrance reveals on scroll |
| **Sliders & Carousel**| Swiper.js | Touch-enabled responsive testimonial sliders |
| **Icons & Fonts** | Phosphor Icons & Google Fonts | Crisp vector iconography and modern typography |
| **Interactivity** | jQuery 3.7.1 | DOM manipulation and plugin bindings |

---

## 📁 Project Architecture & File Directory

```text
Portfolio/
├── README.md                     # Comprehensive documentation guide
├── index.html                    # Single-page application entry point
└── assets/
    ├── css/
    │   ├── main.css              # Core custom styles, theme colors, layout rules
    │   ├── bootstrap.min.css     # Responsive grid framework
    │   ├── swiper-bundle.css     # Slider styles
    │   ├── aos.css               # Scroll animation styles
    │   └── magnific-popup.css    # Lightbox popup modal styles
    ├── images/
    │   ├── logo/
    │   │   ├── logo.png          # Offcanvas mobile menu logo
    │   │   ├── logo-secendary.png# Main header navigation logo
    │   │   └── favicon.png       # Browser tab favicon icon
    │   ├── thumbs/
    │   │   ├── about-three-thumb.png # Main About image
    │   │   ├── portfolio-three-*.jpg # Portfolio showcase items
    │   │   ├── testimonial-*.jpg     # Testimonial client avatars
    │   │   └── team-img*.png         # Client avatar stack
    │   ├── shapes/               # Vector background shapes and ornaments
    │   └── icons/                # SVG action icons
    └── js/
        ├── custom-gsap.js        # GSAP animation initializations
        ├── slider-active.js      # Swiper slider configurations
        ├── aos.js                # AOS scroll animation library
        ├── jquery-3.7.1.min.js   # jQuery core library
        ├── boostrap.bundle.min.js# Bootstrap components script
        └── purecounter.js        # Number counting animations
```

---

## 🚀 How to Use & Run Locally

### Method 1: Direct File Open
1. Open your system's file manager and navigate to the project directory:
   `/home/shan/Documents/Portfolio`
2. Double-click **`index.html`** to open it directly in Google Chrome, Firefox, Safari, or Microsoft Edge.

### Method 2: VS Code Live Server
1. Open the `/home/shan/Documents/Portfolio` folder in **Visual Studio Code**.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click `index.html` and select **"Open with Live Server"**.

### Method 3: Terminal Local HTTP Server
Run any of the following commands in your project terminal:

- **Using Python 3**:
  ```bash
  python3 -m http.server 8000
  ```
  Then open `http://localhost:8000` in your web browser.

- **Using Node.js (`npx serve`)**:
  ```bash
  npx serve .
  ```

---

## 🌐 How to Deploy / Host Online

### Deploying to GitHub Pages
1. Initialize Git and commit your repository:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   ```
2. Create a new repository on GitHub and link remote:
   ```bash
   git remote add origin https://github.com/your-username/portfolio.git
   git branch -M main
   git push -u origin main
   ```
3. Go to **Repository Settings** > **Pages** > Select `main` branch and `/ (root)` folder > Click **Save**. Your site will be published live at `https://your-username.github.io/portfolio/`.

### Deploying to Vercel or Netlify
- **Vercel**: Drag and drop the `Portfolio` folder at [vercel.com/new](https://vercel.com/new).
- **Netlify**: Drag and drop the `Portfolio` folder at [app.netlify.com/drop](https://app.netlify.com/drop).

---

## ⚙️ How to Customize Every Detail

### 1. Changing Your Name & Personal Branding
Open `index.html` and search for occurrences of `Shan`:
- **Page Title**: `<title>Shan - Digital Agency & Creative Portfolio</title>` (line 17)
- **Hero Greeting**: `Hello! I'm Shan` (line 528)
- **Footer Title**: `<h5 class="footer-three-bottom-title text-white text-center">Shan</h5>` (line 2268)

### 2. Updating Logos
- To change the site header logo, replace the image files in `assets/images/logo/`:
  - `assets/images/logo/logo-secendary.png` (Main navigation)
  - `assets/images/logo/logo.png` (Mobile offcanvas)
- Or update the `src` attribute in `index.html` (lines 106 and 278).

### 3. Updating Experience Counter (e.g. 2+ Years)
In `index.html` around line 801:
```html
<span class="tw-btn-circle-icon text-heading tw-text-8 tw-transition-3 font-heading fw-medium">2+</span>
```
Change `2+` to any number you prefer.

### 4. Editing Images (About, Services, Portfolio)
- **About Image**: Place your photo at `assets/images/thumbs/about-three-thumb.png`.
- **Portfolio Images**: Place your project screenshots into `assets/images/thumbs/` and update lines 1253, 1310, 1367, 1424 in `index.html`.

### 5. Updating Social Media Links
Search for social media icons (`ph-facebook-logo`, `ph-x-logo`, `ph-instagram-logo`, `ph-linkedin-logo`) in `index.html` (lines 230-260 and lines 2115-2135) and set the `href="#"` attributes to your profile URLs.

### 6. Configuring Contact Info & Email
In `index.html` lines 2083-2092:
```html
<a href="mailto:shan@gmail.com">shan@gmail.com</a>
<a href="tel:+442039991245">+44 20 3999 1245</a>
```
Replace with your actual email address and telephone number.

---

## 🔧 Troubleshooting & FAQ

- **Q: An image is showing a broken icon (404 error)?**
  - **A**: Ensure the file extension in `index.html` matches the file system exactly (e.g., `.png` vs `.jpg`). Note that Linux file systems are case-sensitive.
- **Q: Smooth scrolling or GSAP animations are not triggering?**
  - **A**: Make sure JavaScript is enabled in your browser and check that `assets/js/custom-gsap.js` is properly loaded at the bottom of `index.html`.

---

## 📄 License

© 2025 Shan. All rights reserved. Free for personal & commercial portfolio usage.
