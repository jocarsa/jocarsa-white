# Jocarsa White Icons

![Jocarsa White Logo](https://jocarsa.github.io/jocarsa-white/logo.svg)

A collection of white-themed SVG icons for your web projects. Easily integrate these icons using CSS classes to enhance your user interface with clean and scalable graphics.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Available Icons](#available-icons)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Installation

You can include the CSS file directly from the GitHub Pages or clone the repository to include it in your project.

### Via CDN

```html
<link rel="stylesheet" href="https://jocarsa.github.io/jocarsa-white/jocarsawhite.css">
```

### Clone the Repository

```bash
git clone https://github.com/jocarsa/white.git
```

Then include the CSS file in your project:

```html
<link rel="stylesheet" href="path/to/jocarsawhite.css">
```

## Usage

To use an icon, add the `jocarsa-icon` class along with the specific icon class to an HTML element, such as a `<span>` or `<i>`.

```html
<span class="jocarsa-icon jocarsa-icon-editar"></span>
```

## Available Icons

Below is a list of available icons with their corresponding CSS classes and previews.

| Icon | CSS Class | Preview |
|------|-----------|---------|
| **Editar (Edit)** | `jocarsa-icon-editar` | ![Editar](https://jocarsa.github.io/jocarsa-white/iconos/editar.svg) |
| **Compartir (Share)** | `jocarsa-icon-compartir` | ![Compartir](https://jocarsa.github.io/jocarsa-white/iconos/compartir.svg) |
| **Eliminar (Delete)** | `jocarsa-icon-eliminar` | ![Eliminar](https://jocarsa.github.io/jocarsa-white/iconos/eliminar.svg) |
| **Documento (Document)** | `jocarsa-icon-documento` | ![Documento](https://jocarsa.github.io/jocarsa-white/iconos/documento.svg) |
| **Cuadrícula (Grid)** | `jocarsa-icon-cuadricula` | ![Cuadrícula](https://jocarsa.github.io/jocarsa-white/iconos/cuadricula.svg) |
| **Lista (List)** | `jocarsa-icon-lista` | ![Lista](https://jocarsa.github.io/jocarsa-white/iconos/lista.svg) |
| **Salir (Exit)** | `jocarsa-icon-salir` | ![Salir](https://jocarsa.github.io/jocarsa-white/iconos/salir.svg) |
| **Guardar (Save)** | `jocarsa-icon-guardar` | ![Guardar](https://jocarsa.github.io/jocarsa-white/iconos/guardar.svg) |
| **Volver (Back)** | `jocarsa-icon-volver` | ![Volver](https://jocarsa.github.io/jocarsa-white/iconos/volver.svg) |

*Add additional icons [here](https://github.com/jocarsa/white/tree/main/iconos).*

## Customization

You can customize the icons by overriding the default CSS classes. For example, to change the size or color:

```css
.jocarsa-icon {
  width: 32px;
  height: 32px;
  fill: #000; /* Change fill color */
}
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m 'Add YourFeature'`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

© 2025 Jocarsa. All rights reserved.
