# Ultimate VSCode Setup

## Disclaimer

This set up is purely my own developer preference. This setup does not infer, in any way, that other setups are inferior or incorrect.

## Extensions

To install the following packages, click on the Extensions tab in the left hand sidebar, and then search the `author.package_name` as displayed in parentheses `()`.

-   Bracket Pair Colorizer 2 (coenraads.bracket-pair-colorizer-2)
-   Color Highlight (naumovs.color-highlight)
-   Prettier (esbenp.prettier-vscode)
-   DotENV (mikestead.dotenv)
-   ES7 React/Redux/GraphQL/React-Native Snippets (dsznajder.es7-react-js-snippets)
-   Markdown Preview Github Styling (bierner.markdown-preview-github-styles)

## Theme

-   Dracula Official (dracula-theme.theme-dracula)
    -   Hit `CMD+Shift+P`
    -   Type `Theme`
    -   Open: `Preferences: Color Theme`
    -   Enable `Dracula Soft`
-   Material Icon Theme (pkief.material-icon-theme)
-   Font is `Cascadia Code` by Microsoft
-   Ligatures are enabled (see config below)

## Settings

To modify your settings file, hit `CMD+Shift+P` and select `Preferences: Open Settings (JSON)`.

Here is my chosen configuration. You are responsible for understanding the configuration and make any changes to your own at your own risk.

```
{
  "editor.formatOnSave": true,
  "editor.fontFamily": "'Cascadia Code', Consolas, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.suggestSelection": "first",
  "editor.wordWrap": "on",
  "editor.fontSize": 14,
  "workbench.colorTheme": "Dracula Soft",
  "workbench.iconTheme": "material-icon-theme",
  "terminal.integrated.fontSize": 14,
  "prettier.semi": true,
  "prettier.tabWidth": 4,
  "prettier.singleQuote": true,
  "prettier.trailingComma": "none"
}
```
