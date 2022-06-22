## Welcome to POS2

```
yarn install
yarn start
```

## Using




## Coding Convention
1. Please keep the folder structure..
2. If React Components, the directory name should start with a capital letter (like CamelCase), and if other components, with a lowercase letter (camelCase).
4. Dont import `useTranslation` or `import React from 'react'` because it will automation import.
5. Please use `<></>` instead of `React.Fragment`.
6. Must have file `index.jsx` in any Folder  UI Component Folder. It's will represent for export  UI Component Folder.
7. Should using commit message convention for any commit. Follow the article: https://dev.to/i5han3/git-commit-message-convention-that-you-can-follow-1709


## Directories

```
├── public
|   └── locales
└── src
    ├── assets
    │   ├── images
    |   ├── css
    |   └── fonts
    ├── components
    ├── contexts
    ├── hooks
    ├── modules
    │   ├── plugins
    |   └── utils
    ├── pages
    ├── services
    ├── stores
    └── styles

```


#### `src/assets` - Folder that stores all assets
#### `src/components` - Define common UI, or Common Wrapper

#### `src/hooks` - Define custom hook.

#### `src/module` - Folder has plugins of setting library, utils, constants, or define function common.
#### `src/pages` - Define common Page, Container Page

#### `src/services` - Folder define API services

#### `src/stores` - Define Recoil store. Dispatch and Atom of recoil
#### `src/styles` - Common styles, reset styles or styles of library
