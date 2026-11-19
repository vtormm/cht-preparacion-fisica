# CHT — Preparació Física

PWA del Club Handbol Terrassa: planificació, feedback i presentació de sessions.

- `public/index.html`: tota l'app (JS vanilla + Firebase Realtime Database via REST)
- `public/sw.js`: service worker (xarxa primer per a l'HTML; còpia local si no hi ha connexió)
- `worker.js` + `wrangler.toml`: desplegament a Cloudflare

Les escriptures passen per una cua local (`cht_outbox`) i es reintenten sense connexió.
