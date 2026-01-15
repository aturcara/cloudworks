# Project Overview

This project is a static responsive website design portfolio by Mohammad Hafiz, showcasing various web projects developed between 2019 and 2026. The website is built using standard web technologies: HTML for structure, CSS (including Typekit for custom fonts) for styling, and JavaScript for interactive elements. It features a main page (`index.html`) that lists individual projects with descriptions and direct links to their live deployments. All associated image assets are stored in the `src/img` directory.

# Building and Running

As a static HTML, CSS, and JavaScript project, there are no complex build steps or dependencies.

*   **To run locally:** Simply open the `index.html` file directly in any modern web browser.
*   **To deploy:** Host the entire project directory on any static web server (e.g., Apache, Nginx, GitHub Pages).

# Development Conventions

*   **Project Structure:**
    *   `index.html`: The main entry point for the website.
    *   `src/css/index.css`: Contains the primary custom styles for the website.
    *   `src/js/index.js`: Contains custom JavaScript for interactive functionalities.
    *   `src/img/`: Stores all image assets used throughout the portfolio.
    *   `src/css/use.typekit.net/` and `src/use.typekit.net/`: Contains Typekit-related font files and stylesheets.

*   **Styling:** The project utilizes custom CSS for layout and visual design, complemented by web fonts loaded via Typekit for typography.
*   **External Links:** All links to external project websites are configured to open in new browser tabs (`target="_blank"`).
*   **Accessibility:** `aria-label` attributes are used for external links to improve accessibility.
