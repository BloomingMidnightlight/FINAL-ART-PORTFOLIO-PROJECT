# FINAL-ART-PORTFOLIO-PROJECT

Portfolio Website Summary

1. The website's Purpose and Theme
Purpose: The website serves as a portfolio for me (Sinai Hernandez), as a UX/UI Developer and Digital Artist. Its primary goal is to showcase both vibrant digital illustrations and technical web development projects. It almost acts as a digital business card and a creative space to attract opportunities for web development, UI/UX consultations, and custom art commissions.

Theme: The theme revolves around a "sleek dark aesthetic." It is a modern, immersive, and visually balanced simple look. By utilizing a dark backdrop with subtle, dynamic interactions (like the particles.js network), the theme creates an elegant, gallery-like atmosphere that makes the colorful digital art and project thumbnails pop without overwhelming the user.

2. Design Choices
Color Palette: The design relies on a neutral, deep dark baseline (Background: #050505, Cards: #111111) paired with crisp off-white (#f5f5f5) text for high readability. To add some personality and energy, vibrant accents are used strategically/specifically a bright blue (#00b4d8) and a purple (#9d4edd). These colors shine in interactive states, the particle background, and the dynamic "ombre" animated border under the welcome section.

Typography: A modern, highly legible pairing of Google Fonts is used. "Outfit" serves as the primary sans-serif body font, offering a clean and accessible reading experience. "Montserrat" is used for titles and hero text, providing a sophisticated, geometric structure that gives the site a premium, structured feel.

Layout: The layout is fully responsive and mobile-friendly, utilizing CSS Flexbox and Grid. The navigation features a clean, fixed header with a dropdown and a mobile toggle menu. The homepage introduces users through a structured flow: an animated hero, an introduction, a horizontal scrollable gallery preview carousel, and a grid for projects. This modular approach keeps the content organized and easy to digest across all device sizes.

3. Challenges Faced and How You Resolved Them
Challenge: Displaying artwork immersively without navigating away from the gallery.
Resolution: You implemented a custom JavaScript Lightbox. By capturing click events on the masonry gallery items, users can view high-resolution images in a modal. You further enhanced the UX by adding next/previous buttons, click-to-close functionality, and full keyboard support (Arrow keys and Escape).

Challenge: Making the site feel dynamic without being distracting or overwhelming.
Resolution: You replaced aggressive slide-in animations with subtle, elegant fades. You integrated an IntersectionObserver in JavaScript to trigger smooth fade-in animations on elements only as the user scrolls them into the viewport. Additionally, the particles.js background was configured to be lightweight and interactive without detracting from the main content.

Challenge: Maintaining a cohesive visual identity across different functional sections (like forms and FAQs).
Resolution: You strictly adhered to your CSS variables (custom properties) across all pages. For the contact form, you styled the inputs and textareas to blend perfectly with the dark card backgrounds and added focus states that highlight the brand's vibrant blue accent. For the FAQ, you built a custom JS-driven accordion that cleanly expands and collapses, keeping the UI uncluttered.
