# Kaywaj.pcr

An elegant, responsive clothing catalogue built with plain HTML, CSS and JavaScript. Brand contact: **kwpcr6573@gmail.com**.

## Included

- Ivory, burgundy and gold editorial design.
- Four original product photographs supplied by the brand.
- Four supplied campaign banners in a full-image lookbook with product enquiry links.
- Collection search and category filters.
- Accessible product dialog with preferred size and quantity.
- Prepared email enquiries with a copy-message fallback.
- Mobile layouts, keyboard focus states and reduced-motion support.
- No build step, tracking scripts, external font services or dependencies.

## Run

Open `index.html` directly, or run `python -m http.server 8000` in this folder and visit `http://localhost:8000`.

## GitHub upload

1. Extract this ZIP.
2. Open your intended repository, such as `kwpcr/kaywaj-pcr` if that is your account and repository.
3. Use **Add file → Upload files**. Upload the CONTENTS of this folder: index.html, styles.css, app.js, products.js, assets/, README.md and .nojekyll.
4. Commit the files. No build service or Node installation is required.

The ZIP is a source package, not evidence of an upload or deployment. The repository must be selected and accessible before pushing.

## Publishing

This is a static site that can be hosted on a service permitting commercial catalogues. For Netlify, deploy this folder with no build command and publish directory `.`. Check the host's current terms before selecting hosting. GitHub can hold source code; do not assume every GitHub Pages plan/use case permits an online business.

## Update the collection

1. Add the original photo under `assets/`, with a simple filename such as `new-suit.webp`.
2. Duplicate an entry in `products.js` and give it a unique `id`.
3. Set `name`, `type`, `category`, `image`, and `description`.
4. Set `price` to a confirmed numeric PKR amount, or leave `null` to show “Price on enquiry”.
5. Allowed categories in the current filters are `velvet` and `embroidered`. Update the HTML filter controls if you introduce a new category.
6. Upload the changed file and image to the same repository and redeploy.

## Product and order accuracy

Shocking Pink and Noor-e-Safa match the supplied campaign names; other names are presentation names for owner approval. Collection product images are original source photographs. The separate lookbook uses the supplied designed campaign banners. Confirm all fabric descriptions and included pieces with the brand. No stock, prices, delivery promises, returns policy or payment methods have been invented. Size options express customer preference only.

This is an enquiry catalogue, **not a checkout, inventory system or order database**. The enquiry button prepares a message in the visitor's email app; the visitor must send it. No emails are sent by this website itself. Confirm availability, total price, delivery and exchange terms directly before accepting payment.

## Privacy

No analytics or cookies are installed. Form entries stay on the page until the visitor copies them or opens their email application. The hosting provider may keep ordinary access logs. The brand's email provider handles messages that customers choose to send.

## Ownership

Brand name and product photographs belong to their respective owners. No third-party reuse permission is granted by this package.
