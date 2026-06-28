# Material promocional — Aetheria

Assets para promocionar el juego en redes, README, itch.io, tiendas, etc.
Todos generados a partir del juego **real** ejecutándose (sin mockups).

| Archivo | Uso recomendado | Detalle |
|---|---|---|
| `banner.png` | Portada / social card (1280×640) | Banner con título, fondo del mundo y tags |
| `promo_full.mp4` | Video promo principal (~11s) | Exploración + comandos + combate |
| `gameplay.mp4` | Clip de exploración (~7.5s) | Movimiento, `ls`, NPCs, leer carta, viajar |
| `gameplay.gif` | GIF para README/redes | Versión animada del clip de exploración |
| `combat.mp4` | Clip de combate (~4s) | `ps`, `kill <PID>`, daño flotante, partículas |
| `combat.gif` | GIF de combate para README/redes | Versión animada del combate |

## Sugerencias de uso

- **GitHub README**: usa `banner.png` arriba del todo y `gameplay.gif` / `combat.gif` en la sección de features.
- **Twitter/X / Bluesky**: `banner.png` como imagen de card; sube `promo_full.mp4` como video nativo.
- **itch.io**: `banner.png` como cover (recorta a 630×500 si hace falta), `promo_full.mp4` como trailer.

## Cómo se regeneran

Los assets se capturan automáticamente con Chrome headless + ffmpeg, conduciendo
el juego real por comandos y movimiento, luego ensamblando los frames.
