# spotify_status
This is a little python script which outputs the current playing song to stdout.\
The tool waits for a notfication by Spotify and asks for the metadata of the current song.

### Dependencies
* Python (2.x or 3.x)
* Python `dbus`
* Python `gi.repository`

### Example usage: [Polybar](https://github.com/jaagr/polybar)
```ini
[module/spotify]
type = custom/script
exec = python /path/to/script/spotify_status.py
format = <label>
```
