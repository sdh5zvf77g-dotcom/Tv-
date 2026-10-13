# UK TV Pro

A responsive, GitHub Pages-compatible UK TV guide and official streaming launcher designed for iPhone.

## Publish to GitHub Pages
1. Create a GitHub repository (or use an existing one).
2. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
3. In **Settings → Pages**, select **Deploy from a branch**, choose your main branch and `/ (root)`, then Save.
4. Open the published Pages URL in Safari on your iPhone.
5. In Safari, tap **Share → Add to Home Screen**.

## Included
- Responsive dark UI for iPhone and desktop
- UK local clock
- Channel search and category filters
- Favourites saved in local browser storage
- Official broadcaster and streaming-service links
- VPN-neutral workflow: connect a VPN in iPhone settings/app before opening a service
- Sample TV guide layout
- Basic service worker caching for repeat visits

## Important limitations
- Programme titles/times in the guide preview are illustrative examples, not live listings.
- Real-time schedules require an authorised EPG data feed and its terms/API credentials.
- Video streams are not embedded; the app opens official broadcaster websites/services.
- VPN connections are managed separately in iOS or a VPN provider app. The app cannot detect or configure VPNs, and a VPN does not guarantee access or override provider eligibility checks.
- BBC iPlayer and other providers may restrict content by country, account, licence or subscription. The app does not bypass restrictions.
- This is an unofficial guide and is not affiliated with BBC, ITV, Channel 4, Channel 5 or Sky.
