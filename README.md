# Solidity Services Section

<!-- 561-group-standards:badges:start -->
[![Red Cup Engineering](https://img.shields.io/badge/561%20Group-Red%20Cup%20Engineering-c0392b)](https://github.com/red-cup-engineering)
[![License: MIT](https://img.shields.io/badge/license-MIT-c0392b)](LICENSE)
[![Indigenous data: CARE](https://img.shields.io/badge/Indigenous%20data-CARE-4b6f44)](https://github.com/red-cup-engineering/.github/blob/main/GOVERNANCE.md)
[![Tips welcome](https://img.shields.io/badge/tips-welcome-d4a017)](https://github.com/561-group/.github/blob/main/TIPS.md)
<!-- 561-group-standards:badges:end -->

This section contains services and utilities specific to Solidity, the
smart-contract language.

## Services

`search-path-for-relations` finds where a Solidity contract, interface,
library, or function is referenced across a directory tree, and classifies
each reference by kind (declaration, import, construction, deployment
target, compiled artifact, selector reference, call/cast, or plain symbol
reference). It is the Solidity parameterization of the language-neutral
[`search-path-for-relations`](../search-path-for-relations) package. See
[`services/search-path-for-relations`](services/search-path-for-relations)
for install, usage, and API details.

## Development

```sh
npm run check   # syntax-check the scripts
npm test        # run the tests
npm run check && npm test  # both
```
