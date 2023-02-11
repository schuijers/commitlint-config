# @schuijers/commitlint-config [![GitHub Build Status][shield-github-build-status]][shield-github-build-status] [![npm][shield-npm]][npm] [![MIT License][shield-license]][license]

Commitlint rules for my personal projects.

## Installation

```shell script
# npm
npm install --save-dev @schuijers/commitlint-config

# yarn
yarn add --dev @schuijers/commitlint-config

# pnpm
pnpm add --save-dev @schuijers/commitlint-config
```

## Usage

Reference `@schuijers/commitlint-config` in your `commitlint.config.js`.

<!-- prettier-ignore -->
```javascript
module.exports = {
  extends: '@schuijers/commitlint-config',
  rules: {
    // your overrides
  },
}
```

Or, you can use it in other ways as described in the
[official documentation](https://commitlint.js.org/#/reference-configuration).

## License

[MIT][license] &copy; [Martijn Schuijers][me]

[license]: ./LICENSE
[me]: https://github.com/schuijers
[npm]: https://npmjs.org/package/@schuijers/commitlint-config
[shield-github-build-status]:
  https://github.com/schuijers/commitlint-config/workflows/Release/badge.svg
[shield-license]: https://img.shields.io/badge/License-MIT-lavender.svg
[shield-npm]: https://img.shields.io/npm/v/@schuijers/commitlint-config.svg
