# Dr. Babasaheb Ambedkar Auditorium Scheduler

Installable web app (PWA) for booking and scheduling the auditorium. Single-page, no build step.

## Deploy on GitHub Pages
1. Create a new repository on GitHub (e.g. `auditorium-scheduler`).
2. Upload all files in this folder (keep the `icons/` folder), or push with git.
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`, and Save.
4. Open `https://<your-username>.github.io/auditorium-scheduler/`.

## Install as an app
- **Android/Chrome/Edge:** open the link → menu → *Install app* / *Add to Home screen*.
- **iPhone/Safari:** Share → *Add to Home Screen*.

## Notes
- Bookings are stored in each browser's localStorage (per device, not shared).
- Approval emails go to the address set in `APPROVAL_EMAIL` inside `index.html`.
