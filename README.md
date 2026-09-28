# Destiny website demos

One Vercel project serves a comparison page at `/`, the enquiry catalogue at `/enquiry/`, and the ecommerce preview at `/shop/`. The original projects are preserved separately.

## Deploy

Import this repository into Vercel as **Other** framework. The `vercel.json` file publishes `dist/`; no build command or environment variables are required. All assets are included. The `X-Robots-Tag` header asks search engines not to index the demos.

This ecommerce checkout is an illustrative local demo. It does not take real payments, place real orders, or send email.
