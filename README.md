# Grok Trading Journal

Clean & simple trading journal focused on **EUR/USD + XAU/USD** during the London–New York overlap.

Built for part-time traders (especially 9-5 jobs in India).

## Features
- Quick trade logging (Pair, Direction, R-result, Outcome, Notes, Plan followed)
- Performance stats (Win rate, Total R, Plan adherence, Best pair)
- Evening checklist (your exact process)
- **MT5 Import** – paste deals from MT5 reports (manual but private & free)
- **Grok Trading Bot** – discipline reminders, risk rules, pair tips, progress check
- Data saved locally on your device (localStorage)
- Progressive Web App – Add to iPhone Home Screen

## Important about MT5 connection
True automatic live sync with MetaTrader 5 is **not possible** from a pure client-side web app for security and technical reasons.

What you *can* do easily:
1. In MT5: Toolbox → History → right-click → Report / Save as Report
2. Copy the closed deals
3. Paste them into the **MT5 Import** tab using the simple format shown

This keeps all your data private on your phone.

## Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) and log in with GitHub
2. **Add New Project** → Import `zero69-art/grok-trading-journal`
3. Click **Deploy** (no build settings needed)
4. Open the live URL in **Safari** on iPhone
5. Tap **Share** → **Add to Home Screen**

## Local use
Open `index.html` in any modern browser.

---
Made for focused, disciplined trading. Process > prediction.
