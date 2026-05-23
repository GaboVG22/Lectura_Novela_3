# Lector Avanzado Sincronizado

Aplicación web/PWA estática para GitHub Pages.

## Mejoras incluidas en esta versión

- Traducción simultánea con reintentos automáticos y caché por frase.
- Fallback de traducción: Google público y MyMemory.
- Avance sincronizado con la voz: la app espera que termine la lectura antes de pasar a la frase siguiente.
- Resaltado palabra por palabra del avance de la traducción en la ventana principal de traducción.
- Se eliminaron los indicadores porcentuales de avance.
- Se ocultaron las ventanas inferiores de historial de lectura y traducciones generadas, manteniendo exportación y sincronización.
- - Modo alternativo por temporizador.
- Voz original y voz traducida pueden activarse por separado.
- Exportación Word del texto original o traducciones generadas.
- Service Worker corregido para funcionar en GitHub Pages con rutas relativas.
- Workflow `.github/workflows/deploy.yml` sin npm, sin Vite y sin proceso de build.

## Uso recomendado

1. Pegue o cargue el texto.
2. Elija inglés o alemán.
3. Inicie la lectura.
4. Active **Voz trad.** para que el texto traducido se vaya destacando palabra por palabra en la ventana principal de traducción.
5. Use **Avance por voz** para que la app espere el fin de la lectura antes de pasar a la siguiente frase.

## Subida a GitHub

Sube todo el contenido de esta carpeta al repositorio, incluyendo `.github`, `icons`, `index.html`, `manifest.json`, `sw.js`, `.nojekyll` y `README.md`.

Luego abre la pestaña **Actions**. Si aparece verde, entra a **Settings → Pages** y revisa el enlace publicado.
