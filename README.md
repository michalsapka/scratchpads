# Scratchpads README
Create multiple scratchpad files for doodling while you're coding.

## Highlights
* Create multiple scratchpads
* Create scratchpads of different languages and file types
* Enjoy VSCode intellisense in your scratchpads
* Scratchpad are not interfering your project and can be removed at any time

## Features

### Add a new screatchpad
* Run the command "Screatchpads: New scratchpad" from the Command Palette
* Select the desired file type

![Create new Scratchpas](https://raw.githubusercontent.com/buenon/scratchpads/master/images/scratchpad_new.gif)

### Remove scratchpad files
* Run the command "Screatchpads: Remove scratchpads" from the Command Palette

*\* Removing scratchpad files loops through all the open tabs and closes the scratchpad ones before deleting the files (might seem wierd)*

### Add a new file type to the list
* Run the command "Screatchpads: New scratchpad" from the Command Palette
* Select "Add custome..." from the list
* Enter the file type's name
* enter the file's extension

![Add a new file type](https://raw.githubusercontent.com/buenon/scratchpads/master/images/scratchpad_add.gif)

### Remove file types from the list
* Run the command "Screatchpads: New scratchpad" from the Command Palette
* Select "Remove..." from the list
* Check the file types you wish to remove and hit enter

![Remove file types](https://raw.githubusercontent.com/buenon/scratchpads/master/images/scratchpad_remove.gif)

### Restore default file type list
* Run the command "Screatchpads: New scratchpad" from the Command Palette
* Select "Restore defaults..." from the list

## Available Commands
* New scratchpad (scratchpads.newScratchpad)
* Remove scratchpad (scratchpads.removeScratchpad)

## Keyboard Shortcuts
You can find instructions on adding short cuts to the commands above on [VSCode website](https://code.visualstudio.com/docs/customization/keybindings).

## Extension Settings

This extension contributes the following settings:

* `scratchpads.promptForRemoval`: By default set to `true`. If set to `false` the user will not be prompted for confirmation when removing scratchpad files.

## Source

[GitHub](https://github.com/buenon/scratchpads)

## License

[MIT](https://raw.githubusercontent.com/buenon/scratchpads/master/LICENSE)
