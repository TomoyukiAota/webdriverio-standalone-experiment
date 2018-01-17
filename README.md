# webdriverio-standalone-experiment

This repository is for experiments of [WebdriverIO](http://webdriver.io/) in standalone mode.

## How To Setup

The following applications are required to be installed on your computer.

- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org/en/) (v8.9.0 LTS or greater)
- [Google Chrome](https://www.google.com/intl/en/chrome/)

To setup the environment, type the following commands:

```bash
git clone https://github.com/TomoyukiAota/webdriverio-standalone-experiment
cd webdriverio-standalone-experiment
npm install
npm run selenium-install
```

## How To Run

To run, two console windows are required. In one of them, type

```bash
npm run selenium-start
```

In the other window, type

```bash
npm start
```

After typing `npm run selenium-start` and `npm start`, web browser launches and actions described in `./src/main.js` run.

[![Screen Capture](https://j.gifs.com/gL6RpD.gif)](https://youtu.be/JJnRd4AC_zI)

## Useful References

- [WebdriverIO - How to use WebdriverIO](http://webdriver.io/guide/getstarted/modes.html)
- [Seleniumとブラウザドライバーのインストールと使い方 | Refills](https://syon.github.io/refills/rid/1496490/)
