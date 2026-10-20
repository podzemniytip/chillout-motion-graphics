# Attribution and modifications

This project adapts the MIT-licensed [Mort1d/motion-graphics-skills](https://github.com/Mort1d/motion-graphics-skills),
based on source commit `7f0c3714dc81bea52644a5287c6350345009e579`.

The original MIT license and copyright notice are preserved in [LICENSE](LICENSE). The bundled Montserrat and
JetBrains Mono fonts have their own SIL Open Font License 1.1 notice in
`skills/chillout-motion-graphics/assets/template/assets/fonts/OFL.txt`.

The project renames the skill to `chillout-motion-graphics` and changes its default music direction to chillout,
chillhop, ambient and downtempo, with matching genre cards and sound suggestions. It also carries a local FFmpeg
compatibility change in `skills/chillout-motion-graphics/scripts/ref-sheet.mjs` (`-vsync vfr` to `-fps_mode vfr`).
