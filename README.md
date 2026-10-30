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
This is a template-powered generator, not an AI model. It combines built-in genre-specific story structures, character roles, goals, locations, events, dialogue patterns, and parody beats. Text is generated locally in your browser.

**Note:** The generator produces structured, readable template-based stories. It does not provide the same free-form creativity, custom prompt understanding, or narrative continuity as a large language model. Very large novels can use significant browser storage; export a copy as TXT/Markdown when needed.

## License
Released under the MIT License.
