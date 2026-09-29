# SafeLink

A polished, responsive, standalone SafeLink web experience.

## Run
Open `index.html` in a browser for the interface. For reliable GPS access,
serve it from `http://localhost` or an HTTPS site (e.g. GitHub Pages).
For example, from this folder run `python -m http.server 5500` and visit
`http://localhost:5500`.

## Features
- Sign up/sign in and personal profile on this device
- Navigation between overview, trusted contacts, SOS activity and profile
- Add, edit, call or remove up to two trusted contacts
- Red SOS button, activate/deactivate, browser GPS and live map
- Google Maps location link and native share/copy emergency message
- SOS history saved locally, responsive purple design

## Important operating limits
This standalone edition stores data and account details in this browser's
localStorage, not a server. Do not reuse a real password or enter sensitive
personal details. Clearing browser data erases the records. Accounts are not
shared between devices. Sharing is initiated by the user through their device's
share sheet; **no automatic messages, police alerts, or SMS are sent**.
A production emergency service requires a secure authenticated backend,
encrypted storage, an actual delivery provider, verification, monitoring,
and end-to-end testing. Do not rely on this alone during an emergency.
