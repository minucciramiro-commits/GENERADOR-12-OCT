# Generador · Museo Evita Palacio Ferreyra

Sitio estático de un solo archivo (`index.html`). No necesita build.

## Subir a Vercel

**Opción A, arrastrar:** entrá a vercel.com/new, elegí subir una carpeta y arrastrá esta carpeta. Framework: "Other". Sin comando de build. Deploy.

**Opción B, con la terminal:**

```
npm i -g vercel
cd museo-evita-generador
vercel --prod
```

## Notas
- Las fuentes vienen de Google Fonts y el .zip usa JSZip desde cdnjs, así que necesita internet.
- Las descargas (SVG, PNG y .zip) funcionan directo desde el navegador.
