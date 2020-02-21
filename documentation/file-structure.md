## File structure

- `/public` contains static assets like the HTML page we're planning to deploy to, or images. You can delete any file in this folder apart from `index.html`.
- `/src` contains our JS and CSS code. `index.js` is the entry-point for our file, and is mandatory.
    - `/components` - 'Dumb-components' / presentational. [Read More &rarr;](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0)
    - `/constants` - App-wide variables
    - `/containers` - 'Smart-components' that connect business logic to presentation [Read More &rarr;](https://redux.js.org/docs/basics/UsageWithReact.html#presentational-and-container-components)
    - `/images` - ...
    - `/lib` - Utils and custom libraries
    - `/models` - Rematch models combining actions, reducers and state. [Read More &rarr;](https://github.com/rematch/rematch#step-2-models)
    - `/routes`- wire up the router with any & all screens [Read More &rarr;](https://github.com/aksonov/react-native-router-flux)
    - `/store`- Redux Store - hooks up the stores and provides initial/template states [Read More &rarr;](https://redux.js.org/docs/basics/Store.html)
    - `/styles`- all the SCSS you could dream of
    - `/tests` contains all of our tests, where the test file matches the resptive file from `/src`
    - `index.js` - The starting place for our app
