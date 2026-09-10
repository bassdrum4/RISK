# RISK

Browser-based RISK-style game prototype.

## Run locally

1. From the repository root, start a static server:
   - `python3 -m http.server 8080`
2. Open:
   - `http://localhost:8080/index.html`

> Use HTTP (not `file://`) so browser features and Firebase auth behavior are consistent.

## App entry points

- `index.html` (primary entry point)
- `nonfunctest_account.html` (full game UI)

## Firebase config in this repo

- Realtime Database rules: `RTDB.json`
- Firestore rules: `firestore.rules`
- Firebase project used by the app is configured directly in `nonfunctest_account.html`
