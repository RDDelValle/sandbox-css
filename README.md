# sandbox-css
Sandbox CSS project for personal reference and education.

## Directories
- [dist/](dist)
  - [css/](dist/css)
- [docs/](docs)
  - [css/](docs/css)
- [src/](src)
  - [assets/](src/assets)
  - [pug/](src/pug)
    - [layout/](src/pug/layout)
    - [mixins/](src/pug/mixins)
    - [index.pug](src/pug/index.pug)
  - [scss/](src/scss)
    - [base/](src/scss/base)
    - [mixins/](src/scss/mixins)
    - [main.scss](src/scss/main.scss)

## NPM
- [package.json](package.json)
  - scripts
    - clean `npm run clean`
    - serve `npm run serve`
      - serve:server `npm run serve:server`
    - dev `npm run dev`
      - dev:watch `npm run dev:watch`
      - dev:server `npm run dev:server`
    - build `npm run build`
    - watch `npm run watch`
    - build:css `npm run build:css`
      - build:dist:css `npm run build:dist:css`
      - build:docs:css `npm run build:docs:css`
    - watch:css `npm run watch:css`
      - watch:dist:css `npm run watch:dist:css`
      - watch:docs:css `npm run watch:docs:css`
    - build:scss `npm run build:scss`
    - watch:scss `npm run watch:scss`
    - build:pug `npm run build:pug`
    - watch:pug `npm run watch:pug`
    - build:assets `npm run build:assets`
  - devDependencies
    - autoprefixer
    - copyfiles
    - live-server
    - npm-run-all
    - postcss
    - postcss-cli
    - pug
    - pug-cli
    - rimraf
    - sass
