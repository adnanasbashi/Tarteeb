TARTEEB LAUNCH PACKAGE

Customer website/PWA:
- index.html
- manifest.json
- sw.js
- icon-192.png
- icon-512.png

IMPORTANT:
This is the customer-facing launch shell. The current prototype sends cart,
VIP registration, special orders, wholesale inquiries and reviews through WhatsApp.
A production admin/database must be connected before relying on persistent stock,
customers, orders or VIP data.

RECOMMENDED FREE STACK:
1. Netlify Free OR Cloudflare Pages Free for hosting.
2. Supabase Free for database, authentication and storage.
3. PWA manifest + HTTPS for installable app behavior.

ADMIN MUST HAVE BEFORE PRODUCTION:
- secure authentication and roles
- products/SKU/pricing
- stock in/out/reservations
- suppliers and purchase orders
- customer/order management
- VIP registrations
- special-order pipeline
- wholesale accounts and tier pricing
- review moderation
- delivery-date calendar
- dashboard
- audit log

LAUNCH QA:
- Replace sample products/prices/stock with verified data.
- Confirm courier delivery dates and pickup location.
- Confirm legal return/privacy/terms.
- Test COD/order confirmation and WhatsApp on Android and iPhone.
- Do not publish sample testimonials as genuine reviews.
