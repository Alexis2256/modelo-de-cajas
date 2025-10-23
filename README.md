# Actividad 6 - Proyecto de Diseño Web con Modelo de Caja

> Proyecto de diseño de una página web aplicando el modelo de caja con CSS Grid y Tailwind CSS

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

## Descripción

Este proyecto es una página web informativa sobre **Tecnologías Web Modernas** que demuestra la aplicación práctica del **modelo de caja CSS** utilizando **CSS Grid** y **Tailwind CSS v4**. El diseño es completamente responsive y presenta información sobre React, Angular, Node.js, Astro, Tailwind CSS y JavaScript.

## Características

- Diseño moderno y atractivo con gradientes de color
- Completamente responsive (móvil, tablet y escritorio)
- CSS Grid avanzado con layout masonry en la sección "Su uso"
- Modelo de caja aplicado en todos los elementos
- Tailwind CSS v4 para estilos utility-first
- Efectos hover interactivos en tarjetas y enlaces
- Fuente personalizada (Eater) para títulos
- Paleta de colores personalizada (violeta y azul)



## Tecnologías Utilizadas

| Tecnología | Uso |
|------------|-----|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) | Estructura de la página |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) | Estilos y diseño |
| ![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat&logo=tailwind-css&logoColor=white) | Framework CSS utility-first |
| ![CSS Grid](https://img.shields.io/badge/CSS_Grid-1572B6?style=flat&logo=css3&logoColor=white) | Sistema de layout responsive |

## Estructura del Proyecto

```
Actividad-6/
├── index.html           # Página principal
├── src/
│   ├── input.css       # Archivo de entrada para Tailwind
│   └── output.css      # Tailwind CSS compilado
├── styles.css          # Estilos personalizados adicionales
├── package.json        # Dependencias del proyecto
└── README.md          # Este archivo
```

## Instalación y Uso

### Requisitos Previos

- [Node.js](https://nodejs.org/) (versión 14 o superior)
- npm o yarn

### Pasos de Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/TU_USUARIO/actividad-6-modelo-caja.git
   cd actividad-6-modelo-caja
   ```

2. **Instalar dependencias**
   ```bash
   npm install
   ```

3. **Compilar Tailwind CSS**
   ```bash
   npm run build
   ```

   O para modo desarrollo con watch:
   ```bash
   npm run dev
   ```

4. **Abrir en el navegador**
   - Abre el archivo `index.html` en tu navegador
   - O usa Live Server en VS Code

## Diseño Responsive

El proyecto utiliza CSS Grid con diferentes configuraciones según el tamaño de pantalla:

### Móvil (< 768px)
- Layout de 1 columna
- Tarjetas apiladas verticalmente
- Padding reducido

### Tablet (768px - 1024px)
- Grid de 2 columnas
- Espaciado optimizado
- Layout sin masonry para evitar espacios vacíos

### Desktop (> 1024px)
- Grid de 3 columnas con masonry
- Items con diferentes tamaños (col-span y row-span)
- Efectos hover completos
- Grid auto-flow dense para llenar espacios

## Modelo de Caja Aplicado

El proyecto demuestra el uso completo del modelo de caja CSS:

- **Margin**: Espaciado exterior entre elementos
- **Border**: Bordes con colores y efectos hover
- **Padding**: Espaciado interior en tarjetas y contenedores
- **Content**: Contenido con tipografía y colores personalizados
- **Box-shadow**: Sombras para profundidad visual
- **Border-radius**: Esquinas redondeadas

## Secciones del Proyecto

1. **Header**: Título principal con gradiente
2. **Tecnologías Web**: Grid de 6 tecnologías con iconos
3. **Su uso**: Layout masonry con información de uso
4. **Referencias**: Enlaces a documentación oficial


## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## Autor

**Alexis**

## Agradecimientos

- [Tailwind CSS](https://tailwindcss.com/) - Framework CSS
- [DevIcon](https://devicon.dev/) - Iconos de tecnologías
- [Google Fonts](https://fonts.google.com/) - Fuente Eater

---
