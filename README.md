Personal Portfolio Website - README
Overview
This project is a personal portfolio website designed to showcase my skills, services, and portfolio. It highlights my expertise as a UI/UX Designer, Web Developer, and Data Analyst while offering an interactive and user-friendly interface for visitors to learn more about my professional background, services, and contact information.

Features
Responsive Design: Optimized for different screen sizes (mobile, tablet, desktop).
Interactive Navigation: Custom side menu with smooth open/close animations.
Tabbed Content: Sections for skills, experience, and education.
Service Highlights: Detailed information on the services I offer.
Portfolio Section: A showcase of previous projects.
Contact Form: Integrated with Google Sheets for easy submission and management of inquiries.
Social Links: Quick access to GitHub, LinkedIn, WhatsApp, and X (formerly Twitter).
Structure
HTML
Defines the overall structure and layout, with sections for the header, about me, services, portfolio, and contact form.
CSS
Linked external stylesheet (style.css) for layout, styling, and responsive design.
FontAwesome icons for navigation and services are integrated via a CDN.
JavaScript
Navigation Menu: JavaScript functions to open and close the side menu.
Tabbed Section: JavaScript functionality for switching between tabs (skills, experience, education).
Google Sheets Integration: A script that connects the contact form to Google Sheets for easy message storage.
File Structure
index.html: Main HTML file.
style.css: External CSS file for styles (linked in the <head>).
images/: Directory for logos, profile pictures, and portfolio images.
fa-icons: FontAwesome icons via CDN for enhanced visual elements.
Instructions
How to Use
Clone the Repository:


Access my portfolio through: https://edelbert08.github.io/main-portfolio/


Customization:

Update the content in the index.html file for your details, services, and portfolio items.
Replace the placeholder images in the images/ folder with your own.
Contact Form Integration
The form submissions are handled via a Google Apps Script that stores the responses in a connected Google Sheet.
To set up your own form submission:
Modify the scriptURL with your own Google Apps Script URL.
Ensure that your Google Sheet has the correct column headers to store the form data.
Credits
FontAwesome: For the icons used throughout the website.
Google Sheets: For handling form submissions.
License
This project is open-source and free to use. Feel free to adapt or modify it as per your needs.
