# Portfolio de Ingeniería: Inteligencia Artificial y Computación Cuántica

## Descripción del Proyecto
Este repositorio contiene el código fuente de mi portfolio profesional. Está diseñado como una Single Page Application (SPA) para presentar mi perfil como estudiante de Ingeniería Informática, destacando mi especialización técnica en la intersección entre el desarrollo de algoritmos, la Inteligencia Artificial y la Computación Cuántica.

## Tecnologías Utilizadas
El proyecto está construido desde cero priorizando el rendimiento, la escalabilidad y el diseño responsivo:

* **Framework Core:** Astro
* **Sistema de Estilos:** Tailwind CSS (v3)
* **Lógica de Interfaz:** JavaScript (Vanilla, implementando Intersection Observer)
* **Arquitectura:** Generación de Sitio Estático (SSG)

## Estructura del Código
La arquitectura del proyecto está modularizada siguiendo las convenciones óptimas del framework:

```text
/
├── public/
│   └── (Archivos estáticos servidos directamente: imágenes, documentos, CV)
├── src/
│   └── pages/
│       └── index.astro (Estructura principal de la web y lógica de navegación)
├── astro.config.mjs (Configuración del motor e integración del sistema de estilos)
├── tailwind.config.mjs (Directivas de diseño, variables y rutas de Tailwind)
└── package.json (Gestión de dependencias del entorno Node.js)