# Codebusters Cipher Lab

An interactive, bilingual learning site for Science Olympiad 2026–27 Division C Codebusters. English is the default (`dist/index.html`); the full Chinese version is at `dist/zh.html`. The language links retain the current page or lesson. Both versions share browser-local progress.

The site includes 12 staged lessons, original short exercises, stepwise hints, automatic grading, decoding workbenches, local progress tracking, and a 15-minute mixed practice set.

## Run locally

Open `dist/index.html` directly, or run:

```bash
python3 -m http.server 8000 --directory dist
```

Then visit `http://localhost:8000`. To deploy, use `dist/` as the static site root. There is no server dependency. Progress is stored in the browser's `localStorage`, so clearing browser data or switching devices will remove it.

## Competition scope

As of November 2, 2026, the official 2027 Division C rules PDF is available through the form on the [Science Olympiad rules page](https://www.soinc.org/rules-2027). This site could not inspect that form-gated manual in full. It uses the [official Codebusters event page](https://www.soinc.org/codebusters-c) and its linked [2026–27 cipher summary](https://ncc.toebes.com/codebusters/Rule-Summary-2027.html) to label the lessons. The full manual and later [official clarifications or corrections](https://www.soinc.org/events/submit-question-and-rule-clarifications) take precedence.

Caesar is taught as a foundation exercise, not labeled a listed 2027 Division C type. Ordinary Morse prepares students for Fractionated Morse. The short puzzles simplify contest problems and are not official test questions. Requirements can vary by tournament level.

## Teacher-recommended resources

- [Puzzle Baron cryptograms](https://cryptograms.puzzlebaron.com/play.php) for monoalphabetic substitution practice.
- [Toebes Codebusters tools](https://toebes.com/codebusters/index.html) for practice generation and solving guides.
- [Scio.ly 2027 study guide](https://www.scio.ly/guides/codebusters) for cipher chapters and strategies.
- [Toebes Codebusters Overview PDF](https://toebes.com/codebusters/Samples/CodeBusters_Overview.pdf), updated for 2026–27 and containing historical material to distinguish from current scope.

The site's Resources page also links videos listed by Science Olympiad or the Toebes tool site. Older videos are labeled by season and do not replace current rules.
