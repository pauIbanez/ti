# Ti

NO VISITIS w3schools.com, molta informació incorrecta, moute per stackoverflow.

### Instala aquestes extensions de VSCode:

- EditorConfig for VS Code
- ESLint (de Microsoft)
- Prettier (de Prettier)
- vscode-icons (de VSCode Icons Team)
- YAML (de Red Hat)

### Configuració

`Ctrl + Shift + P` Escriu "Open Settings" i donali al Open Settings (JSON).
Enganxa aquesta configuració de VS code:

```JSON
{
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "typescript": "typescriptreact"
  },
  "emmet.triggerExpansionOnTab": true,
  "javascript.suggestionActions.enabled": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "js/ts.implicitProjectConfig.experimentalDecorators": true,
  "rainbowTags.hightlightType": "color",
  "typescript.suggestionActions.enabled": false,
  "typescript.updateImportsOnFileMove.enabled": "always"
}

```

### Snippets

Afegeix si vols aquests snipets que he fet jo.
`Ctrl + Shift + P` i busca snippets -> Configure user snippets -> New Global Snippets file -> poses el nom que vulguis, basicament suda.
Borra tot lo verd I enganxa això:

```JSON
"setup html": {
    "scope": "html",
    "prefix": "ht",
    "body": [
      "<!DOCTYPE html>",
      "<html lang=\"en\">",
      "  <head>",
      "    <meta charset=\"UTF-8\">",
      "    <link rel=\"shortcut icon\" href=\"favicon.ico\" type=\"image/x-icon\">",
      "    <meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\">",
      "    <title>Document</title>",
      "  </head>",
      "<body>",
      "</body>",
      "</html>"
    ],
    "description": "Create html skeleton with favicon"
  }

```

Aixi bàsicament, cuant escriguis ht hauria de sortir una xuleta I si prems enter et posarà la meva plantilla de html.
