# Package Name

[![Circle CI](https://circleci.com/gh/Codecademy/package-name.svg?style=svg)](https://circleci.com/gh/Codecademy/package-name)
[![NPM version](https://img.shields.io/npm/v/package-name.svg)](https://npmjs.org/package/package-name)
[![Downloads](http://img.shields.io/npm/dm/package-name.svg)](https://npmjs.org/package/package-name)
![Code Style: Prettier](https://img.shields.io/badge/code_style-prettier-14cc21.svg)

Friendly description of the package.

## Usage

`package-name` does this cool thing.
You want it because of these excellent reasons.

Basic code example showing simple usage:

```js
import { component } from "package-name";

component.action();
```

More advanced code example with some fancy usage:

```js
import { component, fancy } from "package-name";

const preliminary = fancy({
    doThing: true,
});

component.fancyAction({
    doOtherThing: preliminary,
});
```

Ideally here there would be a longer inline list, list of sections, or table of the full features.

## Development

Requires:

* [Node.js](https://nodejs.org) >14 (LTS)
* [Yarn](https://yarnpkg.com/en)

After [forking the repo from GitHub](https://help.github.com/articles/fork-a-repo):

```
git clone https://github.com/<your-name-here>/package-name
cd package-name
yarn
yarn run verify
```

`yarn run verify` will run a full build and set up the package to be consumed locally.

### Contribution Guidelines

We'd love to have you contribute!
Check the [issue tracker](https://github.com/Codecademy/package-name/issues) for issues labeled [Accepting PRs](https://github.com/Codecademy/package-name/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3A%22Accepting+PRs%22) to find bug fixes and feature requests the community can work on.
If this is your first time working with this code, the [Good First issue](https://github.com/Codecademy/guidelines/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+label%3A%22Good+First+Issue%22+) label indicates good introductory issues.

Please note that this project is released with a [Contributor Covenant](https://www.contributor-covenant.org).
By participating in this project you agree to abide by its terms.
See [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md).
