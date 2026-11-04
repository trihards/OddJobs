# Odd Jobs · Prototype playtest notes

## Concept
An eventually finite, gentle, funny game about often-overlooked service work. The humor comes from peculiar customers and circumstances, not from treating workers' competence as a joke. Character builds/loadouts, changing goals, the broader town and finite sessions are **future concepts**, not implemented.

## Current prototype gallery (November 4, 2026)
- Perks: Espresso (circular hold-to-tamp pressure ring and grinder dial), Latte Lab (foam responds to pour speed), Tea Time (six ingredients with customers permitted to receive incorrect blends), Table Service (no timer; thorough cleaning rewarded), Pour Over (circular pours and uneven infusion).
- Lane 7: Shoe Counter (wrong sizes allowed, colors consistent); Ball Polishing (flick/spin, inspect for scuffs, sparkles only when spotless, one final percentage); Jam Session (hidden pathways, completion rather than numeric grading); Last Call (flick sorting, imperfect results permitted, differing friction needs future polish).
- Bookshop: Shelf Service (reset must replay exact arrangement); Book Seek (compact phone UI, author clues and readable names); Cover Story (humorous judgment, future request pool larger than eight); Page Rescue (rotating torn fragments, completion based).
- Roadside Stop: Snack Tetris (precise grid, tap-to-rotate, overlapping allowed, unique-cell scoring); Windshield Duty (sideways squeegee, streaks from insufficient overlap, bugs should be manageable; other windshield shapes later); Oil Check (use gestures for pull/wipe/reinsert/pour; visual jug cue; one full report after the 3 cars).

## Decisions to preserve
- Prototype each physical interaction independently; only integrate after proving it's fun.
- Mobile-first, especially iPhone. Avoid making players scroll to compare a clue, a shelf, and actions.
- The player should be allowed to choose wrongly, finish imperfectly, and see the outcome.
- 100% is achievable with skill and effort, but never obligatory.
- Some games are naturally pass/fail puzzles; they need no numeric score.
- No timers where they add nothing. Possible future customer impatience belongs to broader shared game logic.
- Visual feedback should come from the object: foam, tea infusion, pouring unevenly, cleaning strokes, sparkles.
- Finished game should have little persistent instructional text, with optional help.
- Sound effects, shared visual treatment, progression, continuity, character customization, customer impatience, and content expansion are deliberately deferred.
- Keep standalone working versions intact. This is an archive/gallery, **not** the integrated game.

## Hosting
Static HTML and CSS; no install/build step needed. GitHub Pages can host the root `index.html` from the default branch. On the repository Settings > Pages, choose Deploy from branch, main, / (root).

## Original design ethos
The surprising pleasure of small service tasks; a gently absurd town, built from tactile toys first.

## Perks mini-shifts (November 4, 2026)
- Tea Time: four different customers per shift (drawn without replacement from the existing twelve), drag or tap two ingredient tins to blend, then lift the bag directly in the illustrated cup. Feedback between cups is brief; one summary comes at the end. No separate start-steep or lift button.
- Latte Lab: three automatic customer designs (heart, swirl, leaf), same speed-sensitive foam drawing. Advance after serving; one shift average at the end. Guide toggle remains optional.
- Pour Over: three customer coffees per shift with slightly different bloom and water targets, same circular pour and water-control mechanic, automatic cup changes, final shift average.
- Preserve the old one-cup variants in Git history. Avoid bringing back repetitive buttons for each order.
