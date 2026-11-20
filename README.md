# Teach Me Linux — Ubuntu Edition

An instructor-led, installable Ubuntu learning web app. No backend, no third-party database, and no real system commands run.

## Features
- 22 interactive Ubuntu lessons with predict/learn/practice/prove/review flow
- 3 workplace simulations: business outage, startup scripting, staff account access
- Safe terminal and shell simulations, short quizzes, vi editor practice, study notes
- Responsive iPhone and desktop interfaces
- PWA manifest, app icons and service worker for basic offline use after visiting over HTTPS

## Publish with Sites

Use **Sites** as the website publishing destination, with this GitHub repository as the source of truth. This repository contains only the static website; publishing it on another host is not needed or intended.

The site entry point is `index.html`. Serve the repository root over HTTPS, preserving `manifest.webmanifest`, `sw.js` and the `icons/` directory. The app uses relative asset paths and supports being hosted at a subdirectory. No build command is required.

After Sites publishing, verify `index.html`, `manifest.webmanifest`, `sw.js`, and images load under the published URL; verify the live page on mobile. Then in Safari on iPhone choose Share → Add to Home Screen → Open as Web App (when offered) → Add.

## Limits

This is a **teaching simulator**, not a Linux virtual machine or production server. It changes no real files, accounts, services or packages. Lesson progress lives only in the local browser; clearing site data may erase it. Offline caching depends on browser support and a successful first connection.