# cartasyamigos-ota

Archivos que la app Cartas y Amigos lee sin publicar otra versión (un «OTA» pequeño), servidos por GitHub Pages:
`https://carlos-carmona-777.github.io/cartasyamigos-ota/app/<archivo>`.

- `app/avisos.json`: los avisos del carrusel del Inicio y las portadas de los mosaicos (`RemoteBanner.swift`).
- `app/dificultad.json`: el ajuste de dificultad de los personajes (`DifficultyTuning.swift`).

No se edita aquí: la copia de trabajo y el formato están en el repo de la app, `Arte/Avisos/` (`LEEME.md`), y se
publica con `Arte/Avisos/publicar.sh`, que revisa los archivos antes de subirlos y reemplaza toda la carpeta `app/`.

GitHub Pages tarda un minuto en publicarlo y guarda cada archivo en caché 10 min. **Este repo es público**: nada de
correos personales, claves ni datos privados.
