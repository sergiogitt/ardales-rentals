# Ardales Rentals — Sitio web Astro

Web para alquiler vacacional de 3 propiedades en Ardales, Málaga.

## 🚀 Inicio rápido

```bash
# Instalar dependencias
npm install

# Servidor de desarrollo (http://localhost:4321)
npm run dev

# Build de producción
npm run build

# Preview del build
npm run preview
```

## 📁 Estructura del proyecto

```
ardales-rentals/
├── public/
│   ├── favicon.svg
│   └── robots.txt
├── src/
│   ├── components/
│   │   ├── Nav.astro          # Navegación (sticky, responsive)
│   │   ├── Footer.astro       # Pie de página
│   │   └── PropertyCard.astro # Tarjeta de propiedad
│   ├── data/
│   │   └── properties.ts      # ⭐ DATOS DE LAS PROPIEDADES
│   ├── layouts/
│   │   └── Layout.astro       # Layout base con SEO completo
│   └── pages/
│       ├── index.astro              # Página principal
│       ├── propiedades/
│       │   ├── index.astro          # Listado de propiedades
│       │   └── [slug].astro         # Página individual (dinámica)
│       ├── sobre-ardales/
│       │   └── index.astro          # Página SEO sobre Ardales
│       └── contacto/
│           └── index.astro          # Formulario de contacto
└── package.json
```

## ✏️ Personalizar las propiedades

Edita `src/data/properties.ts` para cambiar:
- Nombres, descripciones y taglines
- Precios, capacidades y características
- Ubicaciones y colores de acento

## 🔍 SEO incluido

- Meta tags completas (title, description, canonical)
- Open Graph para redes sociales
- JSON-LD structured data (LodgingBusiness)
- Geo meta tags (región ES-MA, Málaga)
- Robots.txt
- Sitemap automático (configura `@astrojs/sitemap`)
- Keywords en español para Ardales + turismo rural Málaga

## 📧 Formulario de contacto

El formulario en `/contacto` está listo para Netlify Forms.
Para otras plataformas, conecta a tu servicio preferido (Formspree, EmailJS, etc.)

## 🌐 Despliegue

Compatible con: Netlify, Vercel, Cloudflare Pages, y cualquier hosting estático.

```bash
npm run build
# Sube la carpeta dist/ a tu hosting
```

## 🎨 Paleta de colores

- Terracota: `#c4603a` (acento principal)
- Oliva: `#6b7c4a` (naturaleza)
- Tierra: `#3d2b1f` (texto principal)
- Arena: `#f5f0e8` (fondos)
- Piedra: `#9e9188` (textos secundarios)
