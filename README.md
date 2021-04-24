# React-with-webpack5-and-babel7

A React Project with Webpack 5 and Babel 7

```sh
git clone https://github.com/koomox/react-with-webpack5-and-babel7.git
```

install yarn

```sh
curl -o- -L https://yarnpkg.com/install.sh | bash
```

update Dependencies

```sh
yarn upgrade
```
setting proxy           
```sh
yarn config set proxy socks5://127.0.0.1:1080
```

install Dependencies

```sh
yarn init
yarn add webpack webpack-cli webpack-dev-server --dev
yarn add html-webpack-plugin clean-webpack-plugin --dev
yarn add @babel/core @babel/cli @babel/preset-env @babel/preset-react babel-loader --dev
yarn add react react-dom --dev
yarn add react-hot-loader --dev
yarn add css-loader mini-css-extract-plugin file-loader --dev
```