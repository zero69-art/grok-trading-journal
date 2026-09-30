# Grok Discipline Machine

Fully working discipline-first trading journal for EUR/USD + XAU/USD (London–NY overlap).

## Working Features

- **Daily Loss Limit Lock (–2R)**  
  Tracks today’s R. When it reaches –2 or lower the Save Trade button is disabled and lock banners appear.

- **Forced Reflection**  
  Marking Plan = No opens a modal you must complete (rule broken, feeling, next action) before the data is saved.

- **Weekly Review**  
  Summary of recent sessions, clean vs broken, biggest process leak.

- Pre-session Commitment  
- Streaks (Day / Plan / Clean)  
- Discipline Score (0–100) always in header  
- Today R counter  
- Full trade journal + session log  
- MT5 import (paste lines)  
- Grok bot that uses your real data  
- All data stored only in localStorage on your device

## Bug fixes in this version
- Reliable string IDs (no float delete bugs)
- Clean reflection flow for both trades and sessions
- Accurate daily R calculation using `day` field
- Form clearing after save / reflection
- XSS-safe rendering
- Restored Import tab
- Removed unreachable code
- Null-safe DOM updates

## Deploy
Import this repo on Vercel → Deploy → Open in Safari → Add to Home Screen.
