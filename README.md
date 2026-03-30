# chispas

Pizarrón táctico de voleibol (sitio estático) para visualizar rotaciones, jugadas y recepción.

## Ejecutar en local

Como es una app estática, basta abrir `index.html` en el navegador.

También puedes usar un servidor simple:

```bash
python -m http.server 8080
```

Luego abre `http://localhost:8080`.

## Deploy en Vercel

Este repo queda listo para Vercel como proyecto estático:

1. Importa el repositorio en Vercel.
2. Framework preset: **Other**.
3. Build command: *(vacío)*.
4. Output directory: `.`.

El archivo principal es `index.html` en la raíz.

## Auditoría rápida antes de subir

- Confirmar que `index.html` existe en la raíz.
- Abrir la app y validar:
  - Cambio de tácticas desde sidebar.
  - Controles `Prev / Auto / Next` sin errores en consola.
  - Redimensionar ventana y confirmar que el canvas no se deforma.
- Verificar deploy preview en Vercel sin configuración adicional.
