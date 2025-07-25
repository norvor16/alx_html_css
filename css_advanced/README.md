

---

# Advanced CSS Project

This project focuses on building and styling a professional-looking webpage using advanced CSS techniques, following the provided design specifications in Figma.

## 📁 Project Structure

```

css\_advanced/
├── index.html
├── styles/
│   └── styles.css
├── images/
│   └── (all downloaded assets)
├── fonts/
│   └── SourceSansPro, SpinCycleOT
└── README.md

````

## 📌 Objectives

- Recreate a webpage based on a high-fidelity Figma design.
- Implement responsive and modern styling using CSS.
- Integrate web fonts and image assets.
- Clean up and adjust the HTML markup as needed to align with the design.

## 🖌️ Design Source

- **Figma Page:** [Access Design in Figma](<insert Figma link>)
- Make sure to **Duplicate to Drafts** for full access to styles and measurements.
- Fonts to install:
  - [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)
  - [Spin Cycle OT](https://www.fonts.com/font/spin-cycle)

## 🔧 Installation & Setup

1. Clone this repository:

```bash
git clone https://github.com/your-username/alx_html_css.git
cd alx_html_css/css_advanced
````

2. Open `index.html` in your browser to view the project.

3. Link your local or online fonts and images properly in the `index.html` and `styles.css` files.

## 🧠 Technologies Used

* HTML5
* CSS3 (Flexbox, Grid, Media Queries)
* Google Fonts
* Figma (for UI/UX design reference)

## 💡 Notes

* If some values appear in float in Figma (e.g., `32.13px`), feel free to round to the nearest pixel.
* The original HTML code from the "HTML, Advanced" concept page is used and modified where necessary to incorporate styles, images, and fonts.

## 👨‍💻 Author

This project is part of the ALX SE curriculum. Built with 💙 and code.

````

---

### ✅ `index.html`

Here's a simplified version to start with (based on ALX's HTML Advanced project):

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Advanced CSS Project</title>
  <link rel="stylesheet" href="styles/styles.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@300;400;700&display=swap"
    rel="stylesheet"
  />
</head>
<body>
  <!-- Header -->
  <header>
    <div class="logo">
      <img src="images/logo.png" alt="Logo" />
    </div>
    <nav>
      <ul>
        <li><a href="#">Courses</a></li>
        <li><a href="#">Pricing</a></li>
        <li><a href="#">Login</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
      <h1>Learn to code by watching others</h1>
      <p>See how experienced developers solve problems in real-time.</p>
      <a href="#" class="cta-button">Start now</a>
    </div>
    <img src="images/hero-image.png" alt="Hero Illustration" />
  </section>

  <!-- Main Content -->
  <main>
    <!-- Add content sections here -->
  </main>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 ALX CSS Project. All rights reserved.</p>
  </footer>
</body>
</html>
````

---

### ✅ Next Steps

1. Add full styling in `styles/styles.css` to match the Figma design.
2. Replace image placeholders (e.g., `hero-image.png`, `logo.png`) with actual images from the downloaded assets.
3. Integrate any animations or transitions as specified in the design.
4. Ensure responsiveness using media queries.

