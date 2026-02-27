# Alex Rivera | Frontend Developer Portfolio

A clean, responsive, and beginner-friendly personal portfolio website built entirely with semantic HTML5 and modern CSS3.

## Folder Structure

```
portfolio/
├── index.html
├── assets/
│   ├── images/
│   │   ├── profile.jpg
│   │   ├── project1.jpg
│   │   └── project2.jpg
│   └── resume.pdf
├── css/
│   └── style.css
└── README.md
```

## How to Customize

This portfolio is designed to be easily customizable without needing to rewrite complex logic.

1.  **Personal Info:** Open `index.html` and search for "Alex Rivera" to update the name throughout the document, including the title tag, header logo, about section, and footer copyright.
2.  **Bio:** Update the paragraphs inside the `<div class="about-content">` section to reflect your own journey and experience.
3.  **Colors:** Open `css/style.css` and locate the `:root` block at the very top (under "1. CSS Variables & Reset"). You can change the hex codes for `--color-primary`, `--color-accent`, etc., to quickly apply a new color scheme across the entire site.
4.  **Images:** Replace the placeholder images in the `assets/images/` folder:
    *   `profile.jpg` (Used in the About section - recommend a 1:1 square aspect ratio)
    *   `project1.jpg` & `project2.jpg` (Used in the Projects section)
    *   *Note: Ensure your replacement images use the exact same filenames, or update the `src` attributes in `index.html`.*
5.  **Resume:** Replace the placeholder `resume.pdf` file in the `assets/` folder with your actual resume PDF. Ensure the filename matches, or update the `href` attribute in the Resume section of `index.html`.
6.  **Social Links:** Update the `href` attributes in the Contact section to point to your actual email address, phone number, LinkedIn profile, and GitHub profile.

## How to Run

Because this project uses vanilla HTML and CSS, no build steps, servers, or compilers are required.

Simply double-click `index.html` or open it in any modern web browser (Chrome, Firefox, Safari, Edge) to view the site locally.

## Technologies Used

*   **HTML5:** Employs semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) for structure, accessibility, and SEO.
*   **CSS3:** Utilizes modern layout techniques (Flexbox for alignment, CSS Grid for structured sections like skills and projects), custom properties (variables) for theming, and smooth transitions/hover effects for an engaging user experience.
*   **Responsive Design:** Implements media queries to ensure the layout adapts gracefully to different screen sizes, providing a seamless experience on desktops, tablets, and mobile phones.
