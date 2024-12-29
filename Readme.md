# Nonprofit XD Project

This repository contains the implementation of the **Nonprofit XD Freebie Design**. The goal is to create a responsive, clean, and accessible web structure for a nonprofit organization.

## 📂 Folder Structure

The project is organized as follows:

-   **`/assets/`**: Contains image and media assets organized by pages.
-   **`/pages/`**: HTML files for each specific page (e.g., About Us, Donation).
-   **`/styles/`**: CSS files for structural and reusable styles.

## 🎯 Design Goals and Guidelines

### General Pointers

1. **Work Mobile-First**: Start with mobile layouts and progressively enhance for larger screens (tablet, desktop).
2. **Use Flexbox & Grid**: Emphasize layout flexibility and responsiveness using `flexbox` and `grid`.
3. **Common and Structural CSS**:
    - Create a shared `styles.css` for reusable style classes.
    - Separate page-specific structural CSS for unique elements.
4. **Step-by-Step Development**:
    - Develop section by section and element by element.
    - Focus on layout first, styling details second.

### CSS-Specific Tips

-   Always make mobile resolution work first, then tablet, and finally desktop.
-   Prioritize "in-the-flow" positioning. Use "out-of-flow" (`absolute`, `fixed`) only when necessary.
-   Use **rem** for font sizes for better accessibility.
-   Limit width and height definitions; use percentages inside containers.
-   Link all pages for navigation purposes.

## 📋 Development Notes

### 1. Common CSS (`styles.css`)

-   Add reusable styles like fonts, colors, buttons, and layout utilities.

### 2. Page-Specific Structural CSS

-   Each page should include its structural CSS for layouts and unique content.

### 3. Responsive Design Strategy

-   Design for small screens first and scale up with media queries (`@media`).

### 4. Navigation

-   Link all pages to allow seamless navigation between them.

## 🌐 References

-   [Nonprofit XD Freebie Design](https://nonprofit-xd-freebie.webflow.io/)
-   [Project Assets](https://drive.google.com/drive/folders/1raP7YpOF4knQnX7UWOYJYoTU4KSGJAyy)

## 🛠️ To Do

1. Add README.md and `.gitignore` files to your repository.
2. Organize `assets` by page for easier navigation.
3. Start implementing sections starting with the homepage.

## 🚀 How to Run

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
