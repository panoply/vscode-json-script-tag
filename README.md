[![npm version](https://img.shields.io/badge/vscode-install-blue.svg)](https://marketplace.visualstudio.com/items?itemName=sissel.json-script-tag)

## JSON <script> Tag Syntax Support (VS Code)

Syntax highlighting support for HTML `<script>` tags using `application/json` and `application/ld+json` attributes.

## Why?

VS Code [does not yet support](https://github.com/microsoft/vscode/issues/36280) JSON syntax highlighting on HTML script tags using the `type="application/json"` attribute.

## Example

```html

<script type="application/json">
  /* JSON HERE*/
</script>

<script type="application/ld+json">
  /* JSON HERE*/
</script>

```
