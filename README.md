# VSCode

## Install `code` command

1. cmd + shift + P
2. `Shell Command: Install `code` command in PATH`

https://code.visualstudio.com/docs/setup/mac

## Settings

```json
// 既定の設定を上書きするには、このファイル内に設定を挿入します
{
    "breadcrumbs.enabled": false,
    // https://www.jenniferkonikowski.com/
    "bracket-pair-colorizer-2.colors": [
        "LightSkyBlue",
        // "DodgerBlue",
        "MediumSlateBlue",
        // "BlueViolet",
        "MediumVioletRed",
        "DeepPink",
        // "Red",
        // "DarkOrange",
        "Gold",
        // "GreenYellow",
        "LimeGreen",
        // "LightSeaGreen",
        "DarkTurquoise"
    ],
    "css.lint.duplicateProperties": "warning",
    "css.lint.emptyRules": "ignore",
    "css.lint.unknownVendorSpecificProperties": "warning",
    "css.lint.zeroUnits": "warning",
    "csscomb.preset": "~/csscomb.json",
    "editor.colorDecorators": false,
    "editor.fontSize": 16,
    "editor.minimap.renderCharacters": false,
    "editor.minimap.showSlider": "always",
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.renameOnType": true,
    "editor.renderControlCharacters": true,
    "editor.renderIndentGuides": true,
    "editor.renderWhitespace": "all",
    "editor.showFoldingControls": "always",
    "editor.snippetSuggestions": "top",
    "editor.tabCompletion": "on",
    "editor.tabSize": 2,
    "editor.wordSeparators": "`~!@#%^&*()=+[{]}\\|;:'\",.<>/?",
    "editor.wordWrap": "on",
    "emmet.includeLanguages": {
        "ejs": "html",
        "vue-html": "html"
    },
    "emmet.showSuggestionsAsSnippets": true,
    "emmet.syntaxProfiles": {
        "scss": {
            "attr_quotes": "single"
        }
    },
    "emmet.triggerExpansionOnTab": true,
    "emmet.variables": {
        "lang": "ja"
    },
    "files.associations": {
        "*.sass": "scss",
        "*.ejs": "html"
    },
    "files.autoGuessEncoding": true,
    "files.defaultLanguage": "${activeEditorLanguage}",
    "files.insertFinalNewline": true,
    "gitlens.codeLens.enabled": false,
    "gitlens.defaultDateStyle": "absolute",
    "html.autoClosingTags": false,
    "oneDarkPro.bold": true,
    "php.suggest.basic": false,
    "scss.lint.duplicateProperties": "warning",
    "scss.lint.unknownVendorSpecificProperties": "warning",
    "scss.lint.zeroUnits": "warning",
    "telemetry.enableCrashReporter": false,
    "telemetry.enableTelemetry": false,
    "terminal.integrated.fontSize": 16,
    "scss.lint.emptyRules": "ignore",
    "scss.lint.universalSelector": "warning",
    "terminal.external.osxExec": "iTerm.app",
    "terminal.integrated.scrollback": 10000,
    "window.title": "${dirty}${activeEditorMedium}${separator}${rootName}",
    "window.zoomLevel": 0,
    "workbench.colorTheme": "Atom One Dark",
    "workbench.editor.closeEmptyGroups": false,
    "workbench.iconTheme": "file-icons",
    "workbench.startupEditor": "newUntitledFile",
    "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[json]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
}
```

## Extensions

```sh
$ code --list-extensions | xargs -L 1 echo code --install-extension
code --install-extension 2gua.rainbow-brackets
code --install-extension aaron-bond.better-comments
code --install-extension akamud.vscode-theme-onedark
code --install-extension alefragnani.project-manager
code --install-extension auchenberg.vscode-browser-preview
code --install-extension be5invis.vscode-custom-css
code --install-extension bmewburn.vscode-intelephense-client
code --install-extension bradgashler.htmltagwrap
code --install-extension dakshmiglani.hex-to-rgba
code --install-extension dbaeumer.vscode-eslint
code --install-extension DigitalBrainstem.javascript-ejs-support
code --install-extension dzhavat.css-initial-value
code --install-extension eamodio.gitlens
code --install-extension EditorConfig.EditorConfig
code --install-extension eg2.vscode-npm-script
code --install-extension esbenp.prettier-vscode
code --install-extension felixfbecker.php-intellisense
code --install-extension file-icons.file-icons
code --install-extension henoc.svgeditor
code --install-extension imperez.smarty
code --install-extension mechatroner.rainbow-csv
code --install-extension mkaufman.HTMLHint
code --install-extension monokai.theme-monokai-pro-vscode
code --install-extension mosapride.zenkaku
code --install-extension mrmlnc.vscode-apache
code --install-extension mrmlnc.vscode-csscomb
code --install-extension mrmlnc.vscode-scss
code --install-extension MS-CEINTL.vscode-language-pack-ja
code --install-extension ms-vsliveshare.vsliveshare
code --install-extension naumovs.color-highlight
code --install-extension oderwat.indent-rainbow
code --install-extension ohansemmanuel.css-grid-snippets
code --install-extension pranaygp.vscode-css-peek
code --install-extension shardulm94.trailing-spaces
code --install-extension vincaslt.highlight-matching-tag
code --install-extension wix.vscode-import-cost
code --install-extension wordpresstoolbox.wordpress-toolbox
code --install-extension yusukehirao.vscode-markuplint
code --install-extension yzhang.markdown-all-in-one
code --install-extension zhuangtongfa.material-theme
code --install-extension Zignd.html-css-class-completion
```

PHP Intellisense のインストール後、VSCode にプリインストールされている PHP Language Features を無効にする
