# PawCare — Dog Care Website

This project is a small multi-page static website for a fictional dog care service called "PawCare." It contains three core pages and uses Tailwind CSS utility classes directly in the HTML for styling. All main content stretches the full width of the viewport to satisfy a fluid, full-bleed layout requirement.

Files
- index.html — Home page with hero, service cards, testimonials carousel, and CTA banner.
- about.html — Company mission, team, community & safety details.
- contact.html — Contact form with client-side validation, contact details, and map placeholder.

Design & Features
- Tailwind CSS (via CDN) is used throughout with classes applied directly in the markup.
- Google Fonts included: Poppins and Merriweather. (References are included in the HTML; the top of each HTML file also includes a comment of the form required by the generator: `{{font: Font Name}}`.)
- All main wrappers use `w-full` and `max-w-none` to ensure full-width content on all devices.
- Responsive grid layouts, mobile-first design, and interactive elements (buttons, simple testimonial carousel, and form validation) are implemented with JavaScript.
- Images are placeholders using the special `https://images.pexels.com/photos/3912509/pexels-photo-3912509.jpeg?auto=compress&cs=tinysrgb&h=650&w=940` format. These will be fetched automatically by the hosting system if supported. If you have images you'd like to use, provide them in the expected upload format and they will be integrated directly.

How to use
1. Download the files and open `index.html` in your browser. Use the navigation to access About and Contact pages.
2. To connect the contact form to an actual backend or email service, replace the fake submission logic in `contact.html` with your API call.

Customization
- Colors, fonts, and spacing can be adjusted via Tailwind utility classes directly in the HTML.
- To localize or update images: replace the `src` of `<img>` tags with real image URLs or base64 data URIs.

Notes
- This is a static, client-side website suitable for simple deployments (Netlify, Vercel, GitHub Pages, etc.).
- The testimonials carousel and contact form use minimal JS for clarity and can be extended into more advanced components as needed.

If you'd like additional pages (pricing, blog, booking calendar) or integration with a booking API, tell me what features you want and I can extend the project.