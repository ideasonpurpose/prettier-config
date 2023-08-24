# IOP's Prettier Config

#### Version 0.0.3

[Shared Prettier config](https://prettier.io/docs/en/configuration.html#sharing-configurations) for projects at Ideas On Purpose. Using this reduces redundant code in package.json and keeps coding preferences in sync across projects. 

## How to use

Add this `prettier` key to a project's package.json file:

```json
  "prettier": "@ideasonpurpose/prettier-config"
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
