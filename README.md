# vscode-settings

```
// Place your key bindings in this file to override the defaults
[
    //--------------------------------------------------------------------------------
    /**
	 * Panels
	 */
    {
        "key": "ctrl+e",
        "command": "workbench.action.focusActiveEditorGroup"
    },
    {
        "key": "ctrl+alt+,",
        "command": "workbench.action.openSettingsJson"
    },
    {
        "key": "ctrl+alt+b",
        "command": "workbench.action.toggleActivityBarVisibility"
    },
    //--------------------------------------------------------------------------------
    /**
	 * Fold/Unfold
	 **/
    {
        "key": "ctrl+shift+[",
        "command": "editor.fold",
        "when": "editorTextFocus && foldingEnabled"
    },
    {
        "key": "ctrl+shift+]",
        "command": "editor.unfold",
        "when": "editorTextFocus && foldingEnabled"
    },
    //--------------------------------------------------------------------------------
    /**
	 * File Explorer
	 **/
    {
        "key": "ctrl+d",
        "command": "duplicate.execute",
        "when": "explorerViewletVisible && filesExplorerFocus && !explorerResourceIsRoot && !inputFocus"
    },
    {
        "key": "ctrl+n",
        "command": "explorer.newFile",
        "when": "explorerViewletVisible && filesExplorerFocus && !inputFocus"
    },
    {
        "key": "shift+ctrl+n",
        "command": "explorer.newFolder",
        "when": "explorerViewletVisible && filesExplorerFocus && !inputFocus"
    },
    {
        "key": "f5",
        "command": "multiCommand.refreshAndCollapse",
        "when": "explorerViewletVisible && filesExplorerFocus && !inputFocus"
    },
    //--------------------------------------------------------------------------------
    /**
	 * Multi-Cursor with Multiple Selections
	 **/
    {
        "key": "ctrl+backspace",
        "command": "editor.action.moveSelectionToPreviousFindMatch",
        "when": "editorFocus && editorHasMultipleSelections"
    },
    {
        "key": "ctrl+k ctrl+d",
        "command": "editor.action.moveSelectionToNextFindMatch",
        "when": "editorFocus && editorHasMultipleSelections"
    },
    {
        "key": "ctrl+right",
        "command": "editor.action.insertCursorAtEndOfEachLineSelected",
        "when": "editorFocus && editorHasSelection"
    },
    //--------------------------------------------------------------------------------
    /**
	 * Split Panels
	 **/
    {
        "key": "alt+n",
        "command": "workbench.action.splitEditor",
        "when": "editorFocus"
    },
    {
        "key": "alt+j",
        "command": "workbench.action.joinAllGroups",
        "when": "editorFocus"
    },
    // {
    //     "key": "alt+l",
    //     "command": "workbench.action.navigateRight",
    //     "when": "editorFocus"
    // },
    {
        "key": "alt+h",
        "command": "workbench.action.navigateLeft",
        "when": "editorFocus"
    },
    {
        "key": "alt+=",
        "command": "workbench.action.increaseViewSize",
        "when": "editorFocus"
    },
    {
        "key": "alt+-",
        "command": "workbench.action.decreaseViewSize",
        "when": "editorFocus"
    },
    //--------------------------------------------------------------------------------
    /**
	 * Terminal Split Panel
	 **/
    {
        "key": "alt+n",
        "command": "workbench.action.terminal.split",
        "when": "terminalFocus"
    },
    {
        "key": "alt+w",
        "command": "workbench.action.terminal.kill",
        "when": "terminalFocus"
    },
    {
        "key": "alt+k",
        "command": "workbench.action.terminal.clear",
        "when": "terminalFocus"
    },
    {
        "key": "alt+l",
        "command": "workbench.action.terminal.focusNextPane",
        "when": "terminalFocus"
    },
    {
        "key": "alt+h",
        "command": "workbench.action.terminal.focusPreviousPane",
        "when": "terminalFocus"
    },
    {
        "key": "alt+m",
        "command": "workbench.action.toggleMaximizedPanel",
    },
    {
        "key": "ctrl+w",
        "command": "workbench.action.terminal.kill",
        "when": "terminalFocus"
    },
    {
        "key": "ctrl+tab",
        "command": "workbench.action.terminal.focusNext",
        "when": "terminalFocus"
    },
    {
        "key": "ctrl+shift+tab",
        "command": "workbench.action.terminal.focusPrevious",
        "when": "terminalFocus"
    },
    {
        "key": "alt+1",
        "command": "workbench.action.terminal.focusAtIndex1",
        "when": "terminalFocus"
    },
    {
        "key": "alt+2",
        "command": "workbench.action.terminal.focusAtIndex2",
        "when": "terminalFocus"
    },
    {
        "key": "alt+3",
        "command": "workbench.action.terminal.focusAtIndex3",
        "when": "terminalFocus"
    },
    {
        "key": "alt+4",
        "command": "workbench.action.terminal.focusAtIndex4",
        "when": "terminalFocus"
    },
    {
        "key": "alt+5",
        "command": "workbench.action.terminal.focusAtIndex5",
        "when": "terminalFocus"
    },
    {
        "key": "alt+6",
        "command": "workbench.action.terminal.focusAtIndex6",
        "when": "terminalFocus"
    },
    {
        "key": "alt+7",
        "command": "workbench.action.terminal.focusAtIndex7",
        "when": "terminalFocus"
    },
    {
        "key": "alt+8",
        "command": "workbench.action.terminal.focusAtIndex8",
        "when": "terminalFocus"
    },
    {
        "key": "alt+9",
        "command": "workbench.action.terminal.focusAtIndex9",
        "when": "terminalFocus"
    },
    //--------------------------------------------------------------------------------
    /**
	 * Emmet
	 **/
    {
        "key": "ctrl+m ctrl+i",
        "command": "editor.emmet.action.balanceIn",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+m ctrl+o",
        "command": "editor.emmet.action.balanceOut",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+m ctrl+w",
        "command": "editor.emmet.action.wrapWithAbbreviation",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+m ctrl+m",
        "command": "editor.emmet.action.matchTag",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+m ctrl+e",
        "command": "editor.action.smartSelect.expand",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+m ctrl+r",
        "command": "editor.emmet.action.updateTag",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+m ctrl+backspace",
        "command": "editor.emmet.action.removeTag",
        "when": "editorTextFocus"
    },
    {
        "key": "numpad_subtract",
        "command": "editor.emmet.action.decrementNumberByOneTenth",
        "when": "editorHasSelection"
    },
    {
        "key": "numpad_add",
        "command": "editor.emmet.action.incrementNumberByOneTenth",
        "when": "editorHasSelection"
    },
    {
        "key": "alt+numpad_subtract",
        "command": "editor.emmet.action.decrementNumberByOne",
        "when": "editorHasSelection"
    },
    {
        "key": "ctrl+alt+numpad_subtract",
        "command": "editor.emmet.action.decrementNumberByTen",
        "when": "editorHasSelection"
    },
    {
        "key": "alt+numpad_add",
        "command": "editor.emmet.action.incrementNumberByOne",
        "when": "editorHasSelection"
    },
    {
        "key": "ctrl+alt+numpad_add",
        "command": "editor.emmet.action.incrementNumberByTen",
        "when": "editorHasSelection"
    },
    //--------------------------------------------------------------------------------
    /**
	 * Project Switching
	 **/
    {
        "key": "ctrl+r",
        "command": "-workbench.action.openRecent"
    },
    {
        "key": "ctrl+oem_1",
        "command": "workbench.action.openRecent"
    },
    {
        "key": "ctrl+alt+;",
        "command": "workbench.action.switchWindow",
        "when": "! config.simple-project-switcher.present"
    },
    //--------------------------------------------------------------------------------
    /**
	 * Open DevTools
	 **/
    {
        "key": "ctrl+shift+i",
        "command": "workbench.action.toggleDevTools"
    },
    //--------------------------------------------------------------------------------
    /**
	 *  Live Server
	 **/
    {
        "key": "alt+s alt+s",
        "command": "extension.liveServer.goOnline",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+l alt+o",
        "command": "-extension.liveServer.goOnline",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+s alt+c",
        "command": "extension.liveServer.goOffline",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+l alt+c",
        "command": "-extension.liveServer.goOffline",
        "when": "editorTextFocus"
    },
    //--------------------------------------------------------------------------------
    /**
	 *  Prettier
	 **/
    {
        "key": "ctrl+alt+p",
        "command": "prettier.forceFormatDocument",
        "when": "editorTextFocus"
    },
    //--------------------------------------------------------------------------------
    /**
	 *  Live Preview
	 **/
    {
        "key": "shift+alt+p",
        "command": "livePreview.start.internalPreview.atFile",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+shift+g",
        "command": "workbench.view.scm",
        "when": "workbench.scm.active && !gitlens:disabled && config.gitlens.keymap == 'chorded'"
    },
    {
        "key": "ctrl+shift+g g",
        "command": "-workbench.view.scm",
        "when": "workbench.scm.active && !gitlens:disabled && config.gitlens.keymap == 'chorded'"
    },
]

```

