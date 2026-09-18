# track.thestickytrap.app

The front door for The Sticky Trap order tracker: the address on invoices, packing slips, QR codes and emails.
It forwards straight to `https://thestickytrap.app/track/` with the same query (`?o=CODE&t=TOKEN`) or a bare code in the path
(`track.thestickytrap.app/ST-K3F9`). The tracker itself stays on the app's origin so push notifications and the service worker keep working.

Two files matter: `index.html` and `404.html` (identical - GitHub Pages serves 404.html for path-style links). `CNAME` binds the subdomain.
Owner: the bot editor session (Downloads\Sticky Bot\track-site is the source copy).
