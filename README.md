# stylus-extra

[![Greenkeeper badge](https://badges.greenkeeper.io/Alexgalinier/stylus-exta.svg)](https://greenkeeper.io/)

Wrap stylus to ease recursive file detection and watching.

## Installation

```
npm i stylus-extra -D
```

## Usage

In your package.json scripts
```
"build-styl": "stylus-extra src -o lib",
"watch-styl": "stylus-extra src -o lib -w",
```
