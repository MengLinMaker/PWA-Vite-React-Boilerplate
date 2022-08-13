# PWA Vite React Boilerplate
This boilerplate isalready preinstalled with:
* [Vite Plugin PWA](https://vite-plugin-pwa.netlify.app/) to generate the manifest JSON for [progressive web app (PWA)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps).
* [Vite.js](https://vitejs.dev/) frontend tooling to build for production.
* [React.js](https://reactjs.org/) with TypeScript support.
* [Sass](https://sass-lang.com/) CSS preprocessor. To uninstall, type: ```npm uninstall sass``` in terminal.

# How to use
## Generate GitHub repository
1. Generate your repository from this template: [Click Here](https://github.com/MengLinMaker/PWA-Vite-React-Boilerplate/generate)
2. Clone code to your to remote repository: ```git clone https://github.com/user-name/repository-name```
Note: supply your GitHub user-name and repository-name.

## Development
The following terminal commands are from [Vite.js command line interface](https://vitejs.dev/guide/#command-line-interface). Also check the [package.json](https://github.com/MengLinMaker/PWA-Vite-React-Boilerplate/blob/main/package.json) file "scripts" section for all command line scripts.

### Run development website locally
```
npm run dev
```
Note: 
* There is no PWA functionality in development mode.

### Build production files - to "dist" folder
```
npm run build
```
Note: 
* Ensure there are not TypeScript errors, otherwise complilation will be aborted.
* Build files will be placed in the "dist" folder by default. 

### Run production build website locally
```
npm run preview
```
