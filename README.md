# IRIV PiControl Landing Page

Landing page for [IRIV PiControl](https://my.cytron.io/p-iriv-picontrol-cm4-industrial-controller),
Cytron's IR4.0 industrial controller built on the Raspberry Pi Compute Module.

## Files

| File | What it is |
|---|---|
| `index.html` | The landing page. Self-contained: all CSS and JS are inline. |
| `iriv-3d-explorer.html` | Interactive 3D hardware explorer (~6.4 MB). Embedded in the page via an iframe. |
| `images/logos/` | Partner and brand logos |
| `images/people/` | Testimonial portraits |

## Page structure

Hero → sticky sub-nav → proof strip → Features (3D explorer) → Success Stories
→ Trusted By (testimonials) → Partners → Contact form.

## Publishing to OpenCart

1. Upload `iriv-3d-explorer.html` and the `images/` folder to the server or CDN.
2. In `index.html`, change the iframe `src` and the `images/` paths to full URLs.
3. Paste the contents of `<body>` (plus the `<style>` blocks) into the product page's
   HTML content block in OpenCart.

The contact form posts to ActiveCampaign form 64. Field names and the submit script
are unmodified from the ActiveCampaign embed. Only the styling was replaced.

## Still to do

- Replace three of the four numbers in the proof strip with real figures
  (only "15 tutorials" is verified)
- Confirm the "Get Free Guide" destination, if that CTA comes back
- Decide whether Intellogic is "Technology" or "Solutions". The page currently uses both
