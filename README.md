# sabere-landing

Landing page de **Saberé** — la plataforma que conecta a las familias con la educación de sus hijos.

## Stack

- [Astro](https://astro.build) 7 (sitio estático)
- [Tailwind CSS](https://tailwindcss.com) v4
- Node.js 22+

## Desarrollo

```sh
npm install
npm run dev      # servidor de desarrollo en http://localhost:4321
npm run build    # genera el sitio estático en dist/
npm run preview  # previsualiza el build de producción
```

## Despliegue

El build genera archivos estáticos en `dist/`, listos para servir con Nginx, Caddy o cualquier servidor web.
