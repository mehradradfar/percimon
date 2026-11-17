# Persimon

Clickable prototype for Persimon, a luxury concierge app: browse curated pieces, stays and experiences, or ask for anything, and a personal concierge handles it from quote to delivery.

## Files

- `index.html` is the current prototype (v2), designed like a native iOS app: large titles, translucent bars, inset grouped lists, sheets, a floating tab bar, swipe-back and light/dark mode. It opens with the animated splash (`anim/persimon-onboarding.json`, played with lottie-web).
- `lofi.html` is the earlier grayscale lo-fi version of the flows.
- `img/` holds the generated photography.

Both pages are static files with no build step. Open `index.html` in a browser, or serve the folder.

## Deploy on Vercel

Import this repo at vercel.com/new. Leave the framework preset as "Other" with no build command; Vercel serves `index.html` from the root, and the lo-fi stays reachable at `/lofi.html`.

## Using the prototype

- On desktop, the left panel lists every screen, sheet and state; pick one to jump straight there. Arrow keys step through them.
- On the phone, swipe from the left edge to go back and drag a sheet down to close it.
- Toggle dark mode and hotspots from the left panel.
- On a phone browser, the prototype runs full-screen; the "Screens" button at the top opens the list.

## Sign-in buttons

The "Continue with Apple" and "Continue with Google" buttons show text only. To show the official marks, add Apple's and Google's published button artwork as `img/apple.svg` and `img/google.svg`; the buttons pick them up automatically.

Images are AI-generated placeholders for presentation only. Product and brand names are illustrative.
