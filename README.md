# PORTAFOLIO WEB MINIMALISTA

Este portafolio web de diseño muy simple se creó con el objetivo de ser fácilmente imprimible en formato PDF y proporcionar información clara y concisa.

Elaborado con ASTRO y utilizando NinjaNinja Keys.

[![just-the-basics](https://i.ibb.co/gw3SN4J/Captura-de-pantalla-103.png)](https://ninja-keys-demo.vercel.app/)
[![just-the-basics](https://i.ibb.co/qJpv0c3/Captura-de-pantalla-104.png)](https://portafolio-minimalista.netlify.app/)

**Demo:** [https://portafolio-minimalista.netlify.app/](https://portafolio-minimalista.netlify.app/)

Mejoré las imágenes para que estén más pequeñas y tengan bordes redondeados.

## 🚀 Estructura del proyecto

```sh
npm create astro@latest -- --template basics
```


Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
