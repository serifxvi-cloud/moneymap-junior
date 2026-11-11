# MoneyMap Junior

A standalone, mobile-friendly money-learning website for young learners.

## Run locally
Open `index.html` in a modern browser. No npm, build step, API key, or server is required.

## Publish with GitHub Pages
1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and **/(root)**, then Save.
4. The site will be published at https://serifxvi-cloud.github.io/moneymap-junior/ after GitHub Pages finishes deploying.

## Privacy
This starter edition stores practice entries in the current browser using localStorage. It does not connect to MoneyMap's Supabase project, does not share data with the normal MoneyMap website, and does not process real payments. Clearing browser data can erase the practice records. Children should ask a trusted adult before making real-money decisions.


## Account sign-in setup
MoneyMap Junior now offers Google sign-in and email/password sign-in using the same Supabase Auth project as the main MoneyMap site. In the Supabase dashboard:

1. Open **Authentication → URL Configuration**.
2. Add `https://serifxvi-cloud.github.io/moneymap-junior/` to the allowed redirect URLs.
3. Under **Authentication → Providers**, make sure Google is enabled and its OAuth credentials are configured.
4. Make sure email sign-ups are enabled if you want users to create accounts with email.

The currency dropdown changes the displayed currency using a live exchange-rate feed. New practice entries are still entered and stored in IDR, and practice data remains in the current browser only; signing in does not yet sync Junior balances or entries to the cloud.
