# Rozzie Bike Order Page (Seymore Green)

One-page shirt order form with a built-in admin. Hosted on Netlify.

## Files
- `index.html` - the whole page (customer order form + admin panel)
- `netlify/functions/catalog.mjs` - saves/loads products & settings (Netlify Blobs)
- `package.json`, `netlify.toml` - tell Netlify how to build it

## One-time setup
1. Upload ALL these files to the GitHub repo (keep the folder structure).
2. Netlify > Site configuration > Environment variables > Add `ADMIN_PIN` = a 6+ digit PIN only you know.
3. Trigger a redeploy (Deploys > Trigger deploy).
4. Forms: make sure form detection is enabled; you should see `rozzie-order` and `rozzie-payment`.

## Using the admin
- Scroll to the bottom of the live page, tap "Admin", enter your PIN.
- Change deadline, 2XL+ upcharge, Cash App / Venmo / PayPal.
- Add / edit / hide / delete / reorder products. Upload a blank shirt photo and the logo is placed on it automatically.
- Tap "Publish changes to the live page". Done - no GitHub edit needed.
