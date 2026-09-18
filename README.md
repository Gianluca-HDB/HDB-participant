# HDB Participant v6.9.4 — GitHub Pages ready

Critical fix:
- the unauthenticated global click gate no longer intercepts buttons inside the authentication modal;
- `CREA ACCOUNT` now actually calls Supabase `signUp`;
- `ACCEDI` now actually calls Supabase `signInWithPassword`;
- visible validation/error messages added;
- presentation remains the first screen;
- Participant uses the same Supabase `hdb_store` backend as Researcher;
- Participant auth storage remains isolated from Researcher.

Scientific baseline algorithm unchanged.
