# Game favicons

One square favicon per game, used as the circle-cropped game icon in the site's creator view.
Name the file after the game, lowercase, no spaces, `.png`:

| game | file | status |
| --- | --- | --- |
| Katami | `katami.png` | todo |
| Bubblefish | `bubblefish.png` | todo |
| Book Wyrm | `bookwyrm.png` | wyrm sprite from the game (placeholder) |
| Octane | `octane.png` | todo |
| 250 is... | `250is.png` | todo |
| Sumo Square | `sumosquare.png` | todo |
| Learn to Count | `learntocount.png` | todo |
| Masknum Opus | `masknumopus.png` | todo |
| Molith | `molith.png` | todo |

A game without a favicon falls back to its thumbnail. To use one, set `"favicon"` on the game in
`beetlebox-studios.github.io/data/games.json` to its raw URL under `favicons/`.
