#### Format

Packet:

Bytes    Content

3B       \\xC2\\xB5\\xE3 (header)

16B      username (max 16 chars, padded with \\x00 at end)

idk      user\_uuid (all \\xAB if player not logged in)

3B       ship\_skin (first 3 bytes of hash)

1B       shipX (1 byte)

23+idkB  total

