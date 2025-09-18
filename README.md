# NSBLPA Website Prototype

This repository contains a responsive, mobile-first prototype for the NSBLPA (National Sales & Business Leadership Professionals Association) website. The design is inspired by professional sports league websites like NFL.com, focusing on clean typography, a robust grid system, and an engaging user experience.

## How to Run the Prototype Locally

This prototype is built with static HTML, CSS (Tailwind CSS via CDN), and minimal JavaScript. No complex build tools or server-side setup are required.

1.  **Clone the repository (if applicable):**
    ```bash
    git clone <repository-url>
    cd nsblpa-prototype
    ```
    *(Note: If you received these files directly, skip this step.)*

2.  **Open the files in your web browser:**
    Navigate to the directory where you have saved the `index.html` file. You can simply open `index.html` directly in your web browser (e.g., by double-clicking it).

    To view other pages, open `ownership.html`, `teams.html`, `apps.html`, and `contact.html` in the same manner.

    For a more robust local development experience (especially if you encounter issues with relative paths or certain browser security features), you can use a simple local web server. If you have Python installed, you can run:
    ```bash
    python -m http.server 8000
    ```
    Then, open your browser and go to `http://localhost:8000`.

## Assumptions and Design Decisions

*   **Mobile-First & Responsive:** The prototype is designed with a mobile-first approach, utilizing Tailwind CSS to ensure responsiveness across various screen sizes.
*   **Inspiration:** The overall aesthetic and structural organization draw inspiration from professional sports league websites like NFL.com and FVNSport.com, aiming for a clean, modern, and professional look.
*   **Technology Stack:**
    *   **HTML5:** For semantic structure.
    *   **Tailwind CSS (CDN):** Used for rapid UI development and responsive styling without the need for a build process.
    *   **Vanilla JavaScript (ES6):** Included for potential future interactivity, though current content changes did not require significant JS modifications.
*   **Content Structure:**
    *   **Hero Sections:** Each main page (`index.html`, `ownership.html`, `teams.html`, `apps.html`, `contact.html`) features a prominent hero section with a relevant background image and a clear title/tagline.
    *   **Grid Layouts:** Content is organized using CSS Grid for clear, structured presentation (e.g., team listings, app cards, ownership tiers).
    *   **Navigation:** A consistent header navigation is present across all pages, with a mobile-friendly toggle.
*   **Accessibility:** Efforts were made to include semantic HTML5 elements, `alt` attributes for images, and `aria` attributes for interactive elements (like the mobile menu button) to improve accessibility.
*   **Form Functionality (Contact Page):** The contact form uses a `mailto:` action for basic functionality. For a production environment, this would require a backend service to handle submissions securely and reliably.

## Assets Used

All assets are located in the `assets/` directory.

*   **`styles.css`:** Custom CSS for minor overrides and specific styles not covered by Tailwind.
*   **`scripts.js`:** Placeholder for custom JavaScript. Currently, it contains basic functionality for the mobile navigation toggle.
*   **`images/`:**
    *   **Placeholder Images:** For team logos, owner profiles, and app icons, `picsum.photos` URLs are used to provide diverse and visually appealing placeholders.
        *   *Note:* To replace these with your own local images, place your image files (e.g., `team-logo.png`, `owner-profile.jpg`, `app-icon.png`) in the `assets/images/` directory and update the `src` attributes in the respective HTML files to point to these local paths (e.g., `src="assets/images/team-logo.png"`).
    *   **Banner Images:** Hero section background images are sourced from `unsplash.com` or `picsum.photos` for visual appeal.
        *   *Note:* Similar to placeholder images, these can be replaced with local images by placing them in `assets/images/` and updating the `style="background-image: url(...)"` attribute.
*   **Logos:** The main NSBLPA logo in the header uses a `placehold.co` URL. This can be replaced with an actual logo image by placing it in `assets/images/` (or `assets/logos/`) and updating the `src` attribute in `header` section of all HTML files.

---
