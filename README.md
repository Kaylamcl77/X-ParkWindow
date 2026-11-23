# X ParkWindow

A mobile-friendly STFX student prototype for estimating nearby parking, permit coverage, walking time, and when to leave for class.

## Run it

Open `index.html` in a browser, or publish the repository with GitHub Pages. The app uses plain HTML, CSS, and JavaScript; no build tools or dependencies are required.

Parking lots, distances, availability, class-change patterns, driver reports, and the health-app connection are fictional prototype data.

## Optional Google Maps traffic

The planner can request a traffic-aware drive duration from the Google Routes API. To use it, enable Routes API and billing in your Google Cloud project, create an API key restricted to the Routes API and your website's referrer, then turn on **Use Google Maps traffic** and enter the key and a starting address. The request is sent directly from the browser to Google; the key is not stored by the app. Without a configured key, the manually entered drive time is used.
