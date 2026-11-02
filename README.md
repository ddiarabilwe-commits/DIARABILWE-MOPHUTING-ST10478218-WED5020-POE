Rayton Home Bakery Website

Project Overview

This website is for Rayton Home Bakery. It shows the bakery’s products and contact information. The site keeps the design photos, wording and page layout that were provided for the project.

Features

- The site works on desktops, tablets and phones. It has friendly navigation.

- There are sections for Home, About, Menu, Specials, Gallery and Contact.

- Users can search for products. They can filter by category. Sort by price or name.

- The Gallery includes a lightbox viewer and subtle scroll animations. It supports reduced-motion settings.

- The Contact and Order form has fields for name, email, phone order type and message. All required fields are validated.

- The form sends orders via AJAX to ddiarabilwe@gmail.com using FormSubmit.

- A Google Maps panel shows the bakery’s location with a directions link. The address is 48 Emerald Hills Estate, Rayton.

- SEO includes title, meta description, keywords sharing tags Bakery structured data, robots.txt and a sitemap.xml starter.

Project Files

- index.html – Contains the page layout, embedded styles, SEO data and map code.

- Js/main.js – Handles menu, gallery, filtering, animations and form validation/submission.

- Css/style.css – The stylesheet. Styles are also embedded in HTML for preview.

- Robots.txt and sitemap.xml – Help search engines find and index the site.

Email Form Activation – Required Before Live Orders

The form uses FormSubmit’s AJAX endpoint to send messages to ddiarabilwe@gmail.com.

On the submission FormSubmit sends an activation email to that address. The mailbox owner must open that email. Approve the form. After approval will normal email delivery work.

If the activation email does not appear, check the spam or junk folder.

The form needs an internet connection to work. Before collecting customer data review the service’s privacy policy. Do not collect credit card details or passwords in this form.

The site checks form fields in the browser.. Browser-side checks are not secure. A production system must also. Protect data on the server.

Location Check

The location uses the address:

48 Emerald Hills Estate, Rayton, Gauteng, South Africa.

Double-check the map. Entrance before publishing. The map provider might interpret estate addresses differently.

Run

1. Extract the ZIP file. Open the folder in Visual Studio Code.

2. Open index.html in a browser or use Live Server.

3. Test navigation, menu, gallery, filtering, animations and form.

4. Internet access is needed when testing email submission.

5. Complete FormSubmit activation before expecting email delivery.

GitHub Pages Deployment

1. Upload the folder contents to the repository root on the branch used for GitHub Pages.

2. Keep index.html in the root. Keep the css folders.

3. Go to Settings → Pages.

4. Select the branch (use master if that was used before). Choose / (root).

5. Click Save.

6. Open the published website URL. Test all sections and the contact form.

7. Replace the sitemap placeholder with the published URL if you add a sitemap later.

Testing Checklist

- Run node --check js/main.js to check JavaScript syntax.

- Run unzip -t on the ZIP file to check archive integrity.

- Test the site at phone, tablet and desktop screen sizes.

- Open the published site, not the iPhone Files preview.

- Verify the Google Maps location.

- Complete FormSubmit activation.

- Send a test order before saying email delivery is verified.

- Complete all. Deployment through the owner’s account.

No physical-device testing or completed GitHub deployment is claimed.

Changelog

1 November 2026 – Part 3 Updates

- Expanded SEO metadata. Added Bakery structured data.

- Added Google Maps location panel and directions link.

- Connected the order form to the supplied email using AJAX and FormSubmit.

- Added sending, success and failure messages.

- Configured the form to clear after a successful service response.

- Improved validation feedback using aria-invalid.

- Updated setup, deployment, activation and testing instructions.

Improvements

- Responsive layout and mobile navigation.

- Product search, category filtering and sorting.

- Gallery lightbox.

- Scroll reveal effects.

- Client-side form validation.

References

The Independent Institute of Education (The IIE) (2026) WEDE5020 Module Manual. Johannesburg: The Independent Institute of Education.

FormSubmit (n.d.) FormSubmit: Easy form endpoints. Available at: https://formsubmit.co/ (Accessed: 1 November 2026).

Google (n.d.) Google Maps URLs. Available at: https://developers.google.com/maps/documentation/urls (Accessed: 1 November 2026).

MDN Web Docs (n.d.) Client-side form validation. Available at: https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation (Accessed: 1 November 2026).

MDN Web Docs (n.d.) JavaScript Guide. Available at: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide (Accessed: 1 November 2026).

Schema.org (n.d.) Bakery. Available at: https://schema.org/Bakery (Accessed: 1 November 2026).

WHATWG (n.d.) HTML Living Standard. Available, at: https://html.spec.whatwg.org/ (Accessed: 1 November 2026).
