# 💼 Professional Portfolio Website Using Flex CSS

This project demonstrates how to build a professional and responsive portfolio website using **CSS Flexbox**. It includes clean layouts, responsive columns, skill bars, and adaptive design for mobile.

---

## 🌐 Live Preview

<p align="center">
  <img src="https://github.com/rohitash-eng/professional-portfolio-website-using-flex/blob/main/images/professional-portfolio-website-using-flex.png?raw=true" alt="Portfolio Preview" width="700"/>
</p>

---

## 📘 What We Have Learned in Flex CSS Using This Tutorial

This tutorial demonstrates the use of various **Flexbox CSS properties** to create a responsive, professional layout. Below is a list of all the Flex properties used, with explanations.

### 💡 Flex Container Properties

| Property                | Description                                                                 | Why We Use It                                                                 |
|------------------------|-----------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| `display: flex`        | Converts an element into a flex container.                                 | To enable flexible, responsive layout of child elements.                      |
| `flex-direction: row`  | Arranges flex items horizontally (default).                                | Used implicitly for horizontal layouts.                                       |
| `flex-direction: column` | Stacks flex items vertically.                                              | Useful for vertical sections like `.main-continer` and `.right-section`.     |
| `justify-content: center` | Aligns items along the main axis (horizontal or vertical).                | Used in `.header-box` to center content horizontally.                         |
| `align-items: center`  | Aligns items along the cross axis.                                          | Used in `.footer`, `.heading-wrapper` for vertical centering.                |
| `gap`                  | Adds spacing between flex items.                                            | Used for consistent spacing in `.header-box`, `.exp-wrapper`, etc.           |
| `flex: 1`              | Allows a flex item to grow and fill remaining space.                        | Used in `.header-box` to fill vertical space with `min-height`.              |

### 💡 Flex Item Properties

| Property                | Description                                                                | Why We Use It                                                                 |
|------------------------|-----------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| `flex-basis: 100%`     | Sets the initial size of a flex item before growing/shrinking.              | Used in `.white-div` to allow full-width bars.                                |
| `width: 33.33%` / `66.66%` | Manually sets column widths in flex layout.                              | Used in `.left-bar` and `.right-section` to define layout split.             |
| `flex-direction: column` | Applies column stacking for child items.                                  | Used in multiple wrappers for vertical stacking like `.right-section`.        |

### 📱 Media Query with Flexbox

| Media Query Example                    | Description                                  | Why We Use It                                                                  |
|----------------------------------------|----------------------------------------------|---------------------------------------------------------------------------------|
| `@media screen and (max-width: 480px)` | CSS for small screens (like mobile)          | To make `.header-box`, `.left-bar`, and `.right-section` responsive.          |
| `flex-direction: column`               | Stacks elements vertically on small screens  | Applied inside media query for mobile layout.                                 |
| `width: 100%`                          | Makes columns span full width on mobile      | Used for `.left-bar` and `.right-section` inside media query.                 |

---

## 🔗 Live Demo

➡️ [View Portfolio Live](https://github.com/rohitash-eng/professional-portfolio-website-using-flex/blob/main/images/professional-portfolio-website-using-flex.png?raw=true)

---

## 🧑‍💻 Author

**Rohtash Singh**  
Frontend Developer | CSS Flexbox Enthusiast

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
