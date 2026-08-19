# 💍 Marriage BioData Template

> A modern, responsive, and glassmorphic bio-data template for matrimonial profiles, built with vanilla HTML, CSS, and JavaScript.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

A sleek and elegant **Marriage BioData Template** designed for the modern era. It features a beautiful glassmorphic card, a toggleable dark mode with persistent user preference, and a fully responsive layout.

Perfect for sharing personal and family details in a visually appealing format.

---

## ✨ Features

* **🌗 Dark/Light Mode Toggle** – Switch themes with a single click. Theme preference is saved in `localStorage`.
* **🧊 Glassmorphic Design** – Frosted-glass card with backdrop blur and subtle transparency.
* **📱 Fully Responsive** – Optimized for mobile, tablet, and desktop.
* **🖼️ Photo Gallery Grid** – Includes placeholder images with interactive hover effects.
* **🎨 Customizable** – Easily edit personal, family, career, and business information.
* **⚡ Zero Dependencies** – Built entirely with vanilla HTML, CSS, and JavaScript.
* **🔧 Semantic HTML** – Clean and well-structured markup.
* **📦 Lightweight** – Minimal footprint and fast loading.
* **💾 Persistent Theme** – User theme preference is stored using `localStorage`.

---

## 🚀 Live Demo

You can view a live demo here:

[Demo Link](https://your-demo-link.com)

> Replace the demo URL with your actual deployed project URL.

---

## 🛠️ Tech Stack

| Technology        | Purpose                                                |
| ----------------- | ------------------------------------------------------ |
| HTML5             | Structure and content                                  |
| CSS3              | Styling, glassmorphism, animations, and responsiveness |
| JavaScript (ES6+) | Theme toggle and interactive functionality             |
| localStorage      | Persistent theme preference                            |

---

## 📦 Getting Started

### Prerequisites

Before running the project, make sure you have:

* A modern web browser such as Chrome, Firefox, Edge, or Safari
* Optional: A local development server such as VS Code Live Server

No Node.js or build tools are required.

### Installation

#### 1. Clone the repository

```bash
git clone https://github.com/your-username/marriage-biodata-template.git
```

#### 2. Navigate to the project directory

```bash
cd marriage-biodata-template
```

#### 3. Open the project

You can simply open `index.html` directly in your browser.

Or use a local development server:

```bash
npx serve .
```

Alternatively:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

No build step is required — the project is ready to use.

---

## 🎨 Customization

All personal information is stored directly in `index.html`, making the template easy to customize.

### ✏️ Changing Personal Details

Open `index.html` and update the relevant sections.

* **Profile Photo:** Replace `./Rectangle 2.png` with your own image path.
* **Name:** Update the text inside `<h1>Your <span>Name</span></h1>`.
* **Designation & Salary:** Update `<p class="designation">Designation <span>(Salary)</span></p>`.
* **Family Details:** Edit the `<li>` elements under the **Family Details** section.
* **Maternal Details:** Edit the `<li>` elements under the **Maternal Details** section.
* **Personal Details:** Update birth date, birth time, height, and other information.
* **Job Details:** Modify company, location, designation, and salary information.
* **Business Details:** Update the business name and location.
* **Photos:** Replace the image `src` attributes inside `.photo-grid` with your own images.

---

## 🎨 Changing Colors & Theme

All styling is handled inside `style.css`.

To change the primary accent color, find the default blue color:

```css
#2196f3
```

and replace it with your preferred color.

Dark mode styles are defined using:

```css
body.dark
```

You can customize the dark-mode background, text colors, borders, shadows, and other properties as needed.

---

## 🧩 Changing Images

Place your images inside the project directory and update their paths in `index.html`.

For example:

```html
<img src="./images/profile.jpg" alt="Profile Photo">
```

You can also replace the decorative SVG images with your own assets.

---

## 📁 Project Structure

```text
marriage-biodata-template/
├── index.html          # Main HTML file
├── style.css           # All styles and themes
├── script.js           # Theme toggle and localStorage logic
├── Rectangle 2.png     # Profile photo placeholder
├── Rectangle 2 (1).png # Photo gallery image
├── Frame 8.png         # Photo gallery image
├── Frame 3.png         # Photo gallery image
├── Frame 6.png         # Photo gallery image
├── Frame 7.png         # Photo gallery image
├── screenshots/
│   ├── light.png       # Light mode screenshot
│   └── dark.png        # Dark mode screenshot
├── LICENSE             # MIT License
└── README.md           # Project documentation
```

---

## 📸 Screenshots

### ☀️ Light Mode

![Light Mode](./screenshots/light.png)

### 🌙 Dark Mode

![Dark Mode](./screenshots/dark.png)

> Add your screenshots to the `screenshots` folder and update the paths if necessary.

---

## 🤝 Contributing

Contributions are always welcome and greatly appreciated.

To contribute:

1. Fork the project.
2. Create your feature branch:

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes:

```bash
git commit -m "Add some AmazingFeature"
```

4. Push your branch:

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request.

---

## 📄 License

Distributed under the **MIT License**.

See the `LICENSE` file for more information.

---

## 🙏 Acknowledgments

* [SVGShare](https://svgshare.com/) – For decorative SVG assets.
* [Google Fonts](https://fonts.google.com/) – For additional typography options.
* Placeholder images – Used for demonstration purposes only.

---

## 📬 

### Project Link

https://github.com/JahanzaibJameel/BioData-template

<div align="center">

**Made with ❤️ and lots of ☕**

</div>
