# Pill Box

A realistic 7-day pill organizer that runs entirely in the browser.

## Features
- Weekly organizer with morning, midday, evening and bedtime compartments
- Multiple boxes (for example, one per family member)
- Scan a pharmacy label with the camera; text is read on the device (free, no account)
- Dose alerts with a chime and on-screen banner while the page is open
- Read aloud: speaks each medicine's name, strength, dose, times, directions and the full label text
- Pill counts with refill warnings

## Hosting on GitHub Pages
1. Upload everything in this folder to a repository (keep the `icons` folder and `manifest.json` next to `index.html`).
2. Go to **Settings → Pages**, choose your main branch and the root folder, and save.
3. Open the link GitHub gives you. On a phone, use **Add to Home Screen** to install it with the Pill Box icon.

## Notes
- Data is saved in the browser on each device (localStorage). Clearing browser data removes it.
- The label scanner uses Tesseract (Apache 2.0). Its engine loads from jsDelivr on the first scan; the English language data is built into `index.html`.
- Pill Box helps you keep track. Always follow the directions from your doctor or pharmacist.
