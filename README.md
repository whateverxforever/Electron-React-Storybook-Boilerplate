# Electron-React-Storybook-Boilerplate 🛠

A boilerplate for creating **Electron** application bootstrapped with **React** + **Storybook**. Boilerplate is also configured with **pre-commit hooks** like linting etc. (which you can modify in package.json) and is ready to **build** and **ship** your apps.

## Available Scripts

In the project directory, you can run:

### `yarn electron-dev`

Runs the app in the development mode on [http://localhost:3000](http://localhost:3000). The electron app will automatically pop open.

The page will reload if you make edits. You will also see any lint errors in the console.

### `yarn storybook`

Start the component explorer on [http://localhost:9009](http://localhost:9009). You can view your storybook components.

### `yarn build`

Builds the app for production to the `build` folder.<br /> It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.

### `yarn dist`

Creates a distribution version of the build app and stores it in `dist` folder.<br /> It uses default yarn distribution i.e creates a executable with all the assets, which user can install. <br />
**Windows + Linux Support, couldn't test Mac builds, let me know if it works 😋**



