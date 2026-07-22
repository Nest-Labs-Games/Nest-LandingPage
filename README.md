# Nest Game Incubator — Landing Page

A single-file landing page for the **Nest Game Incubator**, an Indonesian mobile-game incubator and publisher running its first cohort (Batch 1, 2026). Built as clean, self-contained HTML/CSS/JS with no build step and no dependencies.

## Highlights

- Purple-gradient theme with big rounded panels
- Hero **roster carousel** (auto-advancing, with an accessible pause/play toggle and keyboard controls)
- **Running marquee** of media and community partners
- Animated **flowing wave** section dividers and a drifting hero background
- Fully responsive, and it respects `prefers-reduced-motion`
- Sections: hero, partners, the problem, strategy, accelerator funnel, curriculum, timeline, guidelines, team, apply

## View it

Open the file directly in a browser:

```
Nest Incubator Landing.html
```

Or serve the folder so the logos load over HTTP:

```bash
python -m http.server 8000
# then open http://localhost:8000/Nest%20Incubator%20Landing.html
```

## Structure

- `Nest Incubator Landing.html` — the page (all CSS and JS are inline)
- `logos/` — partner logos, roster game art, and the nest wordmark
- `Nest Incubator Landing (original).html` — backup of the original design export
