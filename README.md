# Antistatique

This is a Hugo test for Antistatique Landing Pages.

## Development

To work on this, clone the project, and run:

```bash
# Install Hugo
brew install hugo
# Fetch dependencies
yarn
# Run Toolbox
yarn start
# Serve the Hugo website
hugo serve
```

## Styleguide

Currently, the assets from the website are copied here and transformed to work with the latest Toolbox version. However when you run `yarn start`, you won't have the components, they have not been ported to twig yet. TBD.

**[2017-10-25]** Until it's merged, you have to use the branch `feature/icon-font` of the [Toolbox Utils](https://github.com/frontend/toolbox-utils/pull/3) tool. Clone it, checkout the branch and use it with `yarn link`.
