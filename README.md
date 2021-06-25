# Babel & Nodemon

![image](https://i.morioh.com/f720086fa0.png)

## Installation and Usage

You can install Babel using npm:

```
npm install --save-dev @babel/core @babel/cli @babel/preset-env @babel/node
```

You can install Nodemon using npm:

```
npm install --save-dev nodemon
```

## Configuration

To setup your Babel you can paste this code to your `.babelrc` file:

```json
{
  "presets": [
    "@babel/preset-env"
  ]
}
```

You can then add Start command inside a `package.json` file:

```json
"start": "nodemon --exec babel-node index.js",
```
