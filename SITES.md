# Sites publication handoff

**Project:** Teach Me Linux — Ubuntu Edition
**Repository:** https://github.com/delphiniumnexus/teach-me-linux-beta
**Branch:** main
**Entry point:** /index.html
**Content type:** Static HTML/CSS/JavaScript plus image assets
**Build:** None
**Runtime server:** None
**Site path:** Root preferred (relative links also support a subdirectory)
**HTTPS:** Required for service worker and installability
**Authentication:** Public beta; no login required

## Publish checks

- Visit the final HTTPS site in Safari and Chromium; no JavaScript errors
- Lesson count: 22, workplace mission count: 3
- Try a guided command, a Bash example and a workplace scenario
- `manifest.webmanifest` and `sw.js` load successfully from the site's own URL
- Apple touch icon and manifest icons load
- After an online visit, Home Screen launch works and previously cached interface opens offline where the platform permits

**Important:** The GitHub repository is source storage, not the public site itself. Do not claim Sites is live until a working Sites URL has been returned and verified.