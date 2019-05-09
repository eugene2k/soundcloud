Create and download playlists from soundcloud tracks

usage: scloud MODE [ARGS]

Modes:
   tracks         Get tracks
   playlists      Get playlists

Optional tracks mode arguments:
  -u USER                       The username or user id of the author
  -p PID                        The playlist id
  -q QUERY                      Search for tracks containing query
  -t TAG1,TAG2...,TAGN          Filter by tags
  -g GENRE1,GENRE2...,GENREN    Filter by genre
  -f PATH                       Output the track list into an m3u playlist file

Optional playlists mode arguments:
  -u USERNAME                   The username of the author
  -q QUERY                      Filter out playlists that don't match the query
  -d DIR                        Save playlists in the specified directory


