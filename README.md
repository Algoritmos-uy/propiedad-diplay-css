# propiedad-diplay-css

Pequeño proyecto didáctico que muestra ejemplos prácticos del comportamiento de la propiedad CSS `display`.

## Contenido

- `index.html` : página con ejemplos para los valores `block`, `inline`, `inline-block` y `none`.
- `style.css` : estilos del proyecto con comentarios didácticos que explican cada ejemplo.

## Objetivo

Este repositorio se usa para enseñar cómo funcionan distintos valores de la propiedad `display` en CSS. Incluye ejemplos visuales fáciles de inspeccionar desde las herramientas del navegador.

## Cómo usar localmente

Opciones rápidas para ver el proyecto en tu máquina:

- Abrir directamente:

  - Haz doble clic en `index.html` o ábrelo desde tu editor; el navegador cargará la página (modo archivo).

- Servidor local (recomendado para evitar problemas con importaciones relativas y CORS en algunos navegadores):
  - Con Python 3 instalado, desde la carpeta del proyecto ejecuta:

```powershell
# Servidor HTTP simple en el puerto 8000
python -m http.server 8000
```

    - Luego abre http://localhost:8000 en tu navegador.

## Qué observar en los ejemplos

- Block: cada elemento ocupa la línea completa y acepta width/height.
- Inline: los elementos fluyen en la misma línea; width/height no se aplican de la misma forma.
- Inline-block: se alinean en línea pero sí respetan width/height.
- None: el elemento se elimina del flujo y no ocupa espacio (distinto a `visibility: hidden`).

## Contribuciones

Puedes mejorar los ejemplos añadiendo controles interactivos (por ejemplo, botones para alternar `display`) o anotaciones visibles para estudiantes.

## Licencia

Usa el contenido libremente para enseñanza y adaptaciones. Si quieres una licencia formal, dime cuál prefieres y la añado.
