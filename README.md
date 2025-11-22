# ALX HTML & CSS Project

This repository contains a set of HTML & CSS projects and exercises as part of the ALX curriculum. It focuses on building responsive, well-structured web pages, exploring CSS fundamentals, layout techniques, and advanced styling features.

---

## 📁 Repository Structure

```

alx_html_css/
│
├── css_basic/           # Basic CSS exercises and foundational styling
|    |── base.css
|    |── index.html
|    |── styles.css
|    |── tweets.html
├── css_advanced/        # More advanced CSS projects (grid, flex, animations, etc.)
|    |── index.html
|    |── styles.css
|    |── images
|    |── README      
├── fonts/               # Custom font files used across projects
├── assets/              # Images, icons, and other media assets
├── index.html           # (Optional) Main landing/demo page
├── style.css            # (Optional) Shared global stylesheet
└── README               #Project Documentation 

```

---

## 🛠 Features & Highlights

- Semantic HTML structure  
- CSS layout techniques: Flexbox, Grid  
- Typography with custom fonts (`@font-face`)  
- Responsive design principles (mobile-first)  
- Styling effects: shadows, gradients, overlays, hover states  
- Use of CSS custom properties (variables) for theming  

---

## 🚀 Getting Started

1. **Clone** the repository:
   ```bash
   git clone https://github.com/SireTallest/alx_html_css.git
```

2. **Navigate** into the project folder:

   ```bash
   cd alx_html_css
   ```

3. **Open** the HTML files in your browser (e.g. `index.html` or files inside `css_advanced/`) to view them.

4. **Edit** the CSS or HTML files in your code editor, then refresh the browser to see changes.

---

## 🧩 Usage Examples

* To include a custom font:

  ```css
  @font-face {
    font-family: 'source-sans-pro';
    src: url('fonts/source-sans-pro-Regular.otf') format('opentype');
    font-weight: 400;
    font-style: normal;
  }
  ```

  ```css
  @font-face {
    font-family: 'spincycle-ot';
    src: url('fonts/spincycle-ot-Regular.otf') format('opentype');
    font-weight: 400;
    font-style: normal;
  }
  ```

* To create a responsive grid:

  ```css
  .grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5rem;
  }
  ```

* To overlay a semi-transparent gradient over an image:

  ```css
  header {
    background: 
      radial-gradient(circle, rgba(255,255,255,0.6), rgba(0,0,0,0.5)),
      url('../assets/backgroundHero.jpg') center/cover no-repeat;
  }
  ```

---

## ✅ Tips & Best Practices

* Keep styles modular: avoid one huge CSS file by grouping related rules.
* Use **CSS variables** for colors, spacing, and typography for easier theming and maintenance.
* Test your pages on multiple screen sizes (mobile, tablet, desktop).
* Keep image file sizes optimized (compressed) to improve performance.
* Use meaningful class names to keep your HTML and CSS readable.

---

## 📝 Contributing

Feel free to contribute! You can:

* Add new layout examples (cards, galleries, forms)
* Create media queries
* Improve existing styles or responsiveness
* Add documentation or comments for clarity

Steps:

1. Fork this repository
2. Create your feature branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -m "Add feature"`)
4. Push to your fork (`git push origin feature-name`)
5. Open a Pull Request

---

