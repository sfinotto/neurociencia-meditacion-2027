# Neurociencia y Meditación — Buenos Aires 2027

Sitio estático creado con Astro para los encuentros de Yongey Mingyur Rinpoche en Buenos Aires.

## Requisitos

- Node.js 20+ recomendado
- npm

## Ejecutar localmente

```bash
npm install
npm run dev
```

Abrí la URL que indique Astro, normalmente:

http://localhost:4321

## Generar producción

```bash
npm run build
```

El sitio generado queda en:

dist/

## Vista previa de producción

```bash
npm run preview
```

## Cloudflare Pages

Conectá este repositorio a Cloudflare Pages y usá:

- Framework preset: Astro
- Build command: npm run build
- Build output directory: dist

No necesita adapter de Cloudflare porque este proyecto es completamente estático.

## Antes de publicar

Reemplazar:
- la URL `https://example.pages.dev` de `astro.config.mjs`
- el bloque de fotografía por una imagen autorizada
- la información de sede cuando sea confirmada
- el enlace de inscripción cuando esté disponible

Los textos de los dos encuentros se basan en la gacetilla de prensa suministrada.
