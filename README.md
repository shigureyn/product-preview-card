# Frontend Mentor - Product Preview Card Component

This is my solution to the [Product Preview Card Component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Overview

### The challenge

Users should be able to:

* View the product card layout on different screen sizes
* See hover and focus states for interactive elements
* Use the page comfortably on mobile and desktop devices

### Screenshot

![Project screenshot](images/screenshot.jpg)

### Links

* Solution URL: [GitHub Repository](https://github.com/shigureyn/product-preview-card)
* Live Site URL: [Live Site](https://shigureyn.github.io/product-preview-card/)

## My process

### Built with

* Semantic HTML5 markup
* CSS custom properties
* Flexbox
* CSS Grid
* Mobile-first workflow
* Google Fonts
* BEM-style class naming

### What I learned

During this project, I practiced building a responsive product card using a mobile-first approach. I also improved my understanding of CSS custom properties, typography, spacing, and component-based class naming.

One important part of the project was using CSS variables for colors and fonts:

```css
:root {
  --font-main: "Montserrat", Arial, sans-serif;
  --font-accent: "Fraunces", Georgia, serif;

  --color-green-500: hsl(158, 36%, 37%);
  --color-green-700: hsl(158, 42%, 18%);
  --color-black: hsl(212, 21%, 14%);
  --color-grey: hsl(228, 12%, 48%);
  --color-cream: hsl(30, 38%, 92%);
  --color-white: hsl(0, 0%, 100%);
}
```

I also practiced creating a responsive card layout:

```css
.product-card {
  width: 100%;
  max-width: 343px;
  overflow: hidden;
  background-color: var(--color-white);
  border-radius: 10px;
}
```

### Continued development

In future projects, I want to continue improving:

* Responsive layouts
* Mobile-first workflow
* Semantic HTML structure
* Accessibility and focus states
* Clean CSS organization
* Better image handling with the `picture` element

### Useful resources

* [Frontend Mentor](https://www.frontendmentor.io/) - The platform where I found this challenge.
* [Google Fonts](https://fonts.google.com/) - Used for the Montserrat and Fraunces fonts.
* [MDN Web Docs](https://developer.mozilla.org/) - Helpful documentation for HTML and CSS.

### AI Collaboration

I used ChatGPT during this project as a learning assistant. It helped me understand how to structure the HTML, organize CSS, use CSS variables, connect Google Fonts, and improve the mobile-first layout.

I reviewed and adjusted the suggested code myself to better understand how each part works.

## Author

* GitHub - [@shigureyn](https://github.com/shigureyn)
* Frontend Mentor - [@shigureyn](https://www.frontendmentor.io/profile/shigureyn)
