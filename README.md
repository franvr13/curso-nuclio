# Curso Nuclio - Gestor de Plantas 🌿

Este proyecto es una aplicación web construida con Next.js y TypeScript como parte de un curso de Nuclio. Su objetivo es mostrar una interfaz moderna para gestionar información sobre plantas, incluyendo visualización y detalles mediante una API integrada.

## 🛠 Tecnologías utilizadas

- [Next.js](https://nextjs.org/)
- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [ESLint](https://eslint.org/)
- API REST con rutas App Router (`/api/plants`)

## 📁 Estructura del proyecto

├── public/ # Archivos estáticos (SVGs)
├── src/
│ └── app/
│ ├── components/
│ │ ├── PlantList.tsx # Componente que lista las plantas
│ │ └── PlantModal.tsx # Componente modal con información detallada
│ ├── api/
│ │ └── plants/
│ │ └── route.ts # Ruta de API para obtener plantas
│ ├── page.tsx # Página principal
│ ├── layout.tsx # Estructura común de la app
│ └── globals.css # Estilos globales
├── package.json
├── tsconfig.json
├── next.config.ts
└── .gitignore

## 🚀 Cómo ejecutar el proyecto

Clona el repositorio y ejecuta el servidor de desarrollo:

- git clone https://github.com/franvr13/curso-nuclio.git
- cd curso-nuclio
- npm install
- npm run dev
- La aplicación estará disponible en *http://localhost:3000*

## 📦 Scripts útiles

- npm run dev: inicia el entorno de desarrollo
- npm run build: construye la aplicación para producción
- npm run lint: ejecuta ESLint para verificar errores de estilo/código

## ✨ Características

- Arquitectura modular y escalable con App Router
- Interfaz moderna y responsive
- Componente Modal reutilizable
- API interna con datos de ejemplo

## 📄 Licencia

- Este proyecto es parte de un curso formativo y no está destinado a producción. Uso libre con fines educativos.
