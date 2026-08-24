# Selva Platform — Phase 1 Timeframe

Day-by-day schedule for all 5 team members across 11 weeks. Static HTML — no install or build.

## View

Open [`index.html`](index.html) in a browser (double-click, or from this folder):

```powershell
start index.html
```

## Schedule

| | |
|---|---|
| **Start** | Mon 13 Jul 2026 |
| **End** | Thu 24 Sep 2026 |
| **Work days** | Sun – Thu |
| **Team** | Ahmed · Amr · Demerdash · Salma · Hanaa |
| **Stack** | Node/Express · React (Vite) · React Native/Expo · Prisma/PostgreSQL |

### Roles (legend)

- Ahmed — Backend
- Amr — DevOps / Backend
- Amr — User Mobile App
- Demerdash — Admin Dashboard
- Demerdash — Mobile (W7+)
- Salma + Hanaa — UX / Design
- QA / UAT / Shared

### Weeks

1. Foundation
2. Admin Core
3. Products + CMS
4. Tower Import
5. Orders + Paymob Mobile (Expo Go + Unified Checkout WebView)
6. Care APIs + Egypt delivery (Account + Orders UI; Paymob checkout in W5)
7. RBAC backend DONE · Role Manager/Settings UI · Egypt checkout · Care · FCM open
8. Care deep + EAS preview (warranty display only — no top-up)
9. QA + Store submission
10. UAT + Launch (Phase 1 complete)
11. Selva Assistant (simple grounded chat — CMS `assistant_source` + OpenAI)

**SoT for W6+ tasks:** `@backend/docs/agent`, `@admin-dashboard/docs/agent`, `@user-app/docs/agent` (updated 2026-08-24).

## What’s in the page

- Milestone timeline (M1–M11)
- Week tabs and member filter
- Day grid with per-person tasks
- Weekly deliverables
- Print styles (tabs hidden; all weeks shown)

## Layout

```
time-frame/
├── README.md
└── index.html
```

## Related

Parent BIOSELVA monorepo plans (`selva-plan.md` in `backend/` / `user-app/`) stay synced with this viewer. This repo is the schedule page only.
