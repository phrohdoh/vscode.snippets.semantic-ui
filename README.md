# Semantic UI Snippets for Visual Studio Code

## Add a new snippet

1) Write a snippet in https://pawelgrzybek.com/snippet-generator
2) Copy the resulting JSON
3) Paste said JSON into `snippets.json`
4) Run `Format Document` command on `snippets.json`
5) Open a Pull Request

## Install

1. [Download Visual Studio Code](https://code.visualstudio.com/download?wt.mc_id=DX_841432) then launch it
2. Create a VSIX from this project (TODO: explain and github releases)
3. Install said VSIX (TODO: explain and github releases)

## Snippets

*Below are the currently implemented snippets*

| **Shortcut Prefix** | **Description** |
|---|---|
| **Buttons** | |
|`std-button` | `button`|
|`std-button-tooltip` | `button` with a tooltip|
|`std-button-disabled-tooltip` | `button` with class `disabled` and tooltip on a surrounding `span`|
|`ui-button-deny` | `div` with class `ui black deny button`|
|`ui-button-approve` | `div` with class `ui green approve right button`|
| **Misc** | |
|`ui-segment` | `div` with class `ui segment`|
|`ui-form` | `form` with class `ui form` and method `post`|
|`ui-header` | `div` with class `ui header`|
|`ui-clearing` | `div` with class `ui hidden clearing divider`|
|`ui-modal` | `div` with class `ui modal`|


## License

[![License][license-badge]][MIT License]

[MIT License]: http://en.wikipedia.org/wiki/MIT_License
[license-badge]: https://img.shields.io/badge/license-MIT-blue.svg