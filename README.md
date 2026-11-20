# Police Chief Field Manual

Alliance guide for the mobile game Police Chief (TX1, State 171).

Read it here: https://thevibeguy44.github.io/Police-Chief-Mobile-Guide/

Game art belongs to the game's developer.

## Contributor of the week

The block on the home banner reads `contributor.json`:

```json
{"name": "[TSR] Darth Ranger", "img": "img/contributor-2026-11-19.webp"}
```

Put the player's in-game profile picture in `img/` under a new file name each week (so phones do not keep showing the old one), then set `name` and `img`. The picture shows whole, frame included; add `"round": true` to crop a plain picture to a circle instead. Leave `name` and `img` empty to hide the block. The site picks up the change within about ten minutes.

## Contributors page

The leaderboard at `#contributors` reads `contributors.json`, a list of players:

```json
[
  {"name": "[TSR] Darth Ranger", "state": "171", "points": 1, "img": "img/contributor-2026-11-19.webp"}
]
```

The page sorts by `points` and puts the top three on the podium. `img` is optional (players without one get their initial). Add a player or raise their points and the site shows it within about ten minutes.

Scoring, counted once a change is in the guide (first sender gets the points if two players send the same thing):

- Adding missing info: 4 to 20 points, depending on how much it adds
- Correcting something wrong: 5 points
- Pointing out something useless that gets cut: 3 points
- Art for an icon, banner or section: 2 points
- Layout fix: 1 point
- Wording and typo fixes: no points

Every award is written down in `points-log.md`. The player with the most points in a week (Monday to Sunday, UTC) is the next Contributor of the Week.
