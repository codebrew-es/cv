# Terminal CV — Miguel Ángel Molina Tejedor

Un divertimento personal, más simple que el mecanismo de un chupete 👶. Un currículum vitae interactivo de una sola página en formato *Terminal*, accesible y ligero.

Está optimizado tanto para la navegación web como para la exportación directa a formato PDF manteniendo el estilo visual y el nivel de contraste adecuado.

## 🚀 Características Principales

- **Diseño Estilo Terminal / CLI**: Estética inspirada en la línea de comandos con fuentes monospace (`Fira Code`), indicador de comandos (`$ mamolina --whoami`) y animación de cursor parpadeando.
- **Acceso Directo a PDF (Print-Ready)**: Hojas de estilo CSS dedicadas a la exportación en papel o PDF (formato A4 *single-page*), ocultando elementos interactivos e imprimiendo referencias alternativas (como la URL a la versión web).
- **Modo Claro / Oscuro (Theme Toggle)**: Modos claro/oscuro con cambio automático de contraste y estado.
- **Accesibilidad Nivel AA (WCAG 2.1 / 2.2)**:
  - Estructura HTML5 totalmente semántica (`<header>`, `<main>`, `<section>`, `<footer>`).
  - Uso de clases `sr-only` para lectores de pantalla en enlaces externos.
  - Indicadores visuales de foco claros (`focus-visible`) para navegación 100% por teclado.
  - Relación de contraste optimizada mediante la paleta nativa de Tailwind CSS.
- **Sin Dependencias de Build**: Implementación ligera utilizando CDN para Tailwind CSS y Google Fonts, permitiendo su despliegue inmediato en cualquier servidor estático o GitHub Pages.

## 🛠️ Stack Tecnológico

- **HTML5**: Estructura semántica accesible.
- **CSS3 / Tailwind CSS**: Maquetación en Grid, utilidades responsive y control de `@media print`.
- **JavaScript (Vanilla)**: Lógica ligera para el control del tema (Dark/Light) e interacción con `window.print()`.

## 📁 Estructura del Proyecto

```
.
├── index.html     # La paginilla en sí (Single-file document)
└── README.md      # Documentación del proyecto
```

## 💻 Uso Local

Para ejecutar o modificar este proyecto en tu máquina local:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/codebrew-es/cv.git
   cd cv
   ```

2. Abre el archivo `index.html` en tu navegador preferido:
   ```bash
   # En Linux / macOS
   open index.html

   # En Windows
   start index.html
   ```

## 📄 Exportación a PDF

El documento está pensado para encajar exactamente en una página A4:

1. Pulsa el botón **📄 Imprimir PDF** en la esquina inferior derecha (o usa `Ctrl + P` / `Cmd + P`).
2. En el diálogo de impresión:
   - **Destino**: Guardar como PDF.
   - **Márgenes**: Ninguno (o Predeterminado).
   - **Gráficos de fondo**: Activado (para mantener la coherencia de los colores y bloques).

## 👤 Autor

**Miguel Ángel Molina Tejedor**  
*Senior Fullstack Developer & Software Engineer*

- **Web**: [codebrew.es](https://codebrew.es)
- **Sitio Web Personal**: [mamolina.dev](https://www.mamolina.dev)
- **LinkedIn**: [linkedin.com/in/miguel-ángel-molina-tejedor-9b89a633](https://linkedin.com/in/miguel-ángel-molina-tejedor-9b89a633)