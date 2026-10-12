# Jungian Typology Quiz

A single-file, no-build quiz that returns:

- a four-letter Jungian type (E/I, S/N, T/F, J/P)
- the dominant, auxiliary, and least-developed cognitive function, drawn on a compass
- a primary archetype out of twelve (King, Warrior, Sage, Rebel, Lover, Builder, Guardian, Explorer, Joker, Healer, Judge, Outsider)
- the shadow archetype, defined as the opposite of the primary

24 questions: 12 on the Jungian axes, 12 scenario questions that score the archetypes.
Everything runs in the browser. No data is collected or stored.

## Run it

Open `index.html` in a browser. There are no dependencies. Fonts load from Google Fonts and fall back to system serif and sans if offline.

## Host it with GitHub Pages

Repo Settings > Pages > Source: `main` branch, `/ (root)`. The site appears at `https://<username>.github.io/<repo>/`.

## Where to edit

All content lives at the top of the `<script>` block in `index.html`:

- `JUNG`: the 12 axis questions
- `AQ`: the 12 archetype questions
- `ARCH`: archetype descriptions and shadow pairings
- `TYPES` and `FN`: type nicknames and function descriptions

## Note

Jung described eight cognitive functions. The four-letter code is a later popularization, and the twelve archetypes are a common modern grouping. This is a tool for reflection, not a clinical measure.
