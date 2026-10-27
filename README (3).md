# Café Luuma — Local Business Website & Live Pitch

**Project 3 · FUTURE_FS_03**

An independent student website proposal for Café Luuma in Mavelikara, Kerala. This is not the café’s official website and has not been approved by the owner.

## Live demo

https://cafe-luuma-mavelikara-demo.idealtulip34.chatgpt.site

The hosted demo is private to its owner. To share a publicly accessible URL, deploy the extracted files using GitHub Pages or another static host after reviewing the business details with the owner.

## Technologies

- HTML5
- CSS3 with responsive layouts
- Vanilla JavaScript
- Google Fonts (DM Sans and DM Serif Display, with system fallbacks)
- AI-generated illustrative food imagery

No backend, package installation, API keys or database is required.

## Features

- Café landing page with a light, warm visual direction
- Searchable menu highlights and category filters
- Call-to-phone and Google Maps search links
- Swiggy and Zomato menu links
- Instagram link from a public business listing
- Visit-note planner with a copy button
- Mobile navigation and responsive styling
- Accessible labels, keyboard focus styles, a skip link and reduced-motion support
- SEO title, description and social metadata

## Run locally

Download all files while preserving the folder structure, then open `index.html` in a browser. The clipboard button works best on HTTPS or localhost and includes a manual-copy fallback.

Optional local server:

```sh
python -m http.server 8000
```

Then visit http://localhost:8000.

## Files

| File | Purpose |
|---|---|
| `index.html` | Page structure and content |
| `styles.css` | Theme and responsive layouts |
| `script.js` | Navigation, menu filters/search and visit planner |
| `assets/cafe-spread.png` | AI-generated illustrative food image |
| `assets/favicon.svg` | Proposed favicon |
| `PITCH.md` | Short owner pitch and live-demo walkthrough |
| `SOURCES.md` | Public business details and verification notes |
| `ASSETS.md` | Image-generation provenance and prompt |

## Upload to GitHub

1. Create a repository called **FUTURE_FS_03**.
2. Extract the project ZIP.
3. Open the extracted `FUTURE_FS_03` folder.
4. Choose **Add file → Upload files** on GitHub.
5. Upload the contents of that folder, including `assets`.
6. Commit the files. Do not upload only the ZIP.

For GitHub Pages, open **Settings → Pages**, select **Deploy from a branch**, **main**, **/ (root)**, and save. Use the URL shown by GitHub once deployment finishes.

## Business benefits

| Visitor need | Website response | Potential business benefit |
|---|---|---|
| What can I eat? | Searchable menu highlights and live menu links | Helps visitors decide before arriving |
| Where is the café? | Address and Maps search | Reduces friction in finding the business |
| Can I order delivery? | Links to the café’s delivery listings | Makes the existing ordering channels easier to find |
| Can I plan a group visit? | Copyable visit note and direct call | Supports clear enquiries without promising a booking |
| How do I find updates? | Instagram link | Connects the website to the café’s social presence |

These are expected usability benefits, not measured sales results.

## Verification and limitations

- JavaScript syntax and relative file links checked.
- Browser checks verified menu filtering, search with no matches, and visit-note generation.
- Desktop layout visually inspected.
- Responsive styles are implemented; a real-phone check is still recommended before owner handoff.
- Call, social, map and delivery links are provided; no calls, orders or messages were placed during testing.
- The visit planner does not send or save a booking and does not collect personal contact details.
- No payment processing, online ordering backend, email notifications or WhatsApp integration is included.
- The menu is a highlight selection, with no unverified prices. Delivery menus are the source for current prices and availability.
- No exact opening hours are published because public listings differ. Visitors are prompted to call.
- The image is illustrative AI artwork, not a photograph of the café or its dishes.

## Before official launch

Ask the owner to confirm the spelling, logo, address/pin, phone, Instagram, current menu and hours. Replace illustrative imagery with owner-approved photos and obtain approval for the website and branding. Remove the proposal banner only after approval.

The pitch is prepared in `PITCH.md`. It has not been sent to the owner.

## Author

Akhila · MCA student

GitHub: https://github.com/akhilas094
LinkedIn: https://www.linkedin.com/in/akhilas09
