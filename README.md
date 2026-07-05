# BI & Dashboards

**For analysts: ship a dashboard execs trust, plus the story that makes the numbers land.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Reach for this when you have data in a warehouse and a stakeholder who needs to act on it. It takes you from query to a clean, performant dashboard in Tableau or Power BI, then turns the numbers into a headline-first narrative that survives the exec meeting - so the work gets read, not just built.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/bi-and-dashboards](https://skillme.dev/pack/bi-and-dashboards) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/bi-and-dashboards`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Power BI DAX](skills/power-bi-dax/SKILL.md)** — Writes correct, fast DAX measures with proper filter context, time intelligence on a marked date table, and VertiPaq-friendly patterns, diagnosing slow visuals down to the storage-vs-formula engine split.
- **[Tableau Best Practices](skills/tableau-best-practices/SKILL.md)** — Builds Tableau dashboards that compute correct numbers at the right grain and stay fast - LOD expressions, filter-order pipeline, extract strategy, and mark-count control.
- **[SQL to Insights](skills/sql-to-insights/SKILL.md)** — Turns SQL query results into a decision-ready business narrative - headline finding, drivers, recommendation - plus the right chart choice for the data shape.
- **[Data Storyteller](skills/data-story/SKILL.md)** — Turns data and charts into a decision-driving narrative structured as headline finding, trend, implication, and recommended action - with finding-led chart titles, context for every number, annotation guidance, and honest flags on any conclusion the data cannot support.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
