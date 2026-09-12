# REDLINE — demo build

A compiled static build of the REDLINE browse page, published so the
client can click around it. **Source is not here** — it lives in the
client's own private repository.

It talks to a live Supabase project holding demo data only: six invented
cars and seven invented dealers. The key in the bundle is the
*publishable* key, which is designed to ship in a browser — every table
is behind row level security, so it can read the public browse view and
nothing else.
