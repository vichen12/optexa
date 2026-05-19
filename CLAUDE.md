# Optexa — CLAUDE.md

## Proyecto

Landing page de **Optexa**, construida con React + Vite. El directorio principal del proyecto es `optexa-landing/`.

## Stack tecnológico

- **Framework:** React 19 + Vite 6
- **Estilos:** Tailwind CSS v4
- **Animaciones:** Framer Motion, Spline (3D), react-parallax-tilt
- **Scroll suave:** Lenis (`@studio-freight/lenis`)
- **Iconos:** Lucide React
- **Despliegue:** Netlify (configurado en `optexa-landing/netlify.toml`)

## Estructura

```
optexa-landing/
├── src/
│   ├── components/   # Componentes React
│   ├── assets/       # Imágenes y recursos estáticos
│   ├── lib/          # Utilidades
│   ├── App.jsx       # Componente raíz
│   └── main.jsx      # Punto de entrada
├── public/           # Archivos públicos
├── index.html
├── vite.config.js
└── tailwind.config.js
```

## Comandos

```bash
cd optexa-landing

npm run dev       # Servidor de desarrollo (localhost:5173)
npm run build     # Build de producción → dist/
npm run preview   # Preview del build
npm run lint      # ESLint
```

## Convenciones

- Componentes en `src/components/`, un archivo por componente
- Tailwind para estilos; evitar CSS en línea salvo animaciones complejas
- Framer Motion para transiciones y animaciones de entrada
- Mantener el código limpio y sin dependencias innecesarias
