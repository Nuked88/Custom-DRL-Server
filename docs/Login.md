# Login data (may be incomplete)
The game sends over a login token and a time stamp. The tokenis in base 64 and uses AES encryption to semd over player data. The key is ```09e027edfde3212431a8758576807083``` and the iv is the timestamp it sent. The token decodes into json and contains data such as a player id (UID), and a hash. The game is expecting the token back and also data encoded in base 64 that has "player-id" and expires.

## End Points
- /v2/login