# Friend Group Tap One

A free, static Tap One game for GitHub Pages.

## Included
- 10 fixed categories, each with its own ranked pool of 9 options.
- All unlocked category wheels spin simultaneously for 3.5 seconds.
- All wheels stop together; the player locks exactly one category per round.
- Locked categories never spin again.
- Points: rank 1 = 100, rank 2 = 90, ... rank 9 = 20.
- Independent progress saved in each player's own browser using localStorage.
- Responsive layout for phones and computers.

## Run locally
Open `index.html` in a modern browser.

## Publish free with GitHub Pages
1. Sign in to GitHub and create a new **public** repository, e.g. `friend-group-tap-one`.
2. Upload `index.html` (and the `assets` folder when you add pictures) to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main`, folder `/ (root)`, and save.
6. GitHub will provide the public website URL after deployment.

## Adding photos later
The app is already prepared to look for `.jpg` photos using this folder pattern:

`assets/<category-slug>/<option-slug>.jpg`

Examples:
- `assets/strength/abu.jpg`
- `assets/speed/king-k-rool.jpg`
- `assets/media-knowledge/zainub.jpg`
- `assets/gaming-setup/suhaib.jpg`

The category and option slugs are lowercase, with spaces replaced by hyphens and punctuation removed. If a photo is missing, the game uses a text placeholder instead.

**Privacy:** GitHub Pages sites and files in a public repository are publicly accessible. Only upload pictures you have permission to share publicly. The game stores each player's progress locally in their own browser; it does not send scores to a shared leaderboard.
