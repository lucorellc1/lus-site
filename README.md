# Lu's Card Art: info site

The public business site: home page, how it works, card details, gallery, pricing, FAQ and policies.
It has no payment code. Every "Order" button links to your separate checkout site.

## Files
- `index.html`: home page
- `policies.html`: shipping, refunds, terms of sale, privacy
- `site.css`: styles
- `images/`: put your card photos here

## Before you share it
1. **Card photos:** put them in `images/`, then in `index.html` find `const PHOTOS = [` and add one line per photo:
   `{ src: "/images/card1.jpg", caption: "Rare design" },`
   The Gallery section stays hidden until at least one photo is listed.
2. **Checkout link:** once the checkout site is online, open `index.html` and `policies.html`, find
   `const CHECKOUT_URL = "https://YOUR-CHECKOUT-SITE.vercel.app";` and paste your real checkout address.
3. If you change prices, update the Pricing section here and the checkout site's price files.

## Put it online
In Vercel: Add New → Project → pick this repository → Deploy. No settings or keys are needed for this site.
