# Embark for Windows Terminal
An ambitious theme for windows terminal

## Instructions
Open up your Windows Terminal application and press the shortcut Ctrl+, on your keyboard to open up your Windows Terminal settings json file. Once opened in your favorite text editor, look for the `"schemes": []` array in your settings. Copy and paste the code in the `embark.json` from this repo into the schemes array. To activate it, either add the line `"colorScheme": "Embark"` to your `"profiles"` -> `"defaults"` object (to affect every profile) or to the specific shell profile you want to use it with (i.e. you want Embark for your PowerShell profile, but not for your Ubuntu WSL profile). Consult the official [Windows Terminal Docs](https://docs.microsoft.com/en-us/windows/terminal/customize-settings/color-schemes) for more information. 
