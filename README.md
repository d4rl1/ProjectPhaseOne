# ProjectPhaseOne
This is a multi-page static website for a fictional skateboard shop. The project is built with semantic HTML, modern CSS (using Flexbox, Grid, and variables), and JavaScript to create a modular header and footer.

✨ Features
Homepage (index.html): A welcoming landing page with a large hero image, an overlay, and a clear call-to-action button.

About Page (about.html): A detailed "Our Story" page featuring a hero image and a two-column layout for text and images.

Contact Page (contact.html): A "Hit Us Up" page with a two-part grid layout, including a contact form and a contact info widget.

Dynamic Header/Footer: Uses JavaScript (load-header.js, load-footer.js) to fetch and inject the header and footer into the about.html and contact.html pages, avoiding code repetition.

CSS Theming: Uses CSS variables (:root) to manage the entire site's color scheme from one place.

💻 Technologies Used
HTML5: Semantically structured.

CSS3: Styled with modern CSS, including:

CSS Flexbox (for alignment in the header, footer, and hero content)

CSS Grid (for the two-column contact page layout)

CSS Variables (for easy management of the site-wide color theme)

JavaScript (Vanilla): Used to fetch and inject the global header and footer components for a "Single Page Application" feel.

🚀 How to View This Project
IMPORTANT: This project uses the JavaScript fetch() API to load the header and footer. Due to browser security policies (CORS), it will not work if you just double-click and open the index.html file in your browser (i.e., from a file:///... address).

You must run it on a local server. The easiest way is with the "Live Server" extension in VS Code.

Recommended Method (VS Code)
Open the project folder in Visual Studio Code.

If you don't have it, install the "Live Server" extension from the marketplace.

Right-click on index.html in the file explorer.

Select "Open with Live Server".

This will open the site in your browser on a local server (like http://127.0.0.1:5500), and the header and footer will load correctly.
