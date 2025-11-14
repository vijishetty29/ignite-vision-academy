# ignite-vision-academy

Website design for Ignite Vision Academy

<p align="center">
  <img src="images/logo.png" alt="Ignite Vision Academy Logo" width="150">
</p>

# Ignite Vision Academy Website

A responsive, multi-page static website for an academic publishing and training academy. This site is built with pure HTML, CSS, and vanilla JavaScript, with no build tools or frameworks required.

## _Table of Contents_

- [About The Project](#about-the-project)
- [Key Features](#key-features)
- [File Structure](#file-structure)
- [Getting Started](#getting-started)
- [Technologies Used](#technologies-used)

---

## About The Project

This project is a clean, modern, and fully responsive website designed for **Ignite Vision Academy**. It serves as the academy's official online presence, detailing its academic initiatives, publishing services, and upcoming events.

The site is built with pure HTML and CSS, with a focus on a professional, "bookish" aesthetic using the 'Lora' and 'Roboto' fonts. It includes two main pages: the main landing page (`index.html`) and a separate book `catalog.html`.

---

## Key Features

- **Fully Responsive Design:** Features a mobile-friendly "hamburger" menu for seamless navigation on all devices.
- **Dynamic Hero Carousel:** The homepage greets users with a professional, auto-playing carousel (using Swiper.js) featuring 5 unique slides.
- **Interactive Carousels:** Utilizes Swiper.js for smooth carousels showcasing publications and past event flyers.
- **Two-Image Book Hover:** In the publications carousel and catalog, hovering over a book cover reveals a second image (e.g., the back cover).
- **Functional Contact Form:** The footer contains a contact form that securely sends submissions to an email address via the `FormSubmit.co` service.
- **Floating Action Buttons:** Sticky "Call" and "WhatsApp" buttons are present in the bottom-right corner for easy user contact.
- **Announcement Popup:** A modal window appears on page load to display "Upcoming Events".
- **Social Media Header:** A clean "social ribbon" sits at the top of the page with links to Facebook, Instagram, and YouTube.

---

## File Structure

The project uses a simple and clear file structure.

---

## Getting Started

This is a static website. No complex setup or build process is required.

1.  **Clone the repository (or download the files):**
    ```bash
    git clone [https://github.com/your-username/ignite-vision-academy.git](https://github.com/your-username/ignite-vision-academy.git)
    ```
2.  **Navigate to the folder:**
    ```bash
    cd ignite-vision-academy
    ```
3.  **Open the files:**
    Simply open `index.html` or `catalog.html` in your web browser to view the site.

### Activating the Contact Form

The contact form in the footer uses the **FormSubmit.co** service to send emails.

1.  Open the website in your browser.
2.  Fill out the contact form and submit it **for the first time**.
3.  Check the `ignitevisionacademy@gmail.com` inbox for an activation email from FormSubmit.
4.  **Click the activation link in that email.**

After this one-time activation, all future form submissions will be sent directly to your inbox.

---

## Technologies Used

- **HTML5:** For the core structure and content.
- **CSS3:** For all styling, layout (Flexbox/Grid), and animations.
- **JavaScript (Vanilla):** For the mobile navigation toggle and the announcement popup.
- **[Swiper.js](https://swiperjs.com/):** A modern JavaScript library used for all carousels (hero, publications, and flyers).
- **[FormSubmit.co](https://formsubmit.co/):** A free backend service to handle the HTML contact form submissions.
- **[Google Fonts](https://fonts.google.com/):** Used for the 'Lora' (headings) and 'Roboto' (body) typefaces.
