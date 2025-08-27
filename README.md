# Niyantri — Coffee Shop Website

This is a simple, responsive multi-page website for a coffee shop called "Niyantri." It uses Tailwind CSS via the CDN and Google Fonts for typography. The site is intentionally full-width (no fixed max-width containers) and built to be mobile-friendly.

Files
- index.html — Home page with hero, menu, gallery, and newsletter signup.
- about.html — About page with story, team, founders (GSR & MRR), and philosophy.
- contact.html — Contact page with address, hours, map image placeholder, and contact form.

Design Notes
- All main wrappers use full-width classes (w-full, max-w-none) to ensure the layout fills the viewport width.
- Tailwind CSS is included via the CDN (https://cdn.tailwindcss.com) and the site uses Playfair Display for headings and Inter for body text. Each HTML file includes a comment with the Google Font names at the top for easy reference.
- Images use AI-managed placeholders in the format https://images.pexels.com/photos/6576745/pexels-photo-6576745.jpeg?auto=compress&cs=tinysrgb&h=650&w=940 so the system can fetch high-quality photos automatically. Replace placeholders if you prefer specific images.

Interactive Features
- Mobile nav toggle on the header.
- Menu filter (All / Espresso / Cold Brew / Pastries) implemented in vanilla JavaScript.
- Gallery lightbox modal.
- Newsletter and contact form simple validation and simulated submission with feedback.

How to use
1. Open any of the HTML files in a browser to view the site.
2. The image placeholders (e.g. https://images.pexels.com/photos/5722911/pexels-photo-5722911.jpeg?auto=compress&cs=tinysrgb&h=650&w=940) will be fetched by the image system. If you want to replace them manually, substitute each src with an actual image URL.

Customization
- Change colors in the tailwind.config section inside each HTML file.
- Modify menu items, prices, and images to match your shop's offerings.
- Add backend integration for forms if you want real submissions.

Notes
- This project uses client-side JS only; the forms simulate submission and do not send data to a backend. Integrate with a form backend or serverless function for production.
- All pages are linked with relative paths (./index.html, ./about.html, ./contact.html).

Cofounders
- GSR
- MRR

Enjoy building and customizing Niyantri!