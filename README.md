# ethvault/iframe-provider-polyfill

[![Build Status](https://travis-ci.org/ethvault/iframe-provider-polyfill.svg?branch=master)](https://travis-ci.org/ethvault/iframe-provider-polyfill)
[![MinZipped size](https://badgen.net/bundlephobia/minzip/@ethvault/iframe-provider-polyfill)](https://bundlephobia.com/result?p=@ethvault/iframe-provider-polyfill@0.1.2)
![NPM Version](https://img.shields.io/npm/v/@ethvault/iframe-provider-polyfill.svg)

This is a drop in script that overrides web3 to point at the parent window when the page is embedded in an iframe.
This makes the page instantly compatible with Ethvault.


## Browsers only

This polyfill is meant for browser contexts only. 
The import is no-op in node contexts.

## Usage

Install the dependency

```bash
npm i @ethvault/iframe-provider-polyfill
```

or with yarn:

```bash
yarn add @ethvault/iframe-provider-polyfill
```

Then import it into your script

```typescript
import '@ethvault/iframe-provider-polyfill';
```

Or use a CDN like unpkg or rawgit to get it directly from the source. Thanks to 
[subresource integrity](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity), you can be sure 
the javascript won't change.

Unpkg (v0.1.3)
```html
<script src="https://unpkg.com/@ethvault/iframe-provider-polyfill@0.1.3/dist/index.js" integrity="sha384-ZyiCo4kSqbweMOmopAciwaVi777CpHdHoVn7j/Gq75ocldvNA+65S+45yIj6Xznr" crossorigin="anonymous"></script>
```
