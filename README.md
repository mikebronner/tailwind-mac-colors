# tailwind-colors
Color palette and swatches for macOS's color picker.

## Screenshots
<img width="229" alt="Screen Shot 2020-06-08 at 7 57 06 PM" src="https://user-images.githubusercontent.com/1791050/84101160-3bc90200-a9c2-11ea-9882-e0398297913e.png">

## Installation
1. Download the [latest release](https://github.com/GeneaLabs/tailwind-mac-colors/releases/latest) files and unzip them.
2. (Optional) If you currently have swatches in your color picker tool you want to save, create a backup copy of your local `NSColorPanelSwatches.plist` file using the following terminal command:
    ```sh
    mv ~/Library/Colors/NSColorPanelSwatches.plist ~/Library/Colors/NSColorPanelSwatches.plist.bak
    ```
3. Copy the two files you downloaded to: `~/Library/Colors/`.
4. Open the color picker tool in any Mac app, and select `Color Palettes` tab and select the `Tailwind` palette. You will also want to adjust the width and height of the color picker to show all swatches (recommended width is 10 swatches).
