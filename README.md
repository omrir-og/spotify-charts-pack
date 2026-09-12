# spotify-charts-pack

Personal/friends chord pool for SpotifyChordOverlay.

## How it works
1. Add a chart file under `charts/` (JSON timed chart or ChordPro-ish text).
2. Add a row in `index.json` (`title`, `artist`, `file`, bump `version` when you edit).
3. Push to GitHub (public repo is fine for personal use).
4. In the app set `CHARTS_PACK_URL` to the raw base, e.g.
   `https://raw.githubusercontent.com/YOUR_USER/spotify-charts-pack/master`
5. On the phone: new/changed songs download automatically — no USB.

## Add a song
```json
{
  "title": "Rocket Man",
  "artist": "Elton John",
  "file": "charts/rocket_man.json",
  "version": "1"
}
```

Bump `version` whenever you change an existing file so devices pick up the update.

