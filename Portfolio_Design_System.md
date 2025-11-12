# 🎨 **Portfolio Resume Design System**

This documentation outlines the updated design system for the **portfolio resume project**, reflecting the latest additions

---

## **1. Color Palette**
| Purpose | Color | Description |
|----------|--------|-------------|
| **Primary (Navy)** | `#0a2a66` | Used for headings, borders, and navigation links |
| **Text Color** | `#333` | Standard readable dark gray for content |
| **Background** | `#f5f0e6` | Soft beige for contrast and elegance |
| **Card Background** | `#fff` | Clean white for content sections |
| **Border Color** | `#ccc` | Subtle borders for experience cards |

---

## **2. Typography**
- **Body Text:** `Arial, sans-serif` (modern, readable, professional)  
- **Headers:** `"Times New Roman", serif` (adds classic elegance to titles)

---

## **3. Components and Layout**

### **Header**
- **Design:**  
  Centered name (“Mosheera Ahmed”) with a navy underline. Contact info is navy and bold, and the email is clickable.  
  The **monogram logo (MA)** is positioned on the **top-right corner**, scaling responsively on all devices.
- **Mock-up Screenshot:**  
  ![Header Mock-up](header.png)

---

### **Navigation**
- **Links:** Education • Skills • Experience • Contact • **Yatzy Game**  
- Links use the primary navy color, bold weight, and underline on hover for interactivity.

---

### **Section Title**
- **Design:** Serif `h2` headings with a navy underline separating sections clearly.  
- **Mock-up Screenshot:**  
  ![Section Title Mock-up](section-title.png)

---

### **Skills Grid**
- **Design:** Responsive 4-column layout that automatically shrinks to 2 columns (tablet) or 1 column (mobile).  
- Each skill appears inside a white, bordered mini-card for readability.  
- **Mock-up Screenshot:**  
  ![Skills Grid Mock-up](skills-grid.png)

---

### **Experience Card**
- **Design:** White card with navy border, subtle shadow, and rounded corners.  
- Job titles use serif font for distinction; bullet points use `Arial` for clarity.  
- **Mock-up Screenshot:**  
  ![Experience Mock-up](experience-card.png)

---

### **Yatzy Game Project Card**
- **Design:** Consistent with experience cards (same border, padding, and typography).  
- **Purpose:** Highlights technical achievement and project-based learning.  
- **Content Example:**
  - Built a browser-based Yatzy game using **HTML5, CSS, and JavaScript (ES6 modules)**.  
  - Implemented object-oriented classes (`Dice`, `YatzyEngine`, `YatzyGame`) and game logic (straights, full house, bonuses).  
  - Designed modular architecture separating UI and logic, supporting future **client-server** upgrades.  
- **Mock-up Screenshot:**  
  ![Yatzy Game Mock-up](yatzy-game.png)

---

### **Links**
- **Design:** Bold navy color with underline on hover.  
- Used for email, phone, and GitHub at the footer for direct navigation.  
- **Mock-up Screenshot:**  
  ![Links Mock-up](links.png)

---

## **4. Responsiveness**
- Header logo resizes dynamically with `clamp()` in CSS for smooth scaling.  
- Skills grid adjusts automatically: **4 → 2 → 1 columns** depending on device width.  
- Layout remains centered and consistent across all screen sizes.  
- **Mock-up Screenshot:**  
  ![Responsiveness Mock-up](responsive.png)

---

## **Conclusion**
This document represents the finalized design language of my **personal resume website**.  
It integrates professional layout design, modular structure, responsive scaling, and my **Yatzy Game** project — ensuring a cohesive, elegant, and technically expressive digital portfolio.
