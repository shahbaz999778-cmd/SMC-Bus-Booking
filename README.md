# SMC Bus Booking — Source ZIP

**Brand:** S.M.C SHAHBAZ-E-AL MADINA COACH  
**Short name:** SMC  
**Theme:** Royal Blue + Silver  
**Starter version:** 1.0

## Included
- Responsive mobile-first web app interface
- SMC route selector: Karachi, Jamshoro, Sehwan, Dadu, Khairpur Nathan Shah, Mehar, Larkana
- Demo bus search, seat selection, passenger details
- Easypaisa / Meezan Bank / pay-at-counter payment-method selection
- Local booking history and downloadable demo ticket
- PWA manifest, service worker, and app icon

## Run it
Open `index.html` in a modern browser, or upload the files to a static web host (GitHub Pages can host the front-end).

## Important limitations
This is a **front-end starter/demo**, not a live production booking system or an Android APK. Bus departure times, seat availability, and fares are sample data generated in the browser. Bookings are saved only in that browser's local storage. No live reservation is sent to an SMC office.

Online booking requires a secure backend/database and an operator dashboard to manage real buses, schedules, seats, fares, and bookings. Online Easypaisa/Meezan payment requires a supported merchant/payment integration and server-side verification. Do not publish private account numbers or passwords in public source code.

## GitHub upload
Extract the ZIP, open the `SMC-Bus-Booking` folder, then upload its contents (index.html, styles.css, app.js, manifest.webmanifest, sw.js, README.md, and assets folder) to the root of your GitHub repository. GitHub's web uploader may not accept a ZIP as a runnable website; upload the extracted files instead.

## Next development stage
Connect a backend, real route schedules, confirmed fares, seat inventory, operator/admin authentication, and payment verification before accepting customer bookings.
