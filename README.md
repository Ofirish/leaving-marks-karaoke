# Leaving Marks karaoke

## v4: practice mode for learning the Yiddish (folder `docs/`, works on phones)
Open `docs/index.html` locally, or use the GitHub Pages link once it is enabled (Settings > Pages > Deploy from branch `main`, folder `/docs`).
- Yiddish vocal guide plus Yiddish and Latin transliteration lines shown together (the transliteration is approximate; the lyrics menu also has Yiddish + English).
- Speed 0.5x to 1x with the pitch kept, so you can learn the line slowly and then speed up.
- Loop line (R): repeats the current line. Tap any lyric line to jump to it. Previous and next line buttons (P / N).
- Record yourself (use headphones), then "My take" plays your voice over the music at the same speed.
- The screen stays awake while playing. Audio is compressed (about 15 MB in total, down from 44 MB).


**Latest: `karaoke_leaving_marks_v3.zip`.** Unzip it and open `index.html`. The layout works on phones (portrait and landscape), laptops and desktops.

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

## v3: responsive layout
- A compact bar is always visible: seek + time, Play, vocal track (English / Yiddish / none), lyrics (EN / YI / both / none) and ⚙.
- ⚙ opens a scrollable settings drawer with vocal/music volume, lyrics-follow, sync offset, fullscreen, background, colours and text size. Close it with ✕, Esc or a tap outside.
- The lyrics area scrolls if the text is too tall. Text size adapts to the screen.
- Tested in headless Chrome at 390x844, 844x390, 1280x720 and 1920x1080. Every control is reachable at each size.
