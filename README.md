# VSCode

## Install `code` command

1. cmd + shift + P
2. `Shell Command: Install `code` command in PATH`

https://code.visualstudio.com/docs/setup/mac

## Settings

```json
// 既定の設定を上書きするには、このファイル内に設定を挿入します
{
    "editor.fontSize": 16,
    "editor.minimap.enabled": true,
    "editor.renderWhitespace": "all",
    "editor.renderControlCharacters": true,
    "editor.renderIndentGuides": true,
    "editor.tabSize": 2,
    "editor.wordSeparators": "`~!@#%^&*()=+[{]}\\|;:'\",.<>/?",
    "editor.wordWrap": "on",
    "terminal.external.osxExec": "iTerm.app",
    "window.restoreWindows": "all",
    "window.title": "${activeEditorLong}",
    "workbench.startupEditor": "newUntitledFile",
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
code --install-extension bradgashler.htmltagwrap
code --install-extension dbaeumer.vscode-eslint
code --install-extension DigitalBrainstem.javascript-ejs-support
code --install-extension eamodio.gitlens
code --install-extension EditorConfig.EditorConfig
code --install-extension eg2.vscode-npm-script
code --install-extension esbenp.prettier-vscode
code --install-extension felixfbecker.php-intellisense
code --install-extension file-icons.file-icons
code --install-extension henoc.svgeditor
code --install-extension imperez.smarty
code --install-extension mechatroner.rainbow-csv
code --install-extension monokai.theme-monokai-pro-vscode
code --install-extension mosapride.zenkaku
code --install-extension mrmlnc.vscode-apache
code --install-extension mrmlnc.vscode-csscomb
code --install-extension mrmlnc.vscode-scss
code --install-extension MS-CEINTL.vscode-language-pack-ja
code --install-extension naumovs.color-highlight
code --install-extension oderwat.indent-rainbow
code --install-extension ohansemmanuel.css-grid-snippets
code --install-extension pranaygp.vscode-css-peek
code --install-extension shardulm94.trailing-spaces
code --install-extension shyykoserhiy.vscode-spotify
code --install-extension vincaslt.highlight-matching-tag
code --install-extension wix.vscode-import-cost
code --install-extension wordpresstoolbox.wordpress-toolbox
code --install-extension yzhang.markdown-all-in-one
code --install-extension zhuangtongfa.Material-theme
code --install-extension Zignd.html-css-class-completion
```
