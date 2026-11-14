# mk-news-image

[![make.fun · news-image-01](https://make.fun/badge/news-image-01.svg)](https://make.fun/bounty/news-image-01)

One image summing up the world's news of Friday 13 November 2026, drawn by a single Python 3.13
program with the standard library only. It sets a newspaper front page: a masthead, the day's
lead story in the largest type, a world map window pinning where the stories happened, three
regional columns, and a ticker. The type is drawn by a stroke font defined in `font.py`, so
there is no font file and no dependency.

## Run it

```sh
python3 main.py out.png
```

No network, no clock, no randomness: two runs write byte-identical files.
