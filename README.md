# Web de Siafu

Landing page promocional de **Siafu**, la herramienta de pruebas de carga por terminal configurada con YAML y escrita en Go.

- Página publicada: `index.html`
- Versión de Siafu: v0.4.2
- Repositorio del proyecto: <https://github.com/gac982/siafu>
- English: [README.en.md](README.en.md)

## Ver la página

Es un único archivo autocontenido: ábrelo directamente en el navegador.

```bash
# opción 1: abrir el archivo
xdg-open index.html

# opción 2: servir en local
python3 -m http.server 8000
# http://localhost:8000
```

No necesita build, servidor ni conexión: todo el HTML, CSS y JavaScript está inline. La única dependencia local es `assets/logo.png`, que se usa como favicon y `og:image`.

## Estructura

```text
index.html        página completa (HTML + CSS + JS inline)
assets/logo.png   logo de Siafu (favicon / og:image)
README.md         este archivo (español)
README.en.md      README en inglés
```

## Diseño

- Paleta de cuatro colores de la TUI: Ink `#0E1116`, Bone `#E6E1D6`, Ember `#FC4C02`, Ash `#7A8394`.
- Tipografía editorial (serif tipo Times) para títulos; sans del sistema para cuerpo; mono para código y terminal.
- Móvil-first, sin sombras ni degradados, con bordes de 1px.
- Simulador de la TUI, explorador YAML con resaltado propio y copiado al portapapeles, todo en JavaScript vanilla.

## Licencia

El contenido de esta página describe Siafu, que se distribuye bajo AGPL-3.0-or-later.
