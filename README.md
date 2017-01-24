## Vue js compoentns style guide generator

Initially started after reading [this feature request](https://github.com/vuejs/vue-requests/issues/17).
Now only basic proof of concept is availbale which can load .vue file, parse it and extract basic props of it.
Target is to have some tool with at least some of the [React version](https://github.com/styleguidist/react-styleguidist) capabilities.

### How to try

 - Clone or download this repo
 - ```npm install```
 - ```npm run build``` 
 - if you open the  '/collection-preview/index.html' you should see list of existing components with navigation to their details like this:
 ![resulting output](https://raw.githubusercontent.com/shershen08/vue-styleguide-generator/master/demo-output.jpg)
         
### Todos

- test
- core: merge component file with .md file in the same directory
- core: move the demo-page to use Vue so that components can be generated from its declaration
- ui: search in list of components
- ui: output extra component parameters (computable, data)

