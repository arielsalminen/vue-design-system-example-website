# Using Vue Design System as an NPM dependency on a static website

## Testing from a remote repository

1. Clone this repository
2. Run `npm install`
3. Now you can run `npm run serve` to test that the design system build and its components work.
4. When you’re ready to start testing your own system library, switch the `vue-design-system` dependency in the package.json to point to your own private repository.

## Going further

To make things even simpler, it’s also possible to build and use Vue Design System’s components as Web Components using [vue-web-component-wrapper](https://github.com/vuejs/vue-web-component-wrapper). For instructions on how to modify the build process, see: https://github.com/vuejs/vue-web-component-wrapper
