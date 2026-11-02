# Vikas Lucky Interior Work

Complete static website for Vikas Lucky Interior Work in Khadakpada, Kalyan, Maharashtra.

## Deploy on GitHub Pages

The root `index.html` is a standalone copy of the website with its images and fonts embedded. It can be deployed without a separate assets folder.

In repository **Settings → Pages**, choose **Deploy from a branch**, select **main**, choose **/ (root)**, and save. GitHub will display the published URL after deployment.

The original multi-file website remains in `dist/`.

## Run locally

No build step or dependency installation is required. From this repository, run:

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000 in your browser.

## Files

- `index.html` — standalone export for GitHub Pages, with embedded images and fonts.
- `dist/index.html` — page content, responsive styles and browser interactions.
- `dist/assets/interior-concepts.png` — AI-generated interior design concepts, clearly identified on the website.
- `dist/assets/dm-sans.ttf` and `dist/assets/manrope.ttf` — locally hosted fonts.
- `dist/assets/FONT-LICENSE.txt` — font license.
- `.openai/hosting.json` — original Sites project identity and static hosting configuration.

## Appointments and contact links

The appointment form prepares a WhatsApp message addressed to **+91 70214 10676**. Visitors review and send the message in WhatsApp; the website does not store form submissions or automatically confirm appointments.

The website also includes phone, email, directions and the supplied Google Business profile link. Instagram and Facebook handles were not verified and are not included.

## Hosting

For a static host, publish the `dist` directory. All images and fonts are bundled locally. The original Sites publication is available at:

https://vikas-lucky-interior-kalyan.adityawaghmare5000.chatgpt.site

## Editing

Edit `dist/index.html` to change the page or the WhatsApp destination. The gallery filters and mobile navigation run in the browser. No plugin integration is configured.

The Google rating reflects the supplied profile screenshot. The concept imagery is illustrative and does not show completed client projects.
