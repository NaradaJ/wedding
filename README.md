# යශිතා සහ නාරද — Wedding Invitation

Live link: https://naradaj.github.io/wedding/

## Files
- `index.html`: the whole invitation (styles and script included)
- `assets/`: `cover-art.webp`, `corner.webp`, `music.mp3`, `og-image.jpg` (WhatsApp preview)
- `assets/fonts/`: Noto Serif Sinhala and Noto Sans Sinhala, hosted with the site so the page doesn't depend on Google Fonts

## Put it online with GitHub Pages
1. Go to **Settings → Pages**. Under *Branch*, choose `main` and `/ (root)`, then click **Save**.
2. After about 1 minute the site is live at `https://naradaj.github.io/wedding/`.

## WhatsApp preview image
The preview links in `index.html` already point to `https://naradaj.github.io/wedding/`. If you rename the repository, update the `og:image` and `og:url` lines to match. Paste the link into a WhatsApp chat with yourself to check that the preview appears.

## Personal links for each guest (optional)
Add `?to=` and the guest's name to the end of the link:

```
https://naradaj.github.io/wedding/?to=සුනිල් මහතා සහ පවුලේ අය
```

The cover then shows "ආදරණීය සුනිල් මහතා සහ පවුලේ අය", and the name is already filled in on the RSVP form. Without `?to=`, the link still works for everyone.

## Settings you can change
At the top of the `<script>` section in `index.html`:
- `RSVP_WHATSAPP`: the number that receives RSVP replies (currently 94760686239)
- `MAP_URL`: the location link
