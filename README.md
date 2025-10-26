# 📱 Make a Website Mobile-Friendly Using CSS Media Queries

## 🏁 Objective
The goal of this task is to **convert an existing desktop-only webpage into a mobile-friendly layout** using **CSS media queries**.  
This ensures that the website adjusts automatically for different screen sizes — especially mobile and tablet devices.

---

## 🧠 Features Implemented
- ✅ Responsive design using **CSS media queries**
- ✅ Layout automatically adapts for smaller screens (below 768px)
- ✅ Flexible and readable text and images
- ✅ Navigation bar stacks vertically on mobile
- ✅ Tested using Chrome DevTools (mobile view)

---

## 🧰 Tools Used
- **HTML5**  
- **CSS3 (with media queries)**  
- **VS Code**  
- **Chrome DevTools**

---

## 🧩 Steps to Implement
1. Open the existing HTML file in **VS Code**.
2. Add a **viewport meta tag** in the `<head>` section:
   ```html
   <meta name="viewport" content="width=device-width, initial-scale=1.0" />
Identify elements with fixed widths or large images.

Write media queries targeting max-width: 768px in your CSS file:

@media (max-width: 768px) {
  body {
    font-size: 16px;
  }
  .container {
    flex-direction: column;
    align-items: center;
  }
  img {
    width: 100%;
  }
}


Test the responsiveness in Chrome DevTools → Toggle Device Toolbar (📱 icon).

Fix any overflow or alignment issues until the page looks clean on mobile.

🧩 Sample Output (Expected)
Device	Layout
🖥️ Desktop	Two sections side by side
📱 Mobile	Sections stacked vertically
🖥️ Navbar	Horizontal
📱 Navbar	Vertical
🧾 Deliverables

Updated CSS file with media queries.

Working webpage that is responsive on mobile devices.

GitHub repository link submitted via the provided submission form.

🧭 Outcome

By completing this task, you will:

Understand media queries and responsive web design.

Learn mobile-first design principles.

Be able to build flexible layouts that adapt to any screen size.

🧩 Key Concepts

Media Queries

Responsive Web Design

Viewport Meta Tag

CSS Units (%, rem, vw)

Flexbox and Grid in Responsive Layouts
