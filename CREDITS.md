# Credits

## Wallpaper

The wallpapers in `backgrounds/` come from one Guofeng (国风) night landscape:
deep jade sky, carved emerald peaks, gold-leaf ridges, red-crowned cranes, a
gilded pine and a distant pavilion. It is the night companion to the artwork in
[Jade Crane Light](https://github.com/rafalyovson/omarchy-jade-crane-light-theme).

It was provided by the theme author for redistribution with this theme under
the same MIT license as the palette and packaging files. The 1672×941 source
was upscaled 4× with [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)
(`realesrgan-x4plus`) to 6688×3764, the resolution of Omarchy's stock
wallpapers. `02-crane-flight-dark.webp` and `unlock.png` are crops of that
upscale. The intros in `backgrounds/intros/` are rendered from the same upscale
with ffmpeg (blur, reveal and a slow sub-pixel settle, no new art).
`omarchy.webp` recolors Omarchy's logo wallpaper to this palette. If you fork
the theme and replace the wallpaper, update this file.

## Palette

Colors were sampled from the wallpaper (night sky `#011712`–`#07231a`, jade
`#325b48`, gold leaf `#c6a972`, crane white `#d4c6a7`, crane crown `#b03425`)
and tuned to WCAG AA contrast on the midnight background.

## Icons

GTK icons: `Yaru-sage` (bundled with Omarchy / Yaru).
