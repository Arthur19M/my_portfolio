
# Portfolio – Arthur M

Personal portfolio website built with **HTML**, **CSS**, and Vanilla **JavaScript**.  
Fully responsive, animated, and bilingual (EN / FR).  

---

## Features

- Loader animation
- Responsive navigation with mobile menu
- Dynamic portfolio rendered from JSON data
- Project details popup
- About section with tabs
- Language switcher (English / French)
- Clean structure, no framework

---

## Project Structure

```
my_portfolio/
│
├── css/
│   ├── font-awesome.css
│   └── style.css
│
├── img/
│   ├── portfolio/
│   │   ├── 1.jpg
│   │   ├── 2.jpg
│   │   ├── 3.jpg
│   │   ├── 4.jpg
│   │   └── 5.jpg
│   ├── about-img.png
│   └── profile-img.png
│
├── js/
│   └── script.js
│
├── webfonts/
├── cv.pdf
├── index.html
├── translations.json
├── .nojekyll
└── README.md
````

---

## Multilingual System

- Language toggle button in the header
- Translations stored in `translations.json`
- Text injected dynamically using `data-key` attributes

---

## JavaScript Logic Overview

- Page loader and fade-in animation
- Navigation toggle and section switching
- About section tabs handling
- Portfolio modal popup with dynamic content
- Language switching and re-rendering
- Dynamic portfolio project generation

Main logic is located in `js/script.js`.

---

## How to Run

This project must be served over HTTP.  
Opening `index.html` directly will not load translations due to browser security (fetch + CORS).

### Option 1 — GitHub Pages (recommended)
Deploy the repository on GitHub Pages and open the provided URL.

### Option 2 — Local server

```bash
git clone https://github.com/Arthur19M/my_portfolio.git
cd my_portfolio/

# Python 3
python -m http.server 8000
```

Then open:

```
http://localhost:8000
```

---

## Customization

* **Add projects**: edit `translations.json`
* **Change images**: replace files in `img/portfolio/`
* **Update skills / content**: edit translation keys
* **Style changes**: `css/style.css`

---

## License

This project is based on a template released under the **Creative Commons Zero v1.0 Universal (CC0-1.0)** license.

All modifications and additions are released under the same license.

This project is open-source.
Feel free to use, modify, and adapt it for personal use.

See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

This portfolio is based on a template originally created by [PanduKonala](https://github.com/PanduKonala).

The template was adapted, extended, and customized (design, content, multilingual system, and portfolio logic).

---

2025 – Arthur M · ESIEA
