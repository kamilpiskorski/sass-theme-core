# sass-theme-core

> SASS theme core. Set of utilities, vars, grid, form elements and some pure components.

## Setup

```bash
# install dependencies
npm install

# watch changes and compile sass
npm start

# build for development
npm run build-sass

# run autoprefix
npm run build-autoprefix

# run cleancss
npm run build-cleancss

# build for production
npm run build
```

## Folder structure

    .
    ├── core
    │    ├── base
    │    │   ├── reset
    │    │   ├── variables
    │    │   └── general
    │    └── utilities          # eg. grid, spacing
    ├── shared
    │    ├── components         # eg. navbar, footer, notifications
    │    ├── elements           # eg. button, icon, typography
    │    └── form
    ├── layouts                 # eg. base, auth
    └── modules
         └── [module name]
             ├── components
             ├── elements
             └── sections
