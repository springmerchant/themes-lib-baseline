# Baseline

A simple style library for Bigcommerce themes.

## Installation

```
jspm install --save bc-baseline=bitbucket/pixelunion/bc-baseline
```

## Usage

You can now import the baseline stylesheet:

```
@import "../jspm_packages/bitbucket/pixelunion/bc-baseline@{version-number-here}/baseline";
```

You can check which version you have installed with `jspm inspect`.

It is recommended to import `normalize` before `baseline`.

## Development

Baseline comes with an example HTML file. To rebuild it after adding/changing styles, run `npm run build`. That will compile all SCSS files and inject them into `/scripts/template.html`, saving the result to `example.html`.
