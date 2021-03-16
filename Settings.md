# Settings

These are my settings for Visual Studio Code:

```
{
	// Bracket Pair Colorizer
	"bracket-pair-colorizer-2.forceUniqueOpeningColor": true,
	// General editor settings
	"editor.cursorBlinking": "solid",
	"editor.cursorStyle": "line",
	"editor.cursorWidth": 5,
	"editor.fontFamily": "'Fira Code'",
	"editor.fontLigatures": true,
	"editor.fontSize": 14,
	"editor.fontWeight": "400",
	"editor.formatOnSave": false,
	"editor.insertSpaces": false,
	"editor.letterSpacing": 0.5,
	"editor.lineHeight": 25,
	"editor.quickSuggestions": { "comments": true },
	"editor.renderControlCharacters": true,
	"editor.renderWhitespace": "all",
	"editor.snippetSuggestions": "top",
	"explorer.openEditors.visible": 10,
	"extensions.ignoreRecommendations": true,
	"files.trimTrailingWhitespace": true,
	// Git show how many changes local repo is behind the remote
	"git.autofetch": true,
	// Indent <head> and <body> inside <html>
	"html.format.indentInnerHtml": true,
	// Intelephense
	"intelephense.completion.fullyQualifyGlobalConstantsAndFunctions": true,
	"intelephense.format.braces": "allman",
	"intelephense.environment.phpVersion": "7.4.16",
	"intelephense.files.associations": [
		"*.php",
		"*.phtml"
	],
	"intelephense.phpdoc.functionTemplate": {
		"summary": "$1",
		"tags": [
			"@param ${1:$SYMBOL_TYPE} $SYMBOL_NAME $2",
			"@return ${1:$SYMBOL_TYPE} $2",
			"@throws ${1:$SYMBOL_TYPE} $2"
		]
	},
	// phpfmt - PHP Code Formatter
	"phpfmt.detect_indent": true,
	"phpfmt.exclude": [
		"ReindentComments",
		"StripNewlineWithinClassBody"
	],
	"phpfmt.indent_with_space": true,
	"phpfmt.passes": [
		"PSR2KeywordsLowerCase",
		"PSR2LnAfterNamespace",
		"PSR2CurlyOpenNextLine",
		"PSR2ModifierVisibilityStaticOrder",
		"PSR2SingleEmptyLineAndStripClosingTag",
		"ReindentSwitchBlocks",
		"AlignConstVisibilityEquals",
		"AlignEquals",
		"AllmanStyleBraces",
		"AlignDoubleSlashComments"
	],
	// Add your path to your php executable below:
	"phpfmt.php_bin": "/usr/local/bin/php",
	"phpfmt.psr2": false,
	// Prettier - Code formatter
	"prettier.tabWidth": 4,
	"prettier.useTabs": false,
	// Workbech color settings
	"workbench.colorCustomizations": {
		"activityBarBadge.background": "#616161",
		"list.activeSelectionForeground": "#616161",
		"list.inactiveSelectionForeground": "#616161",
		"list.highlightForeground": "#616161",
		"scrollbarSlider.activeBackground": "#61616150",
		"editorSuggestWidget.highlightForeground": "#616161",
		"textLink.foreground": "#616161",
		"progressBar.background": "#616161",
		"pickerGroup.foreground": "#616161",
		"tab.activeBorder": "#616161",
		"notificationLink.foreground": "#616161",
		"editorWidget.resizeBorder": "#616161",
		"editorWidget.border": "#616161",
		"settings.modifiedItemIndicator": "#616161",
		"settings.headerForeground": "#616161",
		"panelTitle.activeBorder": "#616161",
		"breadcrumb.activeSelectionForeground": "#616161",
		"menu.selectionForeground": "#616161",
		"menubar.selectionForeground": "#616161"
	},
	"workbench.colorTheme": "Cobalt2",
	"workbench.editor.closeOnFileDelete": true,
	"workbench.editor.labelFormat": "long",
	"workbench.iconTheme": "helium-icon-theme",
	"workbench.startupEditor": "newUntitledFile",
	// Zoom level
	"window.zoomLevel": 1,
	// Code formatters
	"[css]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[html]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[javascript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[less]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[php]": {
		"editor.defaultFormatter": "kokororin.vscode-phpfmt"
	},
	"[scss]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[xml]": {
		"editor.defaultFormatter": "DotJoshJohnson.xml"
	},
}
```