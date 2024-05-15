## TOP SETTINGS.JSON

```json
{
  /**
   * Rocketseat Defaults
   * https://www.youtube.com/watch?v=TW3KoPkuWEA
   **/
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontSize": 14,
  "editor.lineHeight": 1.8,
  "editor.rulers": [80, 120],
  "workbench.startupEditor": "newUntitledFile",
  "editor.renderLineHighlight": "gutter",
  "editor.fontLigatures": true,
  "workbench.editor.labelFormat": "short",
  "explorer.compactFolders": false,
  "editor.semanticHighlighting.enabled": false,
  "breadcrumbs.enabled": true,
  "workbench.activityBar.location": "top",
  "editor.minimap.enabled": false,
  "workbench.statusBar.visible": true,
  "explorer.fileNesting.enabled": true,
  "explorer.fileNesting.patterns": {
    "package.json": "package-lock*, yarn*, pnpm-lock*, vite*, tsconfig*, prettier*, .eslint*",
    "tailwind.config*": "tailwind.config*, postcss.config*",
    ".env.local": ".env*",
    ".env": ".env*"
  },
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.fontFamily": "MesloLGS NF",

  /**
   * Origamid Defaults
   * https://www.origamid.com/slide/react-completo/#/0102-ferramentas/4
   **/
  "editor.tabSize": 2,
  "editor.tabCompletion": "on",
  "editor.wordWrap": "on",
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.donotVerifyTags": true,
  "explorer.confirmDragAndDrop": false,
  "editor.formatOnSave": true,
  "html.autoClosingTags": false,
  "editor.colorDecorators": false,
  "editor.autoClosingBrackets": "always",
  "editor.autoClosingQuotes": "always",
  "prettier.singleQuote": true,
  "files.associations": {
    "*.js": "javascriptreact"
  },
  "editor.minimap.renderCharacters": false,
  "telemetry.telemetryLevel": "all",
  "color-highlight.markerType": "dot-before",
  "editor.renderWhitespace": "selection",
  "prettier.trailingComma": "all",
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "explorer.sortOrder": "default",
  "window.title": "${rootName}",
  "window.newWindowDimensions": "offset",
  "html.format.wrapAttributes": "auto",
  "html.format.wrapLineLength": 0,
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.bracketPairColorization.enabled": false,

  /**
   * Better Defaults
   **/
  "editor.copyWithSyntaxHighlighting": false,
  "editor.emptySelectionClipboard": false,
  "workbench.editor.enablePreview": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "files.trimTrailingWhitespace": true,
  "diffEditor.renderSideBySide": false,
  "editor.snippetSuggestions": "top",
  "editor.detectIndentation": false,
  "files.insertFinalNewline": true,
  "files.trimFinalNewlines": true,

  /**
   * Find
   **/
  "search.useIgnoreFiles": false,
  "search.exclude": {
    "**/node_modules": true,
    "**/package-lock.json": true
  },

  /**
   * Code
   **/
  // Include "-" in word selection.
  "editor.wordSeparators": "`~!@#%^&*()=+[{]}\\|;:'\",.<>/?",

  /**
   * Custom
   **/
  "workbench.sideBar.location": "right",
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "codeium.aggressiveShutdown": true,
  "codeium.enableCodeLens": false,
  "codeium.enableSearch": true,
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.minimap.showSlider": "always",
  "git.confirmSync": false,
  "extensions.ignoreRecommendations": true,
  "explorer.confirmDelete": false,
  "files.eol": "\n",
  "workbench.tree.indent": 14,
  "terminal.integrated.defaultProfile.windows": "Command Prompt",
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "git.autofetch": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "git.enableSmartCommit": true,
  "formatFiles.excludedFolders": [
    "node_modules",
    ".vscode",
    ".git",
    "dist",
    ".chrome",
    "k8s",
    "bitbucket-pipelines.yml",
    "setup.sh",
    "/ ^.*(?<!.min)(.(css|js))$ / g"
  ],
  "formatFiles.runOrganizeImports": true,
  "editor.linkedEditing": true,
  "diffEditor.ignoreTrimWhitespace": false,
  "window.zoomLevel": 2,
  "codeium.enableConfig": {
    "*": true,
    "markdown": true
  },
  "remote.autoForwardPortsSource": "hybrid",
  "workbench.iconTheme": "vs-minimal",
  "window.commandCenter": false,
  "workbench.layoutControl.enabled": false,
  "redhat.telemetry.enabled": true,
  "git-graph.date.format": "Relative",
  "[python]": {
    "editor.defaultFormatter": "ms-python.black-formatter",
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
      "source.organizeImports": "explicit"
    }
  },
  "isort.args": ["--profile", "black"]
}
```

---
