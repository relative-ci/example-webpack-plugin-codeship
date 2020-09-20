<h1 align="center">
  Codeship
  +
  <a href="https://relative-ci.com">
    <img alt="RelativeCI" src="https://raw.githubusercontent.com/relative-ci/agent/master/assets/relative-ci--logo.svg?sanitize=true" width="64" valign="middle" />
  </a>
  <br>
  <a href="https://app.codeship.com/projects/388441"><img src="https://app.codeship.com/projects/a0e216e0-4522-0138-32e1-6e64cfacd9d0/status?branch=master" alt="Codeship"></a>
  <a href="https://app.relative-ci.com/projects/64NnGgjGOQXSR5cGHnas"><img src="https://badges.relative-ci.com/badges/64NnGgjGOQXSR5cGHnas?branch=master" alt="relativeCI"></a>
</h1>

> [@relative-ci/agent](https://github.com/relative-ci/agent) [webpack plugin](https://relative-ci.com/documentation/setup/webpack-plugin) setup example for [Codeship](https://codeship.com)

## 1. Install @relative-ci/agent

```shell
npm install --save-dev @relative-ci/agent
# or
yarn add --dev @relative-ci/agent
```

## 2. Configure @relative-ci/agent webpack plugin

[`webpack.config.js`](webpack.config.js#L61)

```js
// webpack.config.jjs
module.exports = {
  // ...
  plugins: [
    // ...
    new RelativeCiAgentWebpackPlugin()
  ]
};
```

[Get started with RelativeCI](https://relative-ci.com/documentation/setup)
