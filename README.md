# **Comic Book Creations — Charismatica**

A front-end web project designed to present original comic content under the brand **Charismatica**, featuring a responsive homepage, comic reader, multi-page navigation, and a modern UI modeled after professional comic platforms.

## **Project Link**
```
https://6910e4e610ffe599364ad08c--gleeful-torrone-b6458a.netlify.app/
```
---
## **📌 Note on Commit History**

The project was primarily developed locally. I encountered a few delays related to file size and intermittent internet stability, which affected the timing of when I was able to push updates. Although I initially planned to commit more frequently, additional incremental commits would not have added meaningful value in this context, since the work was completed independently rather than collaboratively. Once the issues were resolved, I pushed the completed set of changes together.
---

## **📁 Project Structure**

```
Comic-Book-Creations/
│
├── index.html
├── comics.html
├── reader.html
│
├── styles/
│   ├── main.css
│   ├── header.css
│   ├── footer.css
│   └── reader.css
│
├── assets/
│   ├── logo/
│   ├── covers/
│   └── pdf/
│
└── README.md
```

---

## **🌐 Pages Overview**

### **1. Home Page — `index.html`**

* Header with logo, login/signup bar, navigation, and search placement
* Hero section with brand-matching typography
* Featured comics grid

  * 2:3 tile ratio
  * Title & year overlays
  * Hover scaling
  * Responsive (4 → 3 → 2 → 1 columns)
* “Show More” button leading to full comic list
* Full footer with multi-column layout and legal links

---

### **2. Comics Listing — `comics.html`**

* Expanded grid of all comics
* Same card component for visual consistency
* Responsive layout for all screen sizes
* Links into `reader.html`

---

### **3. Comic Reader — `reader.html`**

* Centered PDF viewer
* Minimal UI (when supported by browser)
* Consistent header + footer layout
* Responsive height and spacing using media queries
* Designed for a clean, uninterrupted reading experience

---

## **🎨 Design & Styling**

* CSS Grid for layouts
* Flexbox for alignment
* Media queries for full responsiveness
* Hover animations and overlays
* Brand logo integrated into header and footer
* Dark theme with accent colors matching the Charismatica identity

---

## **🛠️ Technologies Used**

* HTML5
* CSS3 (Flex, Grid, Transitions, Media Queries)
* JavaScript (variables, events, simple functions, animation logic)

---

## **📥 Running the Project**

### **Option 1 — Open directly**

Simply open `index.html` in a browser.

### **Option 2 — Recommended (for PDF viewing)**

Run a lightweight local server:

```
python -m http.server 8000
```

Then open:

```
http://localhost:8000
```

---

## **🚀 Future Improvements**

* Fully functional search bar (JavaScript filtering)
* Auto-advancing hero slider
* JSON-based comic loading
* Light/Dark mode toggle
* Page-to-page smooth transitions

---

## **👤 Author**

**Rohan Prathap Reddy**
GitHub: [https://github.com/vrohan999](https://github.com/vrohan999)
