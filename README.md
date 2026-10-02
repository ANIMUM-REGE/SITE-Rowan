# Rowan — site

> Marketing and privacy pages for Rowan: Trusted Circle.

Static site for the app in [`APP-Rowan`](https://github.com/ANIMUM-REGE/APP-Rowan) (iOS) and [`APP-RowanAndroid`](https://github.com/ANIMUM-REGE/APP-RowanAndroid).
Part of the Perpetua app fleet (`VNTR-Perpetua`).

## Hosting

GitHub Pages from `main`, no custom domain (no `CNAME`): **https://animum-rege.github.io/SITE-Rowan/** (verified 200, 2026-10-02). The store listings link its `privacy.html`.

## Pages

- `index.html`
- `privacy.html`
- `get/index.html`

## App status

Rowan is ✅ live on both the App Store (v1.3.0 public, 1.4.0 in review) and Google Play (1.4.0) — as read 2026-10-02.

> Status drifts — **re-verify rather than trust this line.**
> `VNTR-Perpetua/company/state/ops-drops/store-versions.json` (live ASC / Play / public-store reads, refreshed each publisher cycle by `PRJ-Perpetua/dashboard/store_versions.py`)
> carries the fleet-wide picture.

## Editing

Plain HTML, no build step — edit and commit. Keep privacy/support URLs stable: they
are referenced from live App Store and Play listings, and a broken support URL is a
review-rejection trigger.
