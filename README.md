# Sec-literal
![version](https://img.shields.io/badge/dynamic/json.svg?url=https://raw.githubusercontent.com/fraxken/sec-literal/master/package.json&query=$.version&label=Version)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/fraxken/sec-literal/commit-activity)
[![Security Responsible Disclosure](https://img.shields.io/badge/Security-Responsible%20Disclosure-yellow.svg)](https://github.com/nodejs/security-wg/blob/master/processes/responsible_disclosure_template.md
)
[![mit](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/fraxken/sec-literal/blob/master/LICENSE)
![dep](https://img.shields.io/david/fraxken/sec-literal)

This package is a security utilities library created to analyze [ESTree Literal](https://github.com/estree/estree/blob/master/es5.md#literal) and JavaScript string primitive. This project was originally created to simplify and better test the functionalities required for the SAST Scanner [JS-X-Ray](https://github.com/fraxken/js-x-ray).

## Features

- Detect Hexadecimal, Base64, Hexa and Unicode sequences.
- Detect patterns (prefix, suffix) on groups of identifiers.
- Detect suspicious string and return advanced metrics on it (char diversity etc).

## Getting Started

This package is available in the Node Package Repository and can be easily installed with [npm](https://docs.npmjs.com/getting-started/what-is-npm) or [yarn](https://yarnpkg.com).

```bash
$ npm i sec-literal
# or
$ yarn add sec-literal
```

## API

WORK IN PROGRESS

## License
MIT
