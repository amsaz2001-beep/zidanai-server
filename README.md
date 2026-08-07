# ZidanAI Backend v12

Full EGX universe (~244 Egyptian stocks + metals + US) with Yahoo Finance + Aug-2026 reference seed.

## Run locally (PC or cloud)

```bash
cd server
npm install
npm start
```

API: `http://localhost:8787/api/snapshot?index=EGX30`

## Free cloud deploy (phone can reach it)

### Render.com
1. Create free Web Service
2. Connect this `server` folder (or upload zip)
3. Build: `npm install`
4. Start: `npm start`
5. Copy the public URL e.g. `https://zidanai.onrender.com`

### Railway.app
Same idea — deploy `server`, set start command `npm start`.

## Point the phone app

In the app **Settings / API box**, paste:
`https://YOUR-SERVICE.onrender.com`

Then press Scan. Pill should show **LIVE · N**.