```
{
    //--------------------------------------------------------------------------------
    //---------------  Cursor  ---------------
    //--------------------------------------------------------------------------------
    "editor.cursorBlinking": "expand",
    "editor.cursorStyle": "block",
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.multiCursorModifier": "alt",
    //--------------------------------------------------------------------------------
    //---------------  Typography or Fonts Setup  ---------------
    //--------------------------------------------------------------------------------
    "editor.fontFamily": "Monolisa, Fira code, Operator Mono",
    "editor.fontLigatures": true,
    "editor.fontSize": 13,
    "editor.lineHeight": 28,
    "editor.fontWeight": "450",
    "editor.letterSpacing": 0.5,
    "editor.suggestFontSize": 15,
    "editor.suggestLineHeight": 28,
    "terminal.integrated.fontSize": 15,
    "terminal.integrated.lineHeight": 1.25,
    // "editor.mouseWheelZoom": true,
    "explorer.openEditors.visible": 0,
    "explorer.confirmDelete": false,
    "explorer.confirmDragAndDrop": false,
    "editor.copyWithSyntaxHighlighting": false,
    "editor.emptySelectionClipboard": true,
    "window.newWindowDimensions": "maximized",
    "window.menuBarVisibility": "toggle",
    "workbench.sideBar.location": "right",
    "editor.suggest.preview": true,
    "editor.wordWrap": "on",
    "workbench.startupEditor": "none",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.productIconTheme": "icons-carbon",
    "workbench.colorTheme": "Palenight Operator",
    "material-icon-theme.folders.color": "#f6d572",
    "window.title": "(ツ)_/¯ ${dirty}${activeEditorShort}${separator}${rootName}",
    //--------------------------------------------------------------------------------
    //---------------  Tab Settings  ---------------
    //--------------------------------------------------------------------------------
    "workbench.editor.pinnedTabSizing": "shrink",
    "workbench.editor.tabCloseButton": "off",
    "workbench.editor.highlightModifiedTabs": true,
    // "workbench.editor.wrapTabs": true
    //--------------------------------------------------------------------------------
    //---------------  White Space Settings  ---------------
    //--------------------------------------------------------------------------------
    "editor.renderWhitespace": "all",
    "files.insertFinalNewline": true,
    "files.trimFinalNewlines": true,
    "files.trimTrailingWhitespace": true,
    "diffEditor.ignoreTrimWhitespace": false,
    //--------------------------------------------------------------------------------
    //---------------  Format Settings  ---------------
    //--------------------------------------------------------------------------------
    "editor.formatOnType": true,
    "editor.formatOnSave": true,
    //--------------------------------------------------------------------------------
    //---------------  Minimap Settings  ---------------
    //--------------------------------------------------------------------------------
    "editor.minimap.scale": 1,
    "editor.minimap.size": "fit",
    "editor.minimap.enabled": true,
    "editor.minimap.showSlider": "always",
    //--------------------------------------------------------------------------------
    //---------------  Emmet Settings  ---------------
    //--------------------------------------------------------------------------------
    "emmet.triggerExpansionOnTab": true,
    "emmet.showSuggestionsAsSnippets": false,
    "emmet.includeLanguages": {
        "javascript": "javascriptreact",
        "typescript": "typescriptreact"
    },
    //--------------------------------------------------------------------------------
    //---------------  Better editor Defaults  ---------------
    //--------------------------------------------------------------------------------
    "workbench.editor.showTabs": "multiple",
    // "editor.renderIndentGuides": true,
    "editor.glyphMargin": false,
    // "editor.lineNumbers": "off",
    // "editor.folding": false,
    // "files.autoSave": "afterDelay",
    // "files.autoSaveDelay": 1000,
    "editor.snippetSuggestions": "top",
    "editor.tabCompletion": "on",
    "editor.quickSuggestionsDelay": 0,
    "editor.quickSuggestions": {
        "other": true,
        "comments": true,
        "strings": true
    },
    "editor.detectIndentation": false,
    "editor.scrollbar.verticalScrollbarSize": 0,
    "editor.scrollbar.horizontalScrollbarSize": 0,
    "editor.suggest.showStatusBar": true,
    "javascript.inlayHints.parameterNames.enabled": "all",
    "typescript.inlayHints.parameterNames.enabled": "all",
    "js/ts.implicitProjectConfig.checkJs": true,
    // "extensions.ignoreRecommendations": true,
    //--------------------------------------------------------------------------------
    //---------------  Format Settings & Prettier  ---------------
    //--------------------------------------------------------------------------------
    // "editor.defaultFormatter": "esbenp.prettier-vscode",
    "javascript.preferences.quoteStyle": "single",
    "typescript.preferences.quoteStyle": "single",
    "prettier.jsxSingleQuote": true,
    "[json]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode",
    },
    "[jsonc]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[css]": {
        "editor.defaultFormatter": "vscode.css-language-features"
    },
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    //--------------------------------------------------------------------------------
    //---------------  Terminal Settings  ---------------
    //--------------------------------------------------------------------------------
    "terminal.integrated.cursorBlinking": true,
    "terminal.integrated.fontFamily": "Monolisa, Fira code, Operator Mono",
    "terminal.integrated.defaultProfile.windows": "Git Bash",
    "workbench.colorCustomizations": {
        "editorCursor.foreground": "#fdff6a",
        "terminal.foreground": "#C0C0C0",
        "terminal.background": "#000000",
        "terminal.selectionBackground": "#ffffff",
        "terminalCursor.background": "#C0C0C0",
        "terminalCursor.foreground": "#abec12",
        "terminal.ansiBlack": "#000000",
        "terminal.ansiBlue": "#0000D3",
        "terminal.ansiBrightBlack": "#808080",
        "terminal.ansiBrightBlue": "#0000D3",
        "terminal.ansiBrightCyan": "#02ABEA",
        "terminal.ansiBrightGreen": "#1FB714",
        "terminal.ansiBrightMagenta": "#4700A5",
        "terminal.ansiBrightRed": "#DD0907",
        "terminal.ansiBrightWhite": "#FFFFFF",
        "terminal.ansiBrightYellow": "#FBF305",
        "terminal.ansiCyan": "#02ABEA",
        "terminal.ansiGreen": "#1FB714",
        "terminal.ansiMagenta": "#4700A5",
        "terminal.ansiRed": "#DD0907",
        "terminal.ansiWhite": "#C0C0C0",
        "terminal.ansiYellow": "#FBF305",
        //improved theme details
        "tab.activeBorder": "#80CBC4",
        "tab.activeBackground": "#2d4240",
        "tab.lastPinnedBorder": "#ff0000",
        "editorLineNumber.activeForeground": "#ffffff",
        "editorLineNumber.foreground": "#b6b6b6",
        //improved minimap details
        // "minimapSlider.background": "#62578da2",
        // "minimapSlider.hoverBackground": "#62578da2"
    },
    // "terminal.integrated.profiles.windows": {
    // 	"wt": {
    // 		"path": "C:\\Users\\ABHISHEK\\AppData\\Local\\Microsoft\\WindowsApps\\wt.exe"
    // 	},
    // },
    //--------------------------------------------------------------------------------
    //---------------  Git Settings  ---------------
    //--------------------------------------------------------------------------------
    "git.autofetch": true,
    // "git.enableSmartCommit": true,
    // "git.confirmSync": true,
    //--------------------------------------------------------------------------------
    //---------------  GitLens Settings  ---------------
    //--------------------------------------------------------------------------------
    // "gitlens.views.repositories.files.layout": "auto", // Updated since 9.0.0 - 2018-12-02.
    // "gitlens.currentLine.enabled": false,
    // "gitlens.hovers.enabled": false,
    // "gitlens.keymap": "alternate",
    // "gitlens.advanced.messages": {
    //     "suppressShowKeyBindingsNotice": true
    // },
    //--------------------------------------------------------------------------------
    //---------------  Better Extension Settings  ---------------
    //---------------  IntelliSense for CSS class names in HTML Settings  ---------------
    "editor.linkedEditing": true,
    "html-css-class-completion.enableEmmetSupport": true,
    //---------------  Multi Command Settings  ---------------
    "multiCommand.commands": [
        {
            "command": "multiCommand.refreshAndCollapse",
            "sequence": [
                "workbench.files.action.refreshFilesExplorer",
                "workbench.files.action.collapseExplorerFolders"
            ]
        },
    ],
    //---------------  Peacock Settings  ---------------
    "peacock.affectAccentBorders": true,
    "peacock.elementAdjustments": {
        "activityBar": "none"
    },
    "peacock.favoriteColors": [
        {
            "name": "Angular Red",
            "value": "#dd0531"
        },
        {
            "name": "Azure Blue",
            "value": "#007fff"
        },
        {
            "name": "JavaScript Yellow",
            "value": "#f9e64f"
        },
        {
            "name": "Mandalorian Blue",
            "value": "#1857a4"
        },
        {
            "name": "Node Green",
            "value": "#215732"
        },
        {
            "name": "React Blue",
            "value": "#61dafb"
        },
        {
            "name": "Something Different",
            "value": "#832561"
        },
        {
            "name": "Svelte Orange",
            "value": "#ff3d00"
        },
        {
            "name": "Vue Green",
            "value": "#42b883"
        }
    ],
    //---------------  Prettier Settings  ---------------
    "prettier.tabWidth": 2,
    "prettier.useTabs": true,
    "prettier.singleQuote": true,
    // "prettier.requireConfig": true,
    // "prettier.useEditorConfig": false,
    //---------------  Live Server Settings  ---------------
    "liveServer.settings.donotShowInfoMsg": true,
    "editor.accessibilitySupport": "off",
    "security.workspace.trust.untrustedFiles": "open",
    "vscode-office.openOutline": false,
    "window.zoomLevel": 1,
    "editor.stickyScroll.enabled": true,
    "[typescriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "leetcode.defaultLanguage": "java",
    "leetcode.workspaceFolder": "c:\\Users\\ABHISHEK\\Workspace\\Leetcode",
    "leetcode.showLocked": true,
    "css2react.singleQuotes": true,
    "diffEditor.renderSideBySide": false,
    "workbench.editor.enablePreview": false,
    "[scss]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "html-css-class-completion.includeGlobPattern": "**/*.{css,html,jsx}",
    "redhat.telemetry.enabled": false,
    "openapi.platformUrl": "https://platform.42crunch.com/",
    "workbench.editor.empty.hint": "hidden",
    "workbench.editor.tabActionCloseVisibility": false,
    "workbench.activityBar.location": "hidden",
}
```
