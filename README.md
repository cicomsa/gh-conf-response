# gh-conf-response

[![Build Status](https://travis-ci.com/gh-conf/gh-conf-response.svg?branch=master)](https://travis-ci.com/gh-conf/gh-conf-response)
[![Github Repo Size](https://img.shields.io/github/repo-size/gh-conf/gh-conf-response.svg)](https://github.com/gh-conf/gh-conf-response)
[![LICENSE](https://img.shields.io/npm/l/@gh-conf/gh-conf-response.svg)](https://github.com/gh-conf/gh-conf-response/blob/master/LICENSE)
[![NPM Downloads](https://img.shields.io/npm/dt/@gh-conf/gh-conf-response.svg)](https://www.npmjs.com/package/@gh-conf/gh-conf-response)
[![NPM Version](https://img.shields.io/npm/v/@gh-conf/gh-conf-response.svg)](https://www.npmjs.com/package/@gh-conf/gh-conf-response)
[![Contributors](https://img.shields.io/github/contributors/gh-conf/gh-conf-response.svg)](https://github.com/gh-conf/gh-conf-response/graphs/contributors)
[![Commit](https://img.shields.io/github/last-commit/gh-conf/gh-conf-response.svg)](https://github.com/gh-conf/gh-conf-response/commits/master)

Response builder for gh-conf libraries

> Give us a :star: if you like our work :heart:

<a href="https://www.buymeacoffee.com/gh-conf" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>
<a href="https://www.patreon.com/bePatron?u=15454240" target="_blank"><img src="https://c5.patreon.com/external/logo/become_a_patron_button.png" alt="Become a Patron!" height="40"></a>

Please consider donating, if you like my work

## Install

```
$ npm install @gh-conf/gh-conf-response
```

## Usage

```javascript
const { formatError, formatSuccess } = require('@gh-conf/gh-conf-response');

const successResponse = formatSuccess('Successfully passed', { name: 'formatSuccess' });
console.log(successResponse)
// Output
/**
 * {
 *  status: 'success',
 *  message: 'Successfully passed',
 *  data: {
 *    name: 'formatSuccess'
 *  }
 * }
 **/


const errorResposne = formatError('Error running tests', { err: '101' });
console.log(successResponse)
// Output
/**
 * {
 *  status: 'err',
 *  message: 'Error running tests',
 *  data: {
 *    err: '101'
 *  }
 * }
 **/


```

## Contributing

Interested in contributing to this project?
You can log any issues or suggestion related to this library [here](https://github.com/gh-conf/gh-conf-response/issues/new)

Read our contributing [guide](CONTRIBUTING.md) on getting started with contributing to the codebase

## Contributors

Thank you to all the contributors who have helped us in making this project better 🙌

<a href="https://github.com/arshadkazmi42"><img src="https://github.com/arshadkazmi42.png" width="30" /></a>
