# iTouch README

This extension is a modification of [nasc-vscode-mac-touchbar](https://github.com/on2-dev/nasc-vscode-mac-touchbar) extension since it is no longer getting updated and I wanted to add a few more features of my own.

## Features

The list of features are:

- Go to definition
- Add cursor above
- Add cursor below
- Run command
- Run Code using Code Runner extension
- Toggle side bar
- Toggle Panel/terminal
- Rename/replace all
- Duplicate lines
- Toggle white space characters
- Peek definition
- Show references
- Settings
- Indent
- Outdent
- Jump to matching bracket
- Block comment
- Comment line
- Select next
- Go to next
- Open Dash / Zeal
- Search Dash / Zeal with current selection

## Extension Settings

You can choose the buttons by setting the following settings.  
Please have in mind the limit of 5 active buttons (if you have the OS control strip enabled, 9 buttons if you don't). More than that will break the layout and the buttons will not be visible. It is possible to hide the default VSCode buttons, see **NOTES** at the end of the documentation.

- "arorashivoy-touchbar.goToDefinition": (default _true_) Go to the function or variable definition
- "arorashivoy-touchbar.addCursorAbove": (default _false_) Add a cursor in the line above
- "arorashivoy-touchbar.addCursorBelow": (default _true_) Add a cursor in the line below
- "arorashivoy-touchbar.selectNext": (default _false_) Selects next match 
- "arorashivoy-touchbar.toggleSidebar": (default _false_) Toggles the sidebar
- "arorashivoy-touchbar.togglePanel": (default _true_) Toggles the panel in the bottom of the editor
- "arorashivoy-touchbar.showCommands": (default _true_) Shows the _run command_ prompt
- "arorashivoy-touchbar.rename": (default _true_) Rename (replace all) variable or function names
- "arorashivoy-touchbar.copyLineDown": (default _false_) Duplicates the current line (or selected lines) 
- "arorashivoy-touchbar.goToNext": (default _false_) Go to next match
- "arorashivoy-touchbar.toggleWhiteSpace": (default _false_) Show or hide white spaces
- "arorashivoy-touchbar.peekDefinition": (default _false_) Peek definition/declaration
- "arorashivoy-touchbar.showReferences": (default _false_) List references who use the current symbol
- "arorashivoy-touchbar.settings": (default _false_) Open user settings
- "arorashivoy-touchbar.indent": (default _false_) Indent text
- "arorashivoy-touchbar.outdent": (default _false_) Outdent text
- "arorashivoy-touchbar.jumpToBracket": (default _false_) Jump to matching bracket
- "arorashivoy-touchbar.blockComment": (default _false_) Toggles block comments ( /* ... */ ) for the current selection
- "arorashivoy-touchbar.commentLine": (default _false_) Toggles line comments ( // ) for the current selection
- "arorashivoy-touchbar.formatDocument": (default _false_) Formats the current document
- "arorashivoy-touchbar.docs": (default _false_) Show documentation for current file in Dash / Zeal. Requires extension _deerawan.vscode-dash_
- "arorashivoy-touchbar.docsSelection": (default _false_) Shows documentation for current selection in Dash / Zeal, depending on the doctype. Requires extension _deerawan.vscode-dash_ If "arorashivoy-touchbar.docs" is enabled, then the docs icon will display when there is no selection, and will swap to this tool once text is selected. 
- "arorashivoy-touchbar.enableFuncGroup": (default _false_) Adds a group with the buttons related to _Functions_
- "arorashivoy-touchbar.enableSrcGroup": (default _false_)  Adds a group with the buttons related to the _Source code_
- "arorashivoy-touchbar.enableCursorsGroup": (default _false_)  Adds a group with the buttons related to your _cursors_
- "arorashivoy-touchbar.enableEditorGroup": (default _false_)  Adds a group with the buttons related to _editor's tools_
- "arorashivoy-touchbar.runCode": (default _false_) Run your code using the coderunnner extension from the TouchBar


## NOTES:

Important, if the buttons don't fit in the bar, they will not be shown (this is a current bug in VSCode support for the TouchBar and soon to be fixed). 
