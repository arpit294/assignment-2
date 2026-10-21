# 🚀 Assignment 2: Elementor Mini Website

> **Course Assignment:** WordPress Tutorials – Assignment 2  
> **Topic:** Multi-Page Elementor Mini Website (Home, About, Contact) with Hero Slider & Widgets  
> **Student / Author:** arpit294  
> **Reference Document:** [Assignment 2 Google Doc](https://docs.google.com/document/d/1cdPBE6ZieYSWUcXYsnZ45zs0VJ3HYQuJHky2ffdKuoQ/edit?tab=t.0#heading=h.jzv7vxm7kcj0)

---

## 🎯 Objective
Understand and apply multi-page architecture, header navigation menus, hero sliders, Elementor widgets, and responsive design using Elementor Free.

---

## 🌐 Website Type
- **Category:** Business / Professional Agency & Portfolio Website
- **Theme:** Modern, responsive, and interactive.

---

## 🛠 Tasks & Implementation Breakdown

### 📄 1. Pages Requirement (Minimum 3 Pages)
The website comprises three fully developed pages:
1. **🏠 Home Page (`/home`):**
   - Features the Hero Slider, widget showcase sections, and conversion callouts.
2. **ℹ️ About Page (`/about`):**
   - Company background, mission, milestones, team overview, and core values.
3. **📞 Contact Page (`/contact`):**
   - Interactive inquiry form (WPForms), business address, phone, email, and location map.

---

### 🧭 2. Header Navigation Menu
- Dynamic header menu visible on **all pages**.
- Accurately links: **Home** | **About** | **Contact**.
- Styled with responsive mobile drawer/hamburger navigation.

---

### 🎞 3. Home Page Hero Slider
- Built using **Smart Slider 3** / Elementor Slider.
- Contains **multiple slides** with smooth animated transitions.
- Located prominently in the Hero Section of the Home page with headlines, subheadings, and Call-to-Action buttons.

---

### 🧩 4. Elementor Widgets Usage (Minimum 4 Distinct Widgets)
In accordance with the assignment guidelines, at least four distinct Elementor widgets are integrated:
- ⭐ **Testimonials Widget:** Client reviews and social proof.
- 🔢 **Counter Widget:** Live stats and completed project milestones.
- 📊 **Progress Bar Widget:** Service skills and delivery efficiency.
- 📋 **Icon List Widget:** Key feature highlights and bulleted service benefits.

---

### 📱 5. Mobile & Tablet Responsiveness
- Full responsiveness across **Mobile**, **Tablet**, and **Desktop** screens.
- Automatic column stacking for cards and text blocks.
- Optimized touch targets, readable font scaling, and smooth navigation toggles.

---

## 📂 Repository Contents
```text
├── assignment2_database.sql   # Full MySQL database export for Assignment 2
├── assignment2.docx           # Assignment submission document
├── assignment2.rtf            # Screenshots and notes document
├── wp-content/
│   ├── plugins/
│   │   ├── elementor/         # Elementor Page Builder (Free)
│   │   ├── smart-slider-3/    # Slider Plugin for Hero Section
│   │   ├── wpforms-lite/      # Contact Forms
│   │   ├── header-footer-elementor/
│   │   ├── premium-addons-for-elementor/
│   │   └── classic-editor/
│   ├── themes/
│   │   └── astra/             # Astra Lightweight Theme
│   └── uploads/               # Project images, slider graphics & assets
├── wp-config.php              # Local WordPress configuration
├── index.php
└── README.md                  # Comprehensive project documentation
```

---

## ⚙️ Installation & Setup (Laragon / Localhost)

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/arpit294/assignment-2-elementor-mini-website.git
   ```
   *(Or place into your `laragon/www/assignment-2-elementor-mini-website` directory)*

2. **Database Setup:**
   - Create a MySQL database (e.g. `assignment2_db` or `word`).
   - Import `assignment2_database.sql`:
     ```bash
     mysql -u root -p assignment2_db < assignment2_database.sql
     ```

3. **Configure `wp-config.php`:**
   ```php
   define( 'DB_NAME', 'assignment2_db' );
   define( 'DB_USER', 'root' );
   define( 'DB_PASSWORD', '' ); // or your password
   define( 'DB_HOST', 'localhost' );
   ```

4. **Launch the Website:**
   - Open browser: `http://localhost/assignment-2-elementor-mini-website`

---

## 📸 Submission Files
- Documentation & screenshots included: **`assignment2.docx`** and **`assignment2.rtf`**
