# Grok Discipline Machine

A fully working discipline-first trading journal for EUR/USD + XAU/USD (London–NY overlap).

## Real Features (not placeholders)

- **Daily Loss Limit Lock (–2R)**  
  When today’s total R reaches –2 or lower, the “Save Trade” button is disabled and a lock banner appears. You cannot log more trades that day.

- **Forced Reflection**  
  If you mark a trade or session as “Plan = No”, a modal appears that you must complete before continuing. You answer: which rule, what feeling, what you will do differently.

- **Weekly Review**  
  Shows last sessions summary, clean vs broken sessions, biggest process leak, and a question to set focus for the next week.

- Pre-session Commitment  
- Streaks (Day / Plan / Clean)  
- Discipline Score (0–100) always visible  
- Full trade journal + session log  
- Grok bot that responds based on your real data  
- Data stored only on your device (localStorage)

## Deploy
1. Import this repo on Vercel
2. Deploy
3. Open in Safari → Add to Home Screen

## How to use every evening
1. Open app → click **I Commit for Tonight**
2. Trade (or sit out)
3. Log each trade (or skip)
4. At the end → **Save Session** honestly
5. If you broke rules → complete the forced reflection

This version is designed to make breaking rules feel expensive and following the process feel automatic.
