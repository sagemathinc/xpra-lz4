# The MIT licensed Javascript LZ4 Compression from an old version of Xpra

UPDATE: https://github.com/williamstein/lz4-ts works VERY well, and is beautiful clean code.  I'm switching to that and obviously won't worry about this any further.

This code is copied straight from the upstream Xpra client code, but
with prettier formatting applied.

I couldn't find any npm modules that worked in the
browser and actually decompressed xpra's lz4 compressed data.
This does so and works VERY well/fast. However... it's really big.
Sorry. This should probably be loaded in a separate chunk or something.

TODO: I just hack setting window.lz4 down below! This is not robust,
but it works fine for now.

LICENSE: Xpra was Licensed under MPL 2.0.  This was the license of the frontend client when I copied this code from Xpra.  This code says:

```
* LZ4 based compression and decompression
* Copyright (c) 2014 Pierre Curto
* MIT Licensed
```
