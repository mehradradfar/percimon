# Percimon

Clickable prototype for Percimon, a luxury concierge app: browse curated products and services, or ask for anything, and a personal concierge handles it from quote to delivery.

## Files

- `index.html` is the hi-fi prototype: 24 screens built from the Percimon design system (brand colors, Inter Regular/Medium, buttons, inputs, chips, segmented controls), with photography in `img/`.
- `lofi.html` is the earlier grayscale lo-fi version of the same flows.

Both are static files with no build step. Open `index.html` in a browser, or serve the folder.

## Deploy on Vercel

Import this repo at vercel.com/new. Leave the framework preset as "Other" with no build command; Vercel serves `index.html` from the root, and the lo-fi stays reachable at `/lofi.html`.

## Using the prototype

- On desktop, the left panel lists every screen and its states (pick one to jump straight there); arrow keys step through screens in order.
- On a phone, it runs full-screen; the "Screens" button at the top opens the list.
- Tap empty space to flash what's clickable, or turn on "Show hotspots".

Images are AI-generated placeholders for presentation only. Product and brand names are illustrative.
