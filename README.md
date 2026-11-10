# Bloom Yoga Ballina website

The website for Bloom Yoga Ballina: boutique yoga classes of 6 with Selin at 2/11 Westland Place, West Ballina, NSW 2478.

It is a single static page: `index.html` plus the `images/` folder. There is no build step, framework or database, so any static host can serve it.

## Files

- `index.html`: the whole site (styles are inside the file).
- `images/`: logos and photos, already resized for the web.
- `CNAME`: tells GitHub Pages to serve the site at www.bloomyogaballina.com.au.

## Publish with GitHub Pages

1. In this repository on GitHub, open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, pick the `main` branch and the `/ (root)` folder, then save.
3. Under **Custom domain**, check it shows `www.bloomyogaballina.com.au`, and tick **Enforce HTTPS** once it is available.
4. At your domain registrar, add these DNS records:
   - `CNAME` record: `www` → `bloomyogaballina.github.io`
   - Four `A` records for the bare domain `bloomyogaballina.com.au`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`

   DNS changes can take a few hours to take effect. Check GitHub's current Pages documentation if anything has changed.

Netlify or Vercel also work: connect this repository and leave the build command empty.

## Editing

Open `index.html` in any text editor, change the text, save and commit. Most content is plain text inside the HTML:

- **Schedule**: the `<!-- Schedule -->` section.
- **Prices and Momence links**: the `<!-- Pricing -->` section.
- **Class descriptions**: the `<!-- Yoga -->` section.

## Still to fill in

- `[PER WEEK]` next to the Unlimited price: replace it with the real billing period.
- `[MAILERLITE SIGNUP LINK]` on the **Join the Email List** button: replace it with your MailerLite form or landing page link.

## Booking links (Momence)

- First class free: https://momence.com/Riverside-Yoga-Ballina/membership/First-Class-Free/901614
- Drop In: https://momence.com/Riverside-Yoga-Ballina/membership/Drop-in-Class/927238
- Unlimited: https://momence.com/Riverside-Yoga-Ballina/membership/Unlimited-Membership/901608
- 5 Class Pass: https://momence.com/Riverside-Yoga-Ballina/membership/5-Class-Pass/901610
