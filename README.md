# 🚀 Landing Page - Arquitectura SASS Modular

Link de la Pagina Web: https://entregacurso.free.nf/index.html

Este proyecto utiliza una estructura profesional de SASS (SCSS) basada en el patrón de siete capas para mantener un código escalable, limpio y fácil de mantener.

## 🛠️ Tecnologías y Metodología
- **SASS (SCSS)**: Uso de reglas `@use` para modularización.
- **Arquitectura de Carpetas**: Separación por responsabilidades (abstracts, base, layout, components, pages).
- **Compilación Automática**: Generación de `style.css` y `main.css.map` para debugging.

## 📂 Estructura del Proyecto
El proyecto se organiza de la siguiente manera:

* **abstracts/**: Contiene variables globales como `$primary-color` y mixins reutilizables como `hover-lift`.
* **base/**: Estilos globales y reseteos para el elemento `body`.
* **layout/**: Estilos para componentes estructurales como `header` y `footer`.
* **components/**: Estilos para elementos reutilizables como las `cards`.
* **pages/**: Estilos específicos para la página de inicio (`_home.scss`), incluyendo secciones hero y animaciones.

## ⚡ Características Destacadas
* **Mixins**: Implementación de efectos de elevación (`hover-lift`) y centrado flexible (`flex-center`).
* **Responsive Design**: Uso de Media Queries para adaptar la sección hero en dispositivos móviles (max-width: 768px).
* **Variables Centralizadas**: Control total de colores y transiciones desde un solo archivo.

## 🚀 Cómo ejecutar este proyecto
1. Clona el repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/tu-repositorio.git](https://github.com/tu-usuario/tu-repositorio.git)
