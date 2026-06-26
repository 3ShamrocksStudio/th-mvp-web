# Trashure-Hunters — Web MVP Demo

Tap-to-play browser build of the **Trashure-Hunters** mobile game.

**▶ Play:** https://3shamrocksstudio.github.io/th-mvp-web/

This repo contains **only the compiled, minified web build** — no source code and
no secrets. It runs entirely in the browser against an in-memory / `localStorage`
mock backend (no Supabase, no network), so the full core loop is playable offline:

onboarding → hatch your Elemonster → game home → Trash-Cam cleanup → reward →
collection / leaderboard / profile.

Generated with `npx expo export --platform web`. State lives in your browser's
`localStorage`; clear site data to start fresh.
