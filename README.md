# Anarely Padilla — Psicóloga Infantil

Landing page construida con [Astro](https://astro.build) y [Tailwind CSS](https://tailwindcss.com).

## Estructura

```text
/
├── public/              # Favicon y assets estáticos
├── src/
│   ├── components/       # Header, Hero, Features, Specialties, About,
│   │                      # Pricing, Testimonials, Resources, FAQ,
│   │                      # Newsletter, Contact, Footer
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css    # Tema Tailwind (colores, tipografías)
└── package.json
```

## Comandos

| Comando           | Acción                                       |
| :----------------- | :-------------------------------------------- |
| `npm install`       | Instala dependencias                          |
| `npm run dev`       | Inicia el servidor local en `localhost:4321`  |
| `npm run build`     | Genera el sitio de producción en `./dist/`    |
| `npm run preview`   | Previsualiza el build de producción           |

## Pendientes antes de publicar

- Reemplazar las fotografías de stock (Unsplash) por fotos reales del consultorio y de Anarely.
- Completar datos reales de contacto en `src/components/Header.astro` y `src/components/Contact.astro` (teléfono, correo, dirección).
- Completar credenciales reales (universidad, cédula profesional) en `src/components/About.astro`.
- Definir tarifas reales en `src/components/Pricing.astro`.
- Conectar los formularios de contacto y newsletter a un servicio real (por ejemplo, un endpoint, Formspree, o un CRM).
