# Orders

This repo contains the pixels to be placed by the bot. Pixels that are first in the list are tried first. So when attacked, put **at the front** of the list.

## Format

Orders are generated with the `reference.py` script, with `reference.png` as reference.

![reference](reference.png)

`orders.json` uses a fairly simple format. It is an array, consisting of arrays with three items.

- 0: the x-coordinate of the pixel
- 1: the y-coordinate of the pixel
- 2: the color of the pixel, see mapping below

`[x, y, color],`

Example:

```
[0, 0, 2],
[0, 1, 31],
[0, 2, 12]
```

Color-mapping:

![color-mapping](colors.png)
