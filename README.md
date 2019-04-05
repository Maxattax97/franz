<img src="./build-helpers/images/icon.png" alt="" width="150"/>

# Prattle
[![Build status Windows](https://ci.appveyor.com/api/projects/status/9yman4ye19x4274o/branch/master?svg=true)](https://ci.appveyor.com/project/Maxattax97/prattle/branch/master)
 [![Build Status Mac & Linux](https://travis-ci.com/Maxattax97/prattle.svg?branch=master)](https://travis-ci.com/Maxattax97/prattle) [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://meetfranz.com/payment.html)

Application that organizes messaging services like WhatsApp, Slack, Messenger and many more.

This is a fork of Franz 5 with the aim of decentralization and a few quality of life features. If you like this project, please
consider donating upstream.

## [Download Prattle](https://github.com/Maxattax97/prattle/releases)

## Development

### Preparations

#### Install Linux OS dependencies
[Guide: Linux distribution specific dependencies](docs/linux.md)

#### Fix native modules to match current electron node version
```bash
$ npm run rebuild
```

### Install dependencies
Run the following command to install all dependencies, and link sibling modules with Prattle.
```bash
$ npx lerna bootstrap
```

If you previously ran `npm install` it sometimes is necessary to delete your `node_modules` folder before running `npx lerna bootstrap`.

### Run Prattle Development App
Run these two commands __simultaneously__ in different console tabs.

```bash
$ npm run dev
$ npm run start
```
Be aware that the development database will be reset regularly.

## Packaging
```bash
$ npm run build
```

## How can I support the project?
If you have found a bug that hasn't been reported yet or want to request a new feature, please open a new issue.

## Create your own plugins/recipes
Plugins for Prattle differ from plugins in Franz in that they are decentralized. This has yet to be implemented. Stay tuned!

## License
Prattle is open-source licensed under the Apache-2.0 License.
