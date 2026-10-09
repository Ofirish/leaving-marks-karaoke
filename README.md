# Leaving Marks karaoke

Download the zip, unzip it, and open index.html in a browser.

## v2: vocal-track switch (English / Yiddish / none)

Download `karaoke_leaving_marks_v2.zip`, unzip it, and open `index.html`. You can also open `karaoke_leaving_marks_v2/index.html` from a clone of this repo.
- The 🎤 menu switches between English vocals, Yiddish vocals (synthetic) and no vocals (instrumental only). The selected track stays in sync with the instrumental.
- When "Lyrics follow vocal track" is on (Look → Audio), switching the vocal track also switches the lyrics. You can still choose English, Yiddish, both or none by hand.
- Keys: Space = play/pause, V = cycle vocal track, L = cycle lyrics, ←/→ = ±5 s.

## Yiddish preview (synthetic)
- `leaving_marks_yiddish_preview.mp3`: the full song with a synthetic Yiddish vocal over the instrumental.
- `leaving_marks_yiddish_excerpt_0m46-1m46.mp3`: a 60-second excerpt.

How it was made: the Yiddish lyrics were transliterated and read by a German TTS voice (MMS-TTS deu). Each line was then
time-mapped onto the original sung line, and the original vocal's pitch contour was imposed on it (WORLD vocoder) with reverb added.
This is a robotic, best-effort preview, not a real singer.
