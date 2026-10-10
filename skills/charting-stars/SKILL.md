---
name: charting-stars
description: Calculate birth charts, current sky, horoscopes and compatibility with Charting Stars.
---

# Charting Stars

Use the connected Charting Stars tools for calculations. Do not estimate planet positions yourself.

For a natal chart, get the birth date, recorded local time and birthplace.
If the person does not know the time, set `time_unknown: true`.
If the time is missing, ask before casting. Do not substitute noon or guess a rising sign.
If the birthplace is ambiguous, show the returned candidates and use the selected `place_id`.
If a clock time occurs twice, ask which occurrence to use before passing `time_choice`.

Report the Sun, Moon and rising signs, then the placements relevant to the request.
Retain the returned uncertainty limits. Distinguish calculated positions from interpretation.
Treat astrology as reflection and entertainment. Do not predict events or give medical, legal or financial advice.

Use `current_sky` for current planetary positions and Moon phase.
Use `daily_horoscope` for a Sun-sign horoscope. State that it is not personalized to a full natal chart.
If the person's local date is known, pass it as `date`. Otherwise, explain that the default date uses UTC.
Use `sign_compatibility` for two signs, and explain that this does not compare two full charts.

Only use tools available in the connected server. The ChatGPT server has four free tools and no commerce.
