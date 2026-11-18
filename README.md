# Sparkle Sums 🦄

A unicorn-and-rainbow game for memorizing arithmetic facts, made for a tablet.

**Play it: https://royceness.github.io/sparkle-sums/**

## What it does

A question appears with six possible answers and a countdown timer. The child taps the right one. Questions come in sprints of about ten, with points, streaks, stickers and celebrations that get bigger the better they do.

Pick what to practise on the home screen:

| Mode | Facts |
|---|---|
| Addition | 1–20 + 1–20 (210 facts) |
| Subtraction | a − b for numbers 1–20, never negative (210 facts) |
| Multiplication | tables 1–12 (78 facts) |
| Division | the tables backwards, up to 144 ÷ 12 (144 facts) |
| All | takes turns between the four |

## How it teaches

- **Each fact has its own timer.** It starts at 20 seconds, then 15, 10 and 5. A right answer makes the timer shorter next time; a wrong answer or a time-out makes it longer.
- **Memorized means fast, three times running.** A fact counts as memorized after three right answers in a row within 5 seconds, whatever timer was showing.
- **Easy facts come first.** New facts are introduced a few at a time, and memorized ones come back for review.
- **Misses are gentle.** The right answer is shown, and the fact is asked again later in the same sprint.

A gentler timer setting (30, 20, 12 and 8 seconds) is on the Progress screen.

## For grown-ups

The Progress screen shows every fact as a coloured grid, a list of the facts that need more practice, and a practice log.

- **Everything stays on the device.** Progress and the log are kept in the browser's local storage. Nothing is sent anywhere, and there are no accounts, ads or analytics.
- **Practice log.** Every answer is recorded: the question, the choices, what was tapped, how long it took. Two buttons copy it to the clipboard, with an explanation of the columns at the top, ready to paste into an AI assistant or a spreadsheet.
- **Erasing progress** needs an adult's year of birth and the answer to a sum.

## Putting it on an iPad

Open the link above in Safari, tap Share, then Add to Home Screen. The game then opens full-screen like an app. Always play from that icon so progress stays in one place.

## Running it yourself

The whole game is one file, `index.html`, with no build step and no dependencies. Open it in a browser, or serve the folder:

```bash
python3 -m http.server 8765
```

Then go to `http://localhost:8765`.

## License

MIT. See [LICENSE](LICENSE), and [NOTICE.md](NOTICE.md) for what it covers.
