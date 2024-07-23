## Mortgage Calculator Style Guide

This style guide outlines the conventions and best practices used for the CSS code in the mortgage calculator project.

**General Principles:**

* **Clarity and Maintainability:** Strive for clean, well-organized code that is easy to understand and modify. Use meaningful class names and comments to explain your choices.
* **Specificity:** Use specific selectors to target the desired elements and avoid unintended side effects.
* **Consistency:** Maintain consistent formatting (indentation, spacing) and naming conventions throughout the stylesheet.
* **Responsiveness:** Ensure the layout adapts seamlessly to different screen sizes using media queries.

**Naming Conventions:**

* Use lowercase letters with hyphens (kebab-case) for class names (e.g., `left-side`, `input-group`).
* Consider using more descriptive names for complex classes to improve readability (e.g., `clear-all-text`, `half-input-container`).
* Avoid overly generic class names like `custom` or `important`.

**Formatting:**

* Indent code blocks consistently (usually 2 spaces per level).
* Add spaces around selectors and property names for better readability.
* Use comments to explain complex logic or non-obvious choices.

**Specific Styles:**

* **Base Styles:** Define basic styles for elements like `body`, `h1`, `p`, and `button` to establish a consistent foundation.
* **Layout:** Use classes and grids to structure the layout (e.g., `.container`, `.left-side`, `.right-side`).
* **Form Elements:** Style form elements like inputs, labels, and buttons for clarity and usability (e.g., `.input-group`, `.radio-group`).
* **Typography:** Choose appropriate font families, sizes, and colors for headings, text, and labels.
* **Colors:** Define a color palette and use consistent colors for backgrounds, text, and borders.
* **Responsiveness:** Use media queries to adjust styles for different screen sizes (e.g., adjust padding, font sizes for smaller screens).

**Tools and Resources:**

* Consider using a CSS preprocessor like Sass or LESS for features like variables, mixins, and nesting (optional).
* Utilize browser developer tools to inspect and fine-tune styles.

**Conclusion:**

Following this style guide will help maintain a clean, consistent, and well-documented CSS codebase for the mortgage calculator project, making it easier to understand, maintain, and enhance in the future.

# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

> 💡 These are just the design sizes. Ensure content is responsive and meets WCAG requirements by testing the full range of screen sizes from 320px to large screens.

## Colors

### Primary

- Lime: hsl(61, 70%, 52%)
- Red: hsl(4, 69%, 50%)

### Neutral

- White: hsl(0, 0%, 100%)
- Slate 100: hsl(202, 86%, 94%)
- Slate 300: hsl(203, 41%, 72%)
- Slate 500: hsl(200, 26%, 54%)
- Slate 700: hsl(200, 24%, 40%)
- Slate 900: hsl(202, 55%, 16%)

## Typography

### Body Copy

- Font size (paragraph): 16px 

### Font

- Family: [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans)
- Weights: 500, 700

> 💎 [Upgrade to Pro](https://www.frontendmentor.io/pro?ref=style-guide) for design file access to see all design details and get hands-on experience using a professional workflow with tools like Figma. The design file for this challenge also includes a design system and tablet layout to help you build a more accurate solution faster.
