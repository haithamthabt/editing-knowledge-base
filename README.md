# Editing Knowledge Base
## Overview
This repository hosts a website using **GitHub Pages** using Jekyll and **Minimal theme**.

## Theme Used
The site uses the **Minimal theme** provided by GitHub Pages. Customizations have been made to the theme to meet specific needs.

## Steps Taken

1. **Creating the Website:**
   - This website is hosted on **GitHub Pages** and is structured using Jekyll, a static site generator built into GitHub Pages.

2. **Customizing the Layout:**
   - A custom layout was created by copying the default theme's `default.html` file to the `_layouts` directory. This allowed for direct modifications while retaining the original theme’s structure and styling.
     - File created: `_layouts/default.html`

3. **Custom Footer Addition:**
   - The footer was modified to display custom content, such as copyright information.

## Key Notes for Customization

- **Maintaining Theme Styling**:
  - The `default.html` file was copied to `_layouts` and modified without removing the default elements to maintain the overall theme style.
  - Default styling and scripts were kept intact using Jekyll's `{{ content }}` tag, `{% include %}`, and other built-in features.
  
- **Additional Customizations**:
  - Further customization can be done by modifying `_includes` files (if applicable), CSS styles in `assets/css/`, or by adding more custom layout files as needed.

## Reminders for Future Updates

- **Custom Scripts and Styles**: Additional JavaScript or CSS customizations can be added in the `assets/` directory and linked within `_layouts/default.html`.
