# IOP's Prettier Config

#### Version 0.0.6

![NPM Version](https://img.shields.io/npm/v/%40ideasonpurpose%2Fprettier-config?logo=npm)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/ideasonpurpose/prettier-config/npm-publish.yml?logo=github&logoColor=white)

[Shared Prettier config](https://prettier.io/docs/en/configuration.html#sharing-configurations) for projects at Ideas On Purpose. Using this reduces redundant code in package.json and keeps coding preferences in sync across projects.

## How to use

Install this package:

```sh
npm install --save-dev @ideasonpurpose/prettier-config
```

Then add this `prettier` key to the project's package.json file:

```json
  "prettier": "@ideasonpurpose/prettier-config",
```

## Settings

Some of the settings included in this file:

### HTML

- `printWidth`: `120`
- `tabWidth`: `2`

### PHP

- `printWidth`: `100`
- `singleQuote:` `true`
- `tabWidth`: `4`,
- `trailingCommaPHP`: `true`

Our PHP projects include the [prettier-php plugin](https://github.com/prettier/plugin-php).

### Markdown

- `Options.embeddedLanguageFormatting`: `off`

### Related Projects

* [WordPress Build Tools](https://github.com/ideasonpurpose/build-tools-wordpress)
* [Prettier Config](https://github.com/ideasonpurpose/prettier-config)
* [Stylelint Config](https://github.com/ideasonpurpose/stylelint-config)
* [Docker-based Development Environment for WordPress](https://github.com/ideasonpurpose/docker-wordpress-dev)

## &nbsp;

#### Brought to you by IOP

<a href="https://www.ideasonpurpose.com"><img src="https://raw.githubusercontent.com/ideasonpurpose/ideasonpurpose/master/iop-logo-white-on-black-88px.png" height="44" align="top" alt="IOP Logo"></a><img src="https://raw.githubusercontent.com/ideasonpurpose/ideasonpurpose/master/spacer.png" align="middle" width="4" height="54"> This project is actively developed and used in production at <a href="https://www.ideasonpurpose.com">Ideas On Purpose</a>.

