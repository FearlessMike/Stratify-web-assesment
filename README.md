# Stratify-web-assesment
A webside developed with wordpress for 2nd stage interview with stratify

# Delta Growth — Marketing Landing Page (WordPress Assessment)

## Staging Link (Pantheon)
- Site: [PASTE YOUR PANTHEON TEST/LIVE URL HERE]

## What to Review (Checklist)
### Design / Sections
- Hero
- About (with 3 highlights)
- Services (4 cards)
- Testimonials (dynamic via CPT + ACF + Elementor Loop Grid)
- Pricing (2 plans)
- Contact (Elementor Form)
- Footer (social + copyright)

### Custom Feature
- Testimonials is a Custom Post Type with ACF fields (client name, role, company, rating)
- Testimonials render dynamically on the homepage

### WooCommerce
- 1 product is added and visible on Shop
- Cart + Checkout work (dummy checkout)

### Optimization & Best Practices
- Caching + lazy load enabled (safe settings for Elementor)
- Basic security plugin enabled (firewall/login protection)
- Unused plugins/themes removed

---

## Direct Links
- Home: [PASTE HOME URL]
- Shop: [PASTE /shop/ URL]
- Product: [PASTE PRODUCT URL]
- Cart: [PASTE /cart/ URL]
- Checkout: [PASTE /checkout/ URL]

---

## How to Test WooCommerce (1 minute)
1. Go to Shop
2. Open the product “Growth Website Package”
3. Add to cart → proceed to checkout
4. Place an order (dummy checkout)

---

## How to Add a New Testimonial (Admin)
1. WP Admin → Testimonials → Add New
2. Add:
   - Title (client name)
   - Excerpt (testimonial quote)
   - Featured image (avatar)
   - Fill ACF fields (role, company, rating)
3. Publish
4. Refresh homepage → testimonial appears

---

## Exports included in this repo
- `acf-exports/testimonial-fields.json` (ACF Field Group export)
- `cpt-exports/testimonials-cpt.txt` (CPT UI export)
- `DOCUMENTATION.pdf` (plugins used, setup notes, maintenance)

---

## Notes
- Built with Elementor Pro + Hello Biz theme.
- Site hosted on Pantheon.
