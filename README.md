# Prerequisites

You will need NodeJS, then install Yarn globally

```
npm install - g yarn
```
# Setting up

Create package.json by running this command

```
yarn init
```

# Initial Configuration

## Add Webpack
```
yarn add webpack webpack-dev-server html-webpack-plugin -D
```
## Add Babel-loader (Allow us to use ES2015+ in our code)
```
yarn add babel-core babel-loader babel-preset-env -D
```
# Project Structure

- **src**: Main project container.
- **src/app**: Will host our javacript files.
- **src/public**: Holds project assets and static files.
- **src/style**: Holds the project's global styles.
- **src/app/index.js**: Main entry point into our project.
- **src/public/index.html**: Main project template.

# Start Project

```
yarn start
```

# Errors

If you encounter this error: 'webpack-dev-server not recognized' please run

```
npm install --only=dev
```

*This git follows instructions from [Scotch.io](https://scotch.io/tutorials/setting-up-webpack-for-any-project)*
