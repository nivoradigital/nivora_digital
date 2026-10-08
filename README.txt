NIVORA DIGITAL - STATIC WEBSITE
===============================

A simple, fast, single-page website for Nivora Digital (Amazon seller services).
No build step and no dependencies. It works on any static host (GitHub Pages, Netlify, cPanel, etc.).
To view it, double-click index.html.

FILES
-----
index.html     Main page: header, hero, about, services, how we work, call-back form, contact, footer
privacy.html   Privacy Policy
terms.html     Terms & Conditions
styles.css     All styling (colours are CSS variables at the top of the file)
assets/
  logo.svg     Your Nivora Digital logo (about section and footer). It wraps the same
               image as logo.jpg, so it is not a true vector file.
  logo.jpg     Same logo as a plain image (also used for link previews)
  favicon.png  Browser tab icon, header logo and hero emblem (the N mark from your logo)

DETAILS USED ON THE SITE
------------------------
Business : Nivora Digital
Phone    : +91 82879 08902 (call and WhatsApp buttons)
Services : Amazon Seller Account Management, Listing Creation, Ad Management
Privacy and Terms are dated 8 October 2026 and say disputes go to the competent courts in India.

THE LEAD FORM
-------------
Fields: Name, Phone number, Preferred time to contact.
On submit the form checks the fields, then opens WhatsApp with a ready message
(name, phone, preferred time) to 918287908902 (India code 91 + 8287908902).
The visitor presses Send in WhatsApp, and the lead arrives on that WhatsApp number.
Note: this works without any server, but the lead is only delivered if the visitor presses Send.
To send leads to a different WhatsApp number, replace 918287908902 in index.html
(it appears in the script near the end and in the WhatsApp buttons).

CHOICES MADE FOR YOU (change in the HTML if needed)
---------------------------------------------------
- Service descriptions are short and general. No prices, results, client numbers or ratings are shown,
  because none were provided.
- Preferred-time choices: Morning (9-12), Afternoon (12-4), Evening (4-8), Any time.
- No address, email or business hours are shown, because none were given.
- The hero uses the N emblem from your logo and the site has no photos.

HOW IT WORKS
------------
- Top bar with phone, sticky header with a Call button; anchor links scroll smoothly to each section.
- On mobile (under 860px) the menu collapses behind a Menu button and a Call / WhatsApp bar stays at the bottom.
- The Plus Jakarta Sans font loads from Google Fonts when online; without internet a clean system font is used.
- Sections fade in as you scroll. The footer year updates automatically.

PUBLISHING ON GITHUB PAGES
--------------------------
1. Create a repository and upload all files, keeping the assets folder.
2. In Settings > Pages, choose the main branch and the root folder.
3. Your site will be live at https://USERNAME.github.io/REPOSITORY/
