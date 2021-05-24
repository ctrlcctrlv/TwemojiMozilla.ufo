# Twemoji UFO

This is a UFO of the Twemoji font.

It was generated with the patch I wrote to [`robotools/extractor`](https://github.com/robotools/extractor), [PR №41](https://github.com/robotools/extractor/pull/41).

It does build with `fontmake` without changes. Example command line:

```bash
fontmake --verbose DEBUG -u TwemojiMozilla.ufo --keep-overlaps --output ttf --output-path Twemoji.ttf
```
