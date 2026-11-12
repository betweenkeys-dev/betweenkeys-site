# Between Keys games

Short browser games that teach the ideas in Between Keys Key Notes.

## Folders

- `games/` holds the games page and one folder per game. Each game is a single `index.html`.
- `data/` holds one facts file per Key Note. `stay-shift-step-back.json` feeds the Stay, Shift or Step Back games.
- `games/assets/` holds the icons for the games pages.

## Updating numbers

Open `data/stay-shift-step-back.json`, change the `display` text and `value` for a fact, update its `as_of` date, and update `last_checked` in `meta`. If a source changed, update it under `sources`. Games read this file live, so no code changes are needed. If a new number changes which answer is right, update that card's `choices` too.

## Turning on feedback

Paste the feedback script's web address (it ends in `/exec`) between the quotes of `feedback_url` in the `meta` section of the facts file.

Questions from Between Keys. Research and explanations by my AI assistant.
