[README.md](https://github.com/user-attachments/files/31012844/README.md)
# Job Search Command Centre — Nehal Sharma

Single-file job tracker portal (`index.html`). No build step, no dependencies.

## Publish on GitHub Pages (2 minutes)
1. Create a repo (e.g. `job-tracker`), upload `index.html` and this README.
2. Repo → Settings → Pages → Source: **Deploy from a branch** → `main` / root → Save.
3. Portal is live at `https://<your-username>.github.io/job-tracker/`.
   (Make the repo **private + Pages disabled** if you don't want the tracker public,
   and just open index.html locally instead — it works from a double-click.)

## What's inside
- **Tabs:** Dashboard · Govt-Municipal · Govt-Provincial · Govt-Federal · Private Tech · Non-Tech · US Remote · Outreach
- **13 researched roles** seeded (Aug 12, 2026 search) with ATS score, tuned-ATS target, strengths, gaps, keyword swaps, full cover letter, resume tuning sheet, LinkedIn hiring-team search link, and outreach message per job
- **Pipeline tracker:** Saved → Applied → Screening → Interview → Offer → Accepted/Rejected, with progress rail per card
- **Dashboard:** funnel, response rate, category counts, activity log
- **Auto-hygiene:** postings older than 21 days hide automatically (unless already in your pipeline); everything sorts newest-first
- **AI buttons** (⟳ Fetch fresh jobs, ✦ AI tailored resume+letter) work when the portal runs inside Claude.ai; on GitHub Pages they degrade gracefully with instructions. Workflow: fetch fresh jobs in Claude → Export JSON → Import into your hosted copy.
- **Data:** persists in browser storage; Export/Import JSON for backup or moving between copies.

## Weekly routine
1. Open each category tab → ⟳ Fetch fresh jobs (in Claude) or run the linked searches.
2. Apply to anything ≥85 tuned ATS using the resume tuning sheet + cover letter.
3. Mark **Applied** → Outreach tab → send the LinkedIn message within 24h.
4. Update statuses as responses land; Dashboard shows your response rate.
