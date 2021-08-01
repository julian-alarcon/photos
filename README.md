# Photography by Julian Alarcon

A website with some of my photos.

## Resize for publishing

Using imagemagic (`sudo apt install imagemagick`)

```sh
mogrify -resize "2160x2160>" *.jpg
```

## Resize for thumbnails

Using imagemagic (`sudo apt install imagemagick`)

```sh
mogrify -resize "512x512>" *.jpg
```

### Credits

Based on [https://github.com/rampatra/photography](https://github.com/rampatra/photography)
