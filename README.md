# Photography by Julian Alarcon

A website with some of my photos.

## Resize for thumbnails

Using imagemagic (`sudo apt install imagemagick-6.q16`)

```sh
convert "*.jpg[512x]" -set filename:base "%[basename]" "%[filename:base].jpg"
```

### Credits

Based on [https://github.com/rampatra/photography](https://github.com/rampatra/photography)
