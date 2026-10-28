Privacy

Intervals Player doesn’t have accounts, a database, or analytics. Your data stays with you and the services you connect.

Stored on your device only: your intervals.icu API key, your Strava sign-in tokens, your FTP, your workout library and settings. This is kept in your browser’s local storage and never sent to me or to anyone else, except as described below.

Sent to intervals.icu: your API key (to read your calendar and training load), and completed rides as .fit files (power, and heart rate if a strap is connected).

Sent to Strava, through a small helper: when you connect Strava and after each ride, the app sends the sign-in request and the .fit file to a Cloudflare Worker, which forwards them to Strava. The Worker holds Strava’s client secret and doesn’t store your tokens or ride data. Cloudflare may keep standard request logs under its own policy.

Bluetooth: power, cadence and heart rate from your trainer and strap are read by your browser and used on screen. They aren’t sent anywhere except in the ride file described above.

Hosting: the app is served by GitHub Pages, which may keep standard access logs under GitHub’s policy.

Removing your data: clear the site’s data in your browser to remove everything stored on the device. To disconnect Strava, remove the app under Settings → My Apps on strava.com. To revoke the intervals.icu key, regenerate it in your intervals.icu settings.
