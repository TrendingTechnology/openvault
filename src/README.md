The `src` directory contains the source code of the this project.

## Directory structure

This project uses a strict directory structure.

```
src: This directory.
|
├── assets: All static assets that could be placed on a CDN.
|
├── components: Components that follow the
|   |           Atomic Design structure of Brad Frost.
|   |
│   ├── atom:     An atom consists of a single, minimal component,
|   |             styled or unstyled, like a button.
|   |
│   ├── molecule: A molecule consists of multiple atoms,
|   |             like a search form with the atoms of a text field and a button.
|   |
│   ├── organism: An organism combines multiple molecules,
|   |             like a site header containing multiple molecules.
|   |
│   └── template: A template combines multiple organisms,
|                 and becomes filled with real content.
|
├── core: All core functionalities that work independently of the framework in use
|         like API requests, key generation, data encryption and decryption, etc.
|
├── data: Static data, typed with TypeScript.
|
├── models: Type definitions and interfaces.
|
└── views: Rendered pages that use the templates. 
```