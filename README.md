# Lesson 32 — Studio Ghibli: The Studio That Draws by Hand 🎬

Playful-Detective teaching pack for a one-hour online English lesson (Grade 4/5): an information text about Studio Ghibli, then **synonyms & antonyms**, **past participles**, **reading a film poster** and **ten spelling words**.

**Open `index.html`**, or publish this folder with GitHub Pages and it works as a website.

| File | What it is |
| --- | --- |
| `index.html` | Home page linking the lesson and all three games |
| `lesson-32-studio-ghibli.html` | The 22-slide lesson (arrow keys, thumbnail rail, ⛶ Present, print to PDF) |
| `acorn-catch.html` | Catch acorns, leaves and stars; dodge storm clouds and whirlwinds. 3 lives |
| `whack-an-acorn.html` | 60-second whack-a-mole with acorns. Avoid the prickly chestnut |
| `forest-maze.html` | Random mazes that grow every level. Tap a direction or use the arrows |

## Publishing on GitHub Pages

1. Upload **everything in this folder**, including the sub-folders and the `.nojekyll` file, to the root of a repository.
2. Settings → Pages → Source: *Deploy from a branch* → branch `main`, folder `/ (root)` → Save.
3. After a minute, open `https://<your-username>.github.io/<repo-name>/`.

Everything is static and uses **relative paths only**. There's no build step and no server code.

**If something won't open:** GitHub is case-sensitive, so keep every file and folder name exactly as it is (all lowercase, no spaces). Make sure the `ghibli/`, `stickers/`, `fonts/` and `slides/` folders were uploaded too.

## Folders

- `ghibli/` — lesson pictures
- `stickers/` — cat illustrations
- `fonts/` — Bowlby One SC + Quicksand, self-hosted
- `slides/deck-stage.js` — the slide-deck engine
- `*.css` — Playful Detective tokens and lesson skins (`lesson32.css` is this lesson's theme)
