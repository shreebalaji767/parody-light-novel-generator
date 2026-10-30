# NovelForge — Light Novel Generator

A free, static, browser-based light novel and parody generator. No paid services, AI APIs, backend, database, accounts, ads, or external dependencies.

## Features
- Genre selection: isekai, fantasy, romance, action, school life, sci-fi, horror, comedy, cozy, and genre mashup.
- Chapter counts from **1 to 10,000**, including quick picks for 1,000+.
- Parody slider from 0% serious to 100% chaotic.
- Optional title, premise, and protagonist.
- Batch generation to keep the browser responsive.
- Manual save/load in browser storage (only when you click Save progress), optional auto-save if you enable it, and TXT, Markdown, and JSON export.
- Responsive UI for desktop and mobile.

## GitHub Pages
1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select your default branch and the **/(root)** folder, then save.
4. After GitHub finishes deploying, open the Pages URL shown there.

The site is plain HTML, CSS, and JavaScript. It requires no build step and can also be opened locally by opening `index.html`.

## How the generator works
NovelForge is a procedural story engine, not an AI model or human novelist. Its `narrative-engine.js` module runs entirely in the browser and uses seeded randomness, genre-specific scene material, character profiles, distinct dialogue patterns, plot threads, relationship state, recurring questions, and remembered consequences. Story state is stored with each novel so later chapters can build on earlier decisions. The generator makes no network or AI calls.

The narrative engine is designed to produce more coherent and varied stories than a simple paragraph-template loop, but it cannot understand arbitrary prompts or guarantee the originality, literary judgement, and long-range planning of a skilled human author. Generated chapters are approximately 900–1,000 words. Python is not required at runtime or for GitHub Pages hosting. Very large novels can use significant browser storage; export a copy as TXT/Markdown when needed.

## License
Released under the MIT License.
