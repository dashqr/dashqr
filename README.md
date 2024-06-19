<p align="center">
  <a href="https://dashqr.app">
    <img src="https://cdn.itwcreativeworks.com/assets/dashqr/images/logo/dashqr-brandmark-black-x.svg" width="100px">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/package-json/v/dashqr/dashqr.svg">
  <br>
  <img src="https://img.shields.io/librariesio/release/npm/dashqr.svg">
  <img src="https://img.shields.io/bundlephobia/min/dashqr.svg">
  <img src="https://img.shields.io/codeclimate/maintainability-percentage/dashqr/dashqr.svg">
  <img src="https://img.shields.io/npm/dm/dashqr.svg">
  <img src="https://img.shields.io/node/v/dashqr.svg">
  <img src="https://img.shields.io/website/https/dashqr.app.svg">
  <img src="https://img.shields.io/github/license/dashqr/dashqr.svg">
  <img src="https://img.shields.io/github/contributors/dashqr/dashqr.svg">
  <img src="https://img.shields.io/github/last-commit/dashqr/dashqr.svg">
  <br>
  <br>
  <a href="https://dashqr.app">Site</a> | <a href="https://www.npmjs.com/package/dashqr">NPM Module</a> | <a href="https://github.com/dashqr/dashqr">GitHub Repo</a>
  <br>
  <br>
  <strong>dashqr</strong> is the official npm module of <a href="https://dashqr.app">DashQR</a>, a free QR code generator with analytics and dynamic updates!
</p>

## 🌐 DashQR Works in Node AND browser environments
Yes, this module works in both Node and browser environments, including compatibility with [Webpack](https://www.npmjs.com/package/webpack) and [Browserify](https://www.npmjs.com/package/browserify)!

## 🦄 Features
* Getting proxy lists

### 🔑 Getting an API key
You can use so much of `dashqr` for free, but if you want to do some advanced stuff, you'll need an API key. You can get one by [signing up for a DashQR account](https://dashqr.app/signup).

## 📦 Install DashQR
### Option 1: Install via npm
Install with npm if you plan to use `dashqr` in a Node project or in the browser.
```shell
npm install dashqr
```
If you plan to use `dashqr` in a browser environment, you will probably need to use [Webpack](https://www.npmjs.com/package/webpack), [Browserify](https://www.npmjs.com/package/browserify), or a similar service to compile it.

```js
const dashqr = new (require('dashqr'))({
  // Not required, but having one removes limits (get your key at https://dashqr.app).
  apiKey: 'api_test_key'
});
```

### Option 2: Install via CDN
Install with CDN if you plan to use DashQR only in a browser environment.
```html
<script src="https://cdn.jsdelivr.net/npm/dashqr@latest/dist/index.min.js"></script>
<script type="text/javascript">
  var dashqr = new DashQR({
    // Not required, but having one removes limits (get your key at https://dashqr.app).
    apiKey: 'api_test_Key'
  });
</script>
```

### Option 3: Use without installation
You can use `dashqr` in a variety of ways that require no installation, such as `curl` in terminal/shell. See the **Use without installation** section below.

## ⚡️ Using DashQR
After you have followed the install step, you can start using `dashqr` to generate QR codes for free with analytics and dynamic updates!

For a more in-depth documentation of this library and the DashQR service, please visit the official DashQR website.

## 🔧 Use without installation
### Use DashQR with `curl`
```shell
# Standard
curl -X POST https://api.dashqr.app
```

## 📝 What Can DashQR do?
Dash QR is a [free QR code generator](https://dashqr.app) with analytics and dynamic updates!

## 🗨️ Final Words
If you are still having difficulty, we would love for you to post
a question to [the DashQR issues page](https://github.com/dashqr/dashqr/issues). It is much easier to answer questions that include your code and relevant files! So if you can provide them, we'd be extremely grateful (and more likely to help you find the answer!)

## 📚 Projects Using this Library
* coming soon!

Ask us to have your project listed! :)
