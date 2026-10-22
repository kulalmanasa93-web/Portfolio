# Manasa Kulal — Modern AI/ML & Engineering Portfolio

A modern, high-performance, and fully responsive personal portfolio website crafted for **Manasa Kulal**, Fourth-year B.E. Computer Science and Engineering student specializing in **Artificial Intelligence and Machine Learning (AI & ML)** at **AJ Institute of Engineering and Technology, Mangalore** (Expected Graduation: 2028).

---

## 🌟 Highlights & Key Features

- **🎨 Modern Purple & Pink Gradient Design System**:
  - Customized aesthetic with deep violet, magenta, and soft ambient glows.
  - Glassmorphic navigation bar with backdrop blur and active section indicator (ScrollSpy).
  - Modern typography using Google Fonts (*Outfit* and *Plus Jakarta Sans*).
- **🌗 Functional Dark & Light Mode Toggle**:
  - Smooth color transitions with persistent user preference in `localStorage`.
  - Automatically respects the operating system's color scheme (`prefers-color-scheme`).
- **⚡ Dynamic Hero Section**:
  - Real-time animated typing effect highlighting core roles (*AI & ML Specialist*, *Python & Web Developer*, etc.).
  - Interactive avatar illustration with floating tech chips.
  - Clear Action buttons: *Explore Projects*, *Download Resume*, *Contact Me*.
- **📄 Complete Resume Integration**:
  - **Direct PDF Download**: Working resume file (`assets/docs/Manasa_Kulal_Resume.pdf`) ready for recruiters.
  - **Standalone Printable Web Resume**: Dedicated `resume.html` with vector typography and clean `@media print` layout.
- **💻 Filterable Skills Section**:
  - Interactive category filters: *All*, *AI & Machine Learning*, *Programming Languages*, *Web Development*, *Databases & Tools*.
  - Visual proficiency indicators and icons.
- **🚀 Featured Projects with Deep-Dive Modals**:
  1. **Language Translation Tool** — Python-based translation system using AI and NLP.
  2. **General FAQ Chatbot** — Conversational system utilizing text preprocessing, TF-IDF vectorization, cosine similarity, and Gradio UI.
  3. **Blood Management System** — Full-stack web application with PHP, MySQL, XAMPP, and JavaScript.
  - Detailed modal views displaying architecture, key features, and tech stacks.
- **🎓 Verified Education & Certifications**:
  - B.E. in CSE (AI & ML) at AJ Institute of Engineering and Technology, Mangalore (2024–2028 expected).
  - **Infosys Springboard Certification** in Python, AI/ML fundamentals, and related technologies.
- **🌐 Communication & Languages**:
  - English (Professional Working), Kannada (Native), Hindi (Conversational).
- **📬 Interactive Contact Form & Client-Side Validation**:
  - Instant validation for Name, Email, Subject, and Message.
  - Opens a pre-formatted draft in the user's default email client (`mailto:kulalmanasa93@gmail.com`).
  - Fallback confirmation popup with a **1-click Copy Drafted Message** feature.
- **📱 100% Mobile-Friendly & Accessible**:
  - Responsive drawer navigation menu for mobile devices.
  - High-contrast colors adhering to WCAG standards.
  - Semantic HTML5 tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<aside>`).
- **🛡️ 100% Truthful**:
  - Strictly relies on provided profile details without fabricated statistics or fake results.

---

## 📁 Project Directory Structure

```text
manasa-kulal-portfolio/
│
├── index.html                   # Main portfolio single-page application
├── resume.html                  # Standalone printable & downloadable web resume
├── README.md                    # Project documentation & deployment guide
│
├── css/
│   └── style.css                # Complete CSS styles with dark/light theme variables
│
├── js/
│   ├── script.js                # Interactive logic (themes, typing, modals, validation)
│   └── generate-pdf.js          # Generator script for authentic PDF document
│
└── assets/
    ├── docs/
    │   └── Manasa_Kulal_Resume.pdf   # Downloadable official resume file
    └── images/
        ├── favicon.svg          # Stylized MK logo
        ├── avatar.svg           # Tech avatar illustration
        ├── project-translation.svg # Banner for Language Translation Tool
        ├── project-chatbot.svg     # Banner for General FAQ Chatbot
        └── project-blood.svg       # Banner for Blood Management System
```

---

## 🚀 How to Run Locally

You can run this portfolio locally without installing any web servers:

### Option 1: Direct Double-Click
1. Open the folder `manasa-kulal-portfolio`.
2. Double-click `index.html` to open it in your browser (Chrome, Edge, Firefox, Safari).

### Option 2: VS Code Live Server (Recommended for developers)
1. Open the folder in **Visual Studio Code**.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click `index.html` and choose **"Open with Live Server"**.

### Option 3: Local Node / Python Server
- Using Node:
  ```bash
  npx serve .
  ```
- Using Python:
  ```bash
  python -m http.server 8000
  ```
  Then visit `http://localhost:8000` in your web browser.

---

## 🌐 How to Publish Online for Free

### Method 1: GitHub Pages (Recommended)

1. **Create a GitHub Account**: If you don't already have one, create an account at [github.com](https://github.com).
2. **Create a New Repository**:
   - Repository Name: `portfolio` or `manasa-kulal.github.io`.
   - Set visibility to **Public**.
   - Do not initialize with README or license.
3. **Upload Files**:
   - In your newly created repository page, click **"uploading an existing file"**.
   - Drag and drop all files and folders (`index.html`, `resume.html`, `css/`, `js/`, `assets/`, `README.md`) directly into GitHub.
   - Click **Commit changes**.
4. **Enable GitHub Pages**:
   - Go to your repository's **Settings** tab.
   - On the left sidebar, click **Pages**.
   - Under **Build and deployment > Branch**, select `main` (or `master`) and `/ (root)`.
   - Click **Save**.
5. Within 1–2 minutes, your website will be live at:
   `https://<your-username>.github.io/<repository-name>/`

---

### Method 2: Netlify (Drag-and-Drop, 30 seconds)

1. Go to [netlify.com](https://www.netlify.com) and log in.
2. Go to **Sites** > **Add new site** > **Deploy manually**.
3. Drag and drop the `manasa-kulal-portfolio` folder directly onto the screen.
4. Netlify will publish your site in seconds with a custom HTTPS URL.

---

## ✏️ How to Personalize Your GitHub URL

Search for `manasa-kulal` or `[Placeholder]` in `index.html` and `resume.html` and replace it with your official GitHub profile link once you set it up:
- Target line in `index.html`:
  ```html
  <a href="https://github.com/manasa-kulal" ...>
  ```
  Change to:
  ```html
  <a href="https://github.com/YOUR_ACTUAL_USERNAME" ...>
  ```

---

## 💼 Recruiter Checklist

When sending your portfolio to recruiters and hiring managers:
1. Include the link in your LinkedIn **Featured** section and **Contact Info**.
2. Add the URL to your resume header alongside your email and phone number.
3. Test that clicking **Resume** downloads your latest resume PDF.
4. Test the **Send a Message** form to ensure it triggers your default email client smoothly.

---

&copy; 2026 Manasa Kulal. All rights reserved.
