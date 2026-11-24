# Melon Cash · Landing page

Landing page de una tarjeta virtual presentada como proyecto final del curso de Maquetación Web. Incluye header con menú responsive, sección hero con llamados a la acción, iconos sociales y scroll indicator.

Hecha solo con **HTML5 y CSS3**, sin frameworks ni build.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/responsive-sí-2ea44f)

## Contenido

- [Capturas](#capturas)
- [Características](#características)
- [Stack](#stack)
- [Estructura del repositorio](#estructura-del-repositorio)
- [Cómo verla](#cómo-verla)
- [Despliegue](#despliegue)

## Capturas

| Desktop | Mobile |
| :-----: | :----: |
| ![Desktop](docs/screenshots/01-desktop.png) | ![Mobile](docs/screenshots/02-mobile.png) |

## Características

- **Hero** con título, copy, botones **Catálogo** y **Conoce más**, e imagen principal.
- **Menú responsive** con checkbox toggler y lista de navegación (Home, About, Portfolio, Contact).
- **Iconos** de Boxicons y Remixicon, y tipografías Lato / Vend Sans desde Google Fonts.
- **Diseño adaptable** probado en escritorio y en celular.
- **Sin dependencias de instalación**: se abre directamente en el navegador.

## Stack

| Capa | Tecnologías |
| --- | --- |
| Estructura | HTML5 semántico |
| Estilos | CSS3 con hoja única `style.css` |
| Iconos | Boxicons · Remixicon |
| Tipografías | Google Fonts (Lato, Vend Sans) |

## Estructura del repositorio

```text
Proyecto-final-maquetacion-web/
├── assets/
│   └── imgs/          # imágenes del producto
├── index.html
└── style.css
```

## Cómo verla

Podés abrir `index.html` directamente en el navegador. Si preferís servirla por HTTP:

```bash
python -m http.server 8000
```

Y entrar a <http://localhost:8000>.

## Despliegue

No requiere build. Publicá la raíz del repositorio en GitHub Pages, Netlify, Vercel o cualquier hosting estático.
