# enigma.rest — first working copy of my first website

**Live:** https://lroy-stack.github.io/enigma.rest/src/

The first working copy (January–April 2024) of [`Enigma`](https://github.com/lroy-stack/Enigma), the website I built
by hand for the Enigma restaurant in Calpe (Spain) before AI coding tools. It starts from the free Grecko Bootstrap
template (MIT, © 2019 Marios Sofokleous, see `LICENSE`) and adds a Grunt pipeline to purify and minify CSS, uglify
JavaScript, inline critical CSS and minify HTML.

The restaurant's pages live in `src/`. The `dist/` and `docs/` folders still hold a build of the original template,
made before the customisation, so they do not show the Enigma site.

## Build

```bash
git clone https://github.com/lroy-stack/enigma.rest.git
cd enigma.rest
npm install
bash script.sh   # rebuilds dist/ and docs/ from src/
npx serve dist
```

## Layout

```
src/           the Enigma pages, styles, scripts and media
dist/, docs/   build output (currently the original template's build)
script.sh      build script that runs the Grunt tasks
Gruntfile.js   Grunt configuration
```

---

Versión en español: primera copia de trabajo (enero–abril de 2024) de mi primera web, hecha a mano para el
restaurante Enigma de Calpe sobre la plantilla libre Grecko (MIT). La web está en `src/`; `dist/` y `docs/` aún
contienen el build de la plantilla original.
