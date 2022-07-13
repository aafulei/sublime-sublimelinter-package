# My SublimeLinter Package for Sublime Text 3

This package does nothing other than nullifying the default key bindings in the SublimeLinter Package for Sublime Text 3. In particular, I would like to use <kbd>Ctrl</kbd> + <kbd>Cmd</kbd> + <kbd>E</kbd> as the global keyboard shortcut in macOS to move focus to the menu bar, but the existing default key bindings in the SublimeLinter package contaminate the shortcut. This packages overrides the default key bindings and fixes the problem.

## Install

### macOS

```sh
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
[ -d "SublimeLinter" ] && mv SublimeLinter SublimeLinter.old && echo "Move directory SublimeLinter ===> SublimeLinter.old"
git clone https://github.com/aafulei/sublime-sublimelinter-package.git SublimeLinter
```

### Windows

```bat
cd %APPDATA%\Sublime Text 3\Packages
if exist SublimeLinter (move /Y SublimeLinter SublimeLinter.old) && (echo "Move directory SublimeLinter ===> SublimeLinter.old")
git clone https://github.com/aafulei/sublime-sublimelinter-package.git SublimeLinter
```
