# My Personal Finance Tracker V8

Hosted as a static GitHub Pages app and synced through Supabase.

## Before publishing
Open `config.js` and replace:

PASTE_YOUR_SUPABASE_PUBLISHABLE_KEY_HERE

with your Supabase `sb_publishable_...` key.

Never use or upload an `sb_secret_...` key.

V8 changes:
- No Supabase setup popup on new devices.
- Uses the same Supabase configuration on Windows and Android.
- Persists and auto-refreshes Supabase sessions.
- Detects the `JWT Issued at future` error and clears the bad local session.
- Keeps the existing bills, payments, income, credit cards, EMI and reminder features.
- PWA manifest/service worker included.
