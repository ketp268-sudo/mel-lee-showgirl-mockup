# Homepage mockup — Mel Lee · The Showgirl Method

Static, high-fidelity HTML/CSS mockup of the redesign described in `../payhip-redesign-plan.md` (v2). It is a visual target, not Payhip code: the paste-ready Payhip CSS lives in `../payhip-custom-code/`.

- `index.html` — homepage: sticky header with gold CTA → video hero (poster still + scrim) → credibility ticker → 3 value columns → services ladder with "Most popular" badge → coaching plans (ribbon on the £350 Series) → tutorials grid → text testimonials → showreel → about teaser → FAQ → lead magnet → gold CTA band → footer.
- `work-with-me.html` — Work With Me page per plan §4.3: price ladder, three featured blocks, compare table, meet your coach, testimonials, FAQ, CTA band.
- `styles.css` — Midnight Stage palette (`#0B0F1A` / `#131A2B` / `#2A3550` / `#F4EFE6` / `#A9B0C2` / teal `#2EC4D6` / gold `#D4A93C` / coral `#F2825A`), Playfair Display + Jost (Google Fonts), scroll reveals via `animation-timeline: view()` with reduced-motion fallback.
- `assets/` — Mel's real store images downloaded from the live Payhip CDN and resized (hero poster = blue-smoke shot; showreel poster = red-smoke shot; tutorial covers; sunset series; headshot).

Open `index.html` in any browser (fonts load from Google; without internet the fallback serif/sans is used). Rendered screenshots are in `../../media/mockup/`.

Notes for the build: the hero shows the poster still where Payhip will play Mel's muted looping video; the mobile sticky "Book coaching" bar and the plan button labels need the footer JS (custom domain) on Payhip.
