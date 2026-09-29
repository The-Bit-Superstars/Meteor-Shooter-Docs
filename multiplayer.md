#### Format

Packet:

3B  \\xC2\\xB5\\xE3 (header)

16B username (max 16 chars, padded with \\x00)

idk user\_uuid (all \\xAB if not registered)

3B  ship\_skin (first 3 bytes of hash)

1B  shipX (1 byte)

