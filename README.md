# VS Code Settings

## Folder to clone to
_If cloned to the appropriate folder, all the VS Code settings will be applied
automatically, and pulling the latest changes will give you the latest settings.
There are however some settings that need to be applied manually, for this,
see <!-- [Offline Spell Checker](#offline-spell-checker-apply-manually) and --> [Theming](#theming-apply-manually)._

For Windows:
```
C:\Users\yourusername\AppData\Roaming\Code\User
```

For Mac:
```
/Users/yourusername/Library/Application Support/Code/User
```

## Keybindings
File > Preferences > Keyboard Shortcuts <br />
Use: [keybindings.json](keybindings.json)

| Key | Function |
|----------|-------------|
| ctrl+shift+down | move lines down |
| ctrl+shift+up | move lines up |
| ctrl+d | duplicate lines |
| ctrl+shift+l | format |
| ctrl+e | preview declaration |
| ctrl+shift+t | terminate |
| ctrl+shift+o | toggle output |
| ctrl+enter | open command palette |
| ctrl+shift+enter | open command palette to run command |

## Snippets

Use: [css.json](snippets/css.json), [scss.json](snippets/scss.json), [javascript.json](snippets/javascript.json), [typescript.json](snippets/typescript.json)

- Beginning and ending a section.
- tslint disable linting of the next line.
- Common [Publish-subscribe-library](https://github.com/jamesdeklerk/publish-subscribe-library) functions.

<!--
## Offline Spell Checker (apply manually)
```
ext install spellchecker
```
_Use ctrl+. to get suggestion menu._-->

## Theming (apply manually)
```
ext install Theme-MaterialKit
```

#### Color Theme
File > Preferences > Color Theme > Material Night Eighties

#### File Icon Theme
File > Preferences > File Icon Theme > Seti (Visual Studio Code)