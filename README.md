# Amazon Clone 🛒

A front-end clone of the Amazon homepage built using pure **HTML** and **CSS**. This project replicates the look and feel of Amazon's US homepage, including the navigation bar, hero section, product cards, and footer.

---

## 📸 Preview

> The clone mirrors the layout of [amazon.com](https://www.amazon.com), featuring the navbar, product showcase boxes, a best sellers image strip, sign-in prompt, and footer.

---

## 🚀 Features

- **Responsive Navbar** — Includes the Amazon logo, delivery address indicator, search bar with category selector, sign-in, returns & orders, and cart icon.
- **Navigation Panel** — Secondary nav bar with category links: Today's Deals, Gift Cards, Sell, Registry, Prime Video, and Customer Service.
- **Hero Section** — Full-width banner image with a redirect message linking to Amazon India.
- **Product Showcase Boxes** — Four product cards highlighting:
  - Gaming
  - New Home Arrivals under $50
  - Fashion deals (Jeans, Tops, Dresses, Shoes)
  - Mother's Day gift ideas (Apparel, Shoes, Jewelry, Handbags)
- **Best Sellers Strip** — Horizontal image gallery for Clothing, Shoes & Jewelry.
- **Sign-In Prompt** — Encourages users to sign in for personalized recommendations.
- **Back to Top** — One-click scroll back to the top of the page.
- **Footer** — Includes legal links and copyright information.

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Page structure and semantic markup |
| **CSS3** | Styling, layout (Flexbox), hover effects |
| **Font Awesome 7** | Icons (cart, location pin, search, hamburger menu) |

> ⚠️ No JavaScript, frameworks, or libraries were used. This is a pure HTML + CSS project.

---

## 📁 Project Structure

```
amazon-clone/
├── index.html                  # Main HTML file
├── style.css                   # Stylesheet
├── README.md
└── images/
    ├── amazon-logo.png         # Amazon navbar logo
    ├── hero_image.jpg          # Hero banner background
    │
    ├── box1_image.jpg          # Gaming section
    │
    ├── kitchen_and_dining.jpg  # Home box images
    ├── home_improvement.jpg
    ├── decor.jpg
    ├── bedding_and_bath.jpg
    │
    ├── jeans_under_50.jpg      # Fashion box images
    ├── tops_under_25.jpg
    ├── dresses_under_30.jpg
    ├── shoes_under_50.jpg
    │
    ├── apparel.jpg             # Gifts box images
    ├── shoes.jpg
    ├── jewelry.jpg
    ├── handbags.jpg
    │
    ├── image1.jpg              # Best sellers strip
    ├── image2.jpg
    ├── image3.jpg
    ├── image4.jpg
    ├── image5.jpg
    ├── image6.jpg
    ├── image7.jpg
    └── image8.jpg
```

---

## ⚙️ Getting Started

### Prerequisites

No installations required. Just a modern web browser.

### Running the Project

1. **Clone or download** this repository:
   ```bash
   git clone https://github.com/your-username/amazon-clone.git
   ```

2. **Navigate** into the project folder:
   ```bash
   cd amazon-clone
   ```

3. **Open** `index.html` in your browser:
   - Double-click `index.html`, **or**
   - Right-click → *Open with* → your preferred browser, **or**
   - Use a VS Code extension like **Live Server** for a better development experience.

---

## 🎨 Design Highlights

- Color scheme closely follows Amazon's brand palette (`#131921`, `#232F3E`, `#f08804`, `#ffd814`).
- Flexbox is used throughout for layout — navbar, panel, product boxes, image strip, and footer.
- Hover effects on navbar items, panel options, the search bar, and the sign-in button.
- Font Awesome icons enhance the UI without any extra scripting.

---

## 📌 Known Limitations

- **Not responsive** — The layout is optimized for desktop screens and may not render well on mobile or tablet devices.
- **No JavaScript** — Interactive features like dropdown menus, cart functionality, and search are not implemented.
- **Static images** — Product images are locally referenced and must be present in the project folder.
- **Links** — Most links point to the real Amazon website and are used for reference only.

---

## 🌱 Future Improvements

- [ ] Add CSS media queries for mobile responsiveness
- [ ] Implement a JavaScript-powered search bar
- [ ] Add a working cart counter with JavaScript
- [ ] Create additional pages (product detail, login page)
- [ ] Replace static images with a product API

---

## 🙏 Acknowledgements

- Inspired by [Amazon.com](https://www.amazon.com)
- Icons provided by [Font Awesome](https://fontawesome.com)

---

## 📄 License

This project is intended for **educational purposes only**. All Amazon branding, trademarks, and product imagery belong to Amazon.com, Inc.

---

> Made with ❤️ using HTML & CSS
