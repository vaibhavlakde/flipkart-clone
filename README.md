# 🛒 Flipkart Web Clone (Pure Vanilla HTML5, CSS3 & JavaScript)

A high-fidelity, fully functional **Flipkart Clone** engineered strictly with **HTML5, CSS3, and Vanilla JavaScript (ES6+)**. 

> **🎯 Pure Vanilla Web Implementation**  
> This project is engineered strictly using foundational web technologies (**HTML5, CSS3, and Vanilla JavaScript**) with zero external frameworks or runtime dependencies to guarantee maximum performance, clean code architecture, and high reliability.

---

## 📋 Alignment with Job Description & Requirements

| Job Requirement | Implementation in this Project |
| :--- | :--- |
| **Frontend Technologies (HTML5, HTML, CSS, JavaScript)** | • **HTML5**: Semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`, `<dialog>`-pattern modals).<br>• **CSS3**: CSS Custom Properties (Variables), Flexbox & Grid layouts, media queries for all screen sizes, smooth CSS transitions.<br>• **Vanilla JavaScript (ES6+)**: Event delegation, DOM manipulation, asynchronous timer updates, LocalStorage persistence, Array methods (`filter`, `reduce`, `map`, `sort`). |
| **Content Management Systems (CMS) & Website Authoring** | **Integrated CMS Authoring Console**: A built-in web authoring panel that lets non-technical content authors publish new products, customize promotional banners, and manage catalog data dynamically in real time without touching source code. |
| **Problem Solving** | Resilient search with live suggestion filtering, debounced inputs, price-discount calculations, cart state synchronization across components, image error fallbacks (`onerror`). |
| **Quality & Maintainability** | Modular code organization, strict mode (`'use strict'`), zero console errors, zero build dependencies, clear code comments throughout. |

---

## 🚀 How to Run the Project

No installation, build tools, or server setup required:

1. Navigate to the project folder:
   ```
   C:\Users\vaibh\.gemini\antigravity\scratch\flipkart-clone\
   ```
2. Double-click **`index.html`** or right-click and choose **"Open with Chrome / Edge / Firefox"**.
3. *Optional (VS Code)*: Right-click `index.html` and click **"Open with Live Server"**.

---

## ✨ Features Breakdown

### 1. Header & Navigation
- Flipkart brand logo with **Explore Plus** badge.
- **Instant Search Bar** with real-time autocomplete suggestions and live product matching.
- **Login Modal** with phone/email input and guest checkout option.
- **Cart Button** with real-time item count badge.
- **CMS Authoring Tool Button** directly accessible in the top navbar.

### 2. Category Quick Nav Bar
- Clean category pills (Mobiles, Electronics, Fashion, Appliances, Furniture, Grocery) with active states and one-click filtering.

### 3. Hero Promotional Banner Carousel
- Smooth sliding carousel showcasing Flipkart seasonal deals.
- Automatic cycling (every 4.5 seconds) with pause-on-hover.
- Manual arrow navigation and interactive pagination dots.

### 4. Deal of the Day & Live Countdown Timer
- Real-time countdown timer ticking down to simulate flash sales.
- "View All" button instantly sorting products by biggest discount.

### 5. Advanced Sidebar Filtering & Sorting
- **Category checkboxes** with live synchronization.
- **Dynamic Price Range Slider** with live Rupee label (`₹0` to `₹1,50,000`).
- **Customer Rating Filter** (4★ & above, 3★ & above, All).
- **Flipkart Assured** filter toggle.
- **Sort options**: Popularity, Price (Low to High), Price (High to Low), Rating, and Biggest Discount.
- Active filter badges with one-click clear.

### 6. Product Catalog & Cards
- High quality product imagery with fallback placeholders.
- Wishlist heart button with state toggle.
- Flipkart Assured badge (`f-Assured`).
- Green rating pill with star icon.
- Strikethrough original MRP, discounted price, and calculated discount percentage.
- "Add to Cart" and "Details" (Quick View) buttons.

### 7. Interactive Shopping Cart Drawer
- Slide-over drawer with item listing.
- Quantity increment (`+`), decrement (`-`), and remove options.
- Dynamic **Price Details Breakdown**:
  - Total MRP
  - Discount amount
  - Delivery charges (FREE)
  - Final payable total
  - Total savings message
- Order placement action with feedback toast notification.
- Cart data persists in browser `localStorage`.

### 8. Product Details Quick View Modal
- Detailed specs breakdown, offer tags (bank offers, exchange discounts), and immediate "Add to Cart" / "Buy Now" actions.

### 9. 🛠️ CMS Web Content Authoring Simulator
- Click **"CMS Authoring"** in the header.
- **Add New Product**: Author a new title, category, price, discount, rating, and specs. It immediately injects into the live catalog!
- **Manage Banners**: Publish a custom hero banner with custom title, subtitle, and gradient theme.
- **Reset Catalog**: One-click restore back to default seed data.

---

## 📁 File Structure

```
flipkart-clone/
│
├── index.html        # Semantic HTML5 structure (Header, Nav, Carousel, Grid, Modals, Footer)
├── style.css         # Clean CSS3 stylesheets with variables, Grid, Flexbox, & Media Queries
├── script.js         # Pure Vanilla JavaScript engine (State, DOM, LocalStorage, Search, CMS)
├── server.js         # Lightweight local static server (Node.js built-in http)
├── DOCUMENTATION.md  # Comprehensive technical architecture & module manual
└── README.md         # Project overview and usage guide
```
