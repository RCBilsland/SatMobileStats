# SatMobileStats

Local analysis and map playback for a satellite/mobile drone test over public marshland.

## Live viewer

https://rcbilsland.github.io/SatMobileStats/

Or open `track_viewer.html` locally (needs `track_points.js` beside it).

## Rebuild the viewer

```bash
python3 merge_timeseries.py
python3 make_track_viewer.py
```
