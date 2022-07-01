# px to PX

This is an extension for Visual Studio Code that allows you to convert px to PX, and vice versa.

## Usage

### Keybindings

- `Alt+Z` Px to PX, and PX to px. Converts selected text from px to PX, and PX to px.
- `Alt+S` Asks for a new px per PX value.

![]

### Commands

- Px to PX, and PX to px. Converts selected text from px to PX, and PX to px.
- Px to PX. Converts selected text from px to PX
- PX to px. Converts selected text from PX to px
- Px per PX. Asks for a new px per PX value.

## Extension Settings

This extension contributes the following settings:

- `px-to-PX.px-per-PX`: number of pixels per PX. Default is `16px`.
- `px-to-PX.number-of-decimals-digits`: maximum number of decimals digits a px or PX can have
- `px-to-PX.only-change-first-ocurrence`: set to change all or only the first selected ocurrence of px/PX
- `px-to-PX.notify-if-no-changes`: enable/disable notification that alerts the users if no conversion could be made

## Known Issues

- If you select a value with multiple cursors it will get converted, but following cursors may change place after the conversion.
- '_Edits from command extension.pxToPXAndPXToPx were not applied_' message appears in debug console.

## Release Notes

### 1.0.0

Initial release

---

## Contributing

Feel free to fork this repository and use it the way you like. If you want to propose a nice new feature, just create a pull request from you forked branch.
[My github]

**Enjoy!**
