# Harmony

Read `README.md` first: what Harmony is and how to run it. The Exact app is
`app/` (its `AGENTS.md` is the authoring guide); the backend is
`snapback/schema.q`; `seed.mjs` writes the demo data. Keep every read in the
one `snapshot` source and every write admit-only (`db.write`): natively the
Snapback device serves one answer at a time (`app/app.ts` says why).
