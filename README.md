# Aprilon — Rutas Eficientes (landing)

Landing page del proyecto final **Aprilon · Rutas Eficientes** (Tecnicatura en Informática, 2026).
Enfoque híbrido: mitad producto, mitad proyecto académico.

Es una sola página estática (`index.html`), sin dependencias ni build. La única fuente externa es la tipografía Manrope de Google Fonts.

## Publicar en GitHub Pages

El repositorio **tiene que ser público** para que Pages funcione en el plan gratuito.

```bash
cd "C:\Users\Equipo\Downloads\aprilon-landing"
git init
git add .
git commit -m "Landing de Aprilon Rutas Eficientes"
gh repo create aprilon-rutas-eficientes --public --source=. --push
```

Después, en el repo: **Settings → Pages → Source: Deploy from a branch → main / (root)**.
La página queda en `https://<usuario>.github.io/aprilon-rutas-eficientes/`.

## Antes de publicar

- [ ] Completar la sección **Equipo**: los cinco nombres reales, su rol y las iniciales del avatar. En el HTML está marcada con un recuadro punteado y la palabra PENDIENTE.
- [ ] Si hay foto grupal, reemplazar la grilla de avatares por la foto.
- [ ] Si hay logo de la empresa, reemplazar el punto verde del encabezado.
- [ ] Revisar que el texto de la sección "El proyecto" coincida con lo que se va a presentar.

## Estructura

- `index.html` — la página completa (estilos incluidos).
- No hay build, ni `node_modules`, ni configuración: lo que ves es lo que se publica.
