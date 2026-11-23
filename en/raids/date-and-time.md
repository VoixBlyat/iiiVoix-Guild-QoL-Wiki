# Enter a date and time

[🇩🇪 Deutsch](../../raids/zeiten.md) · 🇬🇧 English

The raid form has two fields:

- **Date or Now:** Enter a date or “Now.”
- **Start time:** Enter when the raid should begin.

## The raid starts now

If the raid should start right away:

- **Date or Now:** `Now`
- **Start time:** leave empty

The bot shows the raid as starting now.

## The raid starts later today

Example: It is afternoon and you want to start at 20:30 today.

- **Date or Now:** `Now`
- **Start time:** `20:30`

The time must still be in the future. A time that has already passed today is rejected.

## The raid is on another day

Enter the date as `DD.MM` or `DD.MM.YYYY`. Keep the dots.

Example: December 25, 2026, at 20:30:

- **Date or Now:** `25.12.2026`
- **Start time:** `20:30`

You can leave out the year. For `25.12`, the bot picks the next matching date. A date always needs a time.

## Enter a start and end time

You can enter both times, for example:

- **Start time:** `20:30-21:00`

This means the raid starts at 20:30 and is planned to end at 21:00. It does **not** mean the raid starts at some point between 20:30 and 21:00.

The end time must be later than the start time and on the same day. So `21:00-20:30` is not valid.

## Common mistakes

- `25/12` does not work—use dots: `25.12`.
- A date without a time is not accepted.
- Past dates and times are not accepted.
- Use the 24-hour format: `20:30`, not `8:30 PM`.

The time shown in the raid post follows the time zone configured for the bot. If you are unsure, ask in the server.