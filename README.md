# IOP's Prettier Config

#### Version 0.0.4

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
- `singleQuote: `true`
- `tabWidth`: `4`,
- `trailingCommaPHP`: `true`

Our PHP projects include the [prettier-php plugin](https://github.com/prettier/plugin-php).

### Markdown

- `Options.embeddedLanguageFormatting`: `off`

## &nbsp;

#### Brought to you by IOP

<a href="https://www.ideasonpurpose.com"><img src="https://raw.githubusercontent.com/ideasonpurpose/ideasonpurpose/master/IOP_monogram_circle_512x512_mint.png" height="44" align="top" alt="IOP Logo"></a><img src="https://raw.githubusercontent.com/ideasonpurpose/ideasonpurpose/master/spacer.png" align="middle" width="4" height="54"> This project is actively developed and used in production at <a href="https://www.ideasonpurpose.com">Ideas On Purpose</a>.
