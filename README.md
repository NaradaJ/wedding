# යශිතා සහ නාරද — Wedding Invitation

## Put it online with GitHub Pages
1. On GitHub, create a new **public** repository, for example `wedding`.
2. Click **Add file → Upload files**. Drag in everything from this folder (`index.html`, `README.md` and the whole `assets` folder), then click **Commit**.
3. Go to **Settings → Pages**. Under *Branch*, choose `main` and `/ (root)`, then click **Save**.
4. After about 1 minute your link appears: `https://YOUR-USERNAME.github.io/wedding/`

## Turn on the WhatsApp preview image
Open `index.html` on GitHub and click the pencil icon to edit it. Replace the two places that say `SITE_URL` with your real link, without a trailing slash. For example:

```
SITE_URL/assets/og-image.jpg  →  https://narada.github.io/wedding/assets/og-image.jpg
SITE_URL/                     →  https://narada.github.io/wedding/
```

Commit the change. Then paste the link into a WhatsApp chat with yourself to check that the preview appears.

## Personal links for each guest (optional)
Add `?to=` and the guest's name to the end of the link:

```
https://narada.github.io/wedding/?to=සුනිල් මහතා සහ පවුලේ අය
```

The cover then shows "ආදරණීය සුනිල් මහතා සහ පවුලේ අය", and the name is already filled in on the RSVP form. Without `?to=`, the link still works for everyone.

## Settings you can change
At the top of the `<script>` section in `index.html`:
- `RSVP_WHATSAPP`: the number that receives RSVP replies (currently 94760686239)
- `MAP_URL`: the location link
