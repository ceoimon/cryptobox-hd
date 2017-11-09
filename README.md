## Cryptobox-HD

*Note: If you don't need header encryption, use the original [Cryptobox](https://github.com/wireapp/wire-webapp-cryptobox) instead*

Cryptobox-HD provides a high-level API with persistent storage for the [Proteus-HD][2] implementation of the [Signal Protocol][3].

[2]: https://github.com/ceoimon/proteus-hd
[3]: https://signal.org/docs/

## Build Status

[![Build Status](https://travis-ci.org/ceoimon/cryptobox-hd.svg?branch=header_encryption)](https://travis-ci.org/ceoimon/cryptobox-hd)

## Installation

### Node.js

```bash
yarn add cryptobox-hd
```

### Browser

Use a module bundler or [UMD](https://github.com/umdjs/umd) builds in the [`dist` folder](https://unpkg.com/cryptobox-hd/dist/)

## Usage

### Browser

- [browser.html](./examples/browser.html)

### Node.js

- [index.js](./examples/node/index.js)

## Development

### Testing

Run individual test:

```bash
# Example
gulp test_browser --file "common/CacheSpec.js"
```

Run all tests (in Chrome & Node.js):

```bash
yarn test
```
