# Creator Board

A simple goal board for YouTube creators, live at https://creatorboard.netlify.app. Accounts and saved boards live in Supabase; this repo is the website itself (one `index.html` plus the Home Screen app icons and settings).

## How updates work

- `preview` branch: the test version at https://preview--creatorboard.netlify.app (shows a "Test version" label and installs to the Home Screen as "CB Test"). Netlify branch deploys don't use update credits.
- `main` branch: the live website. Every push to `main` is a production deploy on Netlify (15 credits on the Free plan), so changes land on `preview` first and go to `main` in one batch once they're approved.
