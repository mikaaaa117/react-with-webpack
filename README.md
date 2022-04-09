# Adding React framework in your project with webpack
### First, install react and ReactDOM as dependencies of project
```
npm install react react-dom
```
### Second, install compiler to your project as devDependencies:
```
npm install -D @babel/core @babel/preset-env @babel/preset-react babel-loader css-loader style-loader sass-loader sass webpack webpack-cli
```
### Webpack's config file:
In your project create `webpack.common.js` config file.
Content of config you can take from github repository:

https://github.com/mikaaaa117/webpack-config.git

And in `package.json` file add script:
`"watch": "webpack --config webpack.common.js --watch"`
