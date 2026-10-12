# Mi Portafolio

Sitio web personal de desarrollo web, realizado como proyecto del curso de Programación Web. Presenta quién soy, los proyectos que desarrollé, respuestas a preguntas frecuentes y mis datos de contacto.

## Sitio desplegado

🔗 **<https://sabrina.github.io/mi-portafolio/>**

## Páginas

| Página | Archivo | Contenido |
|---|---|---|
| Inicio | `index.html` | Presentación, herramientas, galería de proyectos y destacados |
| Sobre mí | `pages/sobre-mi.html` | Perfil, formación y habilidades |
| Proyectos | `pages/proyectos.html` | Detalle de cada proyecto con tecnologías y enlace al código |
| FAQ | `pages/faq.html` | Preguntas frecuentes en formato acordeón |
| Contacto | `pages/contacto.html` | Medios de contacto y disponibilidad |

## Tecnologías

- **HTML5** semántico.
- **Sass (SCSS)**: los estilos se escriben en partials dentro de `scss/` y se compilan a `css/style.css`.
- **CSS3**: Flexbox, Grid con `grid-template-areas` y media queries mobile-first (768px y 1024px).
- **Bootstrap 5.3** por CDN: navbar responsiva, carousel, accordion, badges y botones, adaptados a la paleta del sitio.
- **Google Fonts**: Montserrat y Open Sans.
- **Git y GitHub** para el control de versiones y el despliegue con GitHub Pages.

## Estructura del proyecto

```
mi-portafolio/
├── index.html
├── pages/
│   ├── sobre-mi.html
│   ├── proyectos.html
│   ├── faq.html
│   └── contacto.html
├── scss/
│   ├── main.scss              # único punto de entrada
│   ├── utilities/
│   │   ├── _variables.scss
│   │   └── _mixins.scss
│   ├── base/
│   │   ├── _base.scss
│   │   └── _tipografia.scss
│   ├── layout/
│   │   ├── _header.scss
│   │   ├── _nav.scss
│   │   ├── _hero.scss
│   │   ├── _main.scss
│   │   └── _footer.scss
│   └── components/
│       ├── _buttons.scss
│       ├── _cards.scss
│       ├── _badges.scss
│       ├── _carousel.scss
│       ├── _accordion.scss
│       ├── _lists.scss
│       ├── _figures.scss
│       └── _contact.scss
├── css/
│   └── style.css  
├── img/            # generado por Sass, no se edita a mano
├── package.json
├── .gitignore
└── README.md
```

## Cómo verlo en tu computadora

```bash
git clone https://github.com/sabrina/mi-portafolio.git
cd mi-portafolio
```

Después, abrir `index.html` en el navegador.

## Cómo compilar los estilos

Requiere [Node.js](https://nodejs.org/).

```bash
npm install          # instala Sass (solo la primera vez)
npm run sass         # compila scss/main.scss a css/style.css
npm run sass:watch   # recompila cada vez que se guarda un .scss
```

## Autor

Tu Nombre · [GitHub](https://github.com/tu-usuario) · [LinkedIn](https://www.linkedin.com/in/tu-usuario)
