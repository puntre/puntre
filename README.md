# Hi, I'm Paul (Pun) Tresattayapan

CS @ UC Berkeley · Software engineering, probability, and competitive programming

I build systems that have to be right under pressure: real-time alerting, concurrent state, and math you can check.

📫 puntre210 [at] gmail [dot] com

---

### Featured

**[ollo](https://github.com/Thunyatorn/ollo)** · *Cal Hacks 13.0*
Fall detection on the cameras a home already has. When someone falls, ollo messages and calls caregivers and keeps escalating until exactly one person takes ownership.

- **2.7 s** from fall to alert, using on-device YOLO pose + ByteTrack; a fall is a fast drop followed by stillness, so sitting down doesn't trigger it
- Alert ownership and escalation timers live in **SpacetimeDB** as transactions, so if two caregivers tap "I'm on it" at once, exactly one wins
- Vision LLM runs only after a local alert: **~$0.01 per fall** instead of ~$18 per camera-hour for frame-by-frame analysis
- Twilio + Cartesia voice calls that dial first and generate speech while ringing; React dashboard, ESP32 wrist buzzer, Garmin watch app

`Python` `TypeScript` `React` `SpacetimeDB` `OpenCV` `FastAPI` `C++`

---

### Projects

| Project | What it is | Stack |
|---|---|---|
| [**GeoBash**](https://github.com/puntre/geobash) · [live](https://geobash.vercel.app) | Turns plane-geometry diagrams into algebraic equations and machine-verifiable coordinate proofs | TypeScript, Next.js |
| [**Nightshift Portal**](https://github.com/puntre/nightshift-portal) · [live](https://nightshift-portal-pun12.vercel.app) | Hackathon application portal: applicants apply as hacker, judge, mentor or volunteer; organizers review, grade and decide | Next.js 16, TypeScript, Supabase (Postgres + RLS) |
| [**Sipmap**](https://github.com/puntre/Sipmap) | Crowdsourced map for finding and rating public drinking-water dispensers | JavaScript, geospatial |

---

### Skills

**Languages:** C++ · Python · TypeScript · JavaScript · LaTeX
**Systems & data:** Postgres, Supabase, SpacetimeDB, FastAPI, SQLite
**Web:** React, Next.js, Tailwind
**ML / vision:** PyTorch, Ultralytics YOLO, OpenCV
