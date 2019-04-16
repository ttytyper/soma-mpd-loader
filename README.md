# Lists and plays Soma FM radio stations through mpd

List available channels:

    soma

Play channel(s):

    soma [grep options] search

`search` is matched against the playlist url, the station id, and the genre(s) of the channels

All loaded streams are shuffled before playing starts. This helps distribute server load.

Specifying a period (".") as the search string will load all stations. This
may be useful for a sort of jukebox with lots of genres in random order.

[Screenshot](screenshot.png)
