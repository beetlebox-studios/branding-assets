# Game favicons

One square favicon per game, used as the circle-cropped game icon in the site's creator view.
Name the file after the game, lowercase, no spaces, `.png`:

| game | file | status |
| --- | --- | --- |
| Katami | `katami.png` | todo |
| Bubblefish | `bubblefish.png` | todo |
| Book Wyrm | `bookwyrm.png` | worm sprite from the game |
| Octane | `octane.png` | todo |
| 250 is... | `250is.png` | todo |
| Sumo Square | `sumosquare.png` | todo |
| Learn to Count | `learntocount.png` | todo |
| Masknum Opus | `masknumopus.png` | todo |
| Molith | `molith.png` | todo |

The game's logo from `logos/` is always its first sticker. A game can have several more (`name.png`, `name_2.png`, ...). Games with stickers show them
as outlined stickers (no circle, no label) in the site's creator view and in the middle of the right
panel when the game is selected. A game without any falls back to its thumbnail in a circle.
Set `"favicons"` (a list of raw URLs under `favicons/`) on the game in
`beetlebox-studios.github.io/data/games.json`.
