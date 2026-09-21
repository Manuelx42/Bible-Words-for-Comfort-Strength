# Bible-Words-for-Comfort-Strength
## About Words for Comfort & Strength

Words for Comfort & Strength is a quiet, single-page reading app built around Bible verses chosen for comfort and strength. It's designed to feel like a calm space to return to, not a database to search through.

## What it does

* Presents over 100 verses (King James Version in English, Luther 1912 in German), organized into 17 themes such as Trust & Faith, Peace & Anxiety, Perseverance, and The Power of God.
* Lets you draw a single random verse into a full-screen, distraction-free view, with a gentle fade-in.
* Lets you bookmark any verse, from the list or from a random draw, and revisit your saved verses from a panel in the corner.
* Switches instantly between English and German.
* Switches between light and dark mode, following your device by default, with a manual override that's remembered.
* Installs like an app on your phone or desktop (Add to Home Screen / Install app), with its own icon, and keeps working offline once you've opened it at least once.

## What it's for

Anyone who wants a small, always-available collection of comforting scripture to return to during a hard day, rather than scrolling through a full Bible app to find something specific.

## What it's built with

A single self-contained HTML file (markup, styles, and logic together), a web app manifest, and a service worker for offline caching. No backend, no account, no tracking. Everything you bookmark or choose stays in your browser's local storage on your own device.

## Possible future features

Ideas under consideration for later versions:

* **Bible Reading Plan** — a calendar icon next to the bookmark icon opens a plan that surfaces one verse a day, each with a short introductory sentence for context.
* **Vote for new verses** — a way for readers to suggest and upvote verses they'd like to see added to the collection.
* **Add your own verses** — a way for readers to add personal verses to their own copy of the app.

None of these are built yet. They would need a small backend (or a shared data store) for voting and submissions, since the app currently runs entirely client-side with no server component.