# Hackathon Atlas maintenance instructions

- Repository: Koko08071/-hackathon-; branch: main.
- Production: https://hackathon-winners-atlas.vercel.app/ (existing Vercel project hackathon-winners-atlas).
- Treat this repository as the source of truth. For every requested website update (design, project records, images, filters, offline version), edit and commit the affected source files to main, then deploy that commit to the existing production project and verify deployment status and public HTTP response. Report the actual commit and deployment status; do not report success if either step fails.
- Keep horizontal project cards, red software / blue hardware luminous labels, responsive layout, explicit event and award fields, month and region filters, search, light/dark mode, and offline access.
- Verify awards against primary sources wherever available; distinguish team names from project names and classify by actual deliverable. Do not generate product imagery. Use attributable real project screenshots/photos; respect licenses and avoid unrelated event posters.
- Keep the current production URL stable. Mainland China mobile access requires real network testing; deployment readiness alone does not establish VPN-free reachability.
- Release v1.5.1: 82 records (19 classified hardware) across 22 events; editorial selection, not a complete global census.
