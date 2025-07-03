# Custom Dark Theme for Trilium Notes

A polished and functional dark theme for Trilium Notes, designed for a clean and focused writing experience. This theme combines a comfortable dark mode with a colorful, hierarchical note tree to improve navigation and readability.

## Features

- **Comfortable Dark Mode**: A pleasant dark background that's easy on the eyes
- **Colored Note Tree**: The note tree on the left has colored borders, which helps to visually separate different levels of notes
- **Customized Headers**: Headers are styled with unique background colors to make them stand out
- **Improved Readability**: The theme includes many small tweaks to spacing, fonts, and colors to make your notes easier to read and write
- **Code-Friendly**: Includes syntax highlighting styles that are clear and easy to read
- **Smooth Transitions** - Hover effects and focus states now animate smoothly
- **Better Syntax Highlighting** - More comprehensive color scheme for code
- **Enhanced Tables** - Better styling with hover effects and improved borders
- **Improved Focus Indicators** - Better keyboard navigation visibility
- **Print Styles** - Theme adapts for printing
- **Version Header** - Professional documentation at the top

## **Major Improvements:**

1. **Better Organization** - Grouped related styles into logical sections with clear comments
2. **Reduced Redundancy** - Condensed the tree coloring code from ~60 lines to ~30 lines using CSS variables
3. **Enhanced Accessibility** - Improved text contrast and added better focus indicators
4. **Modern CSS** - Added CSS custom properties, transitions, and better selectors
5. **Performance** - More efficient selectors and reduced specificity conflicts

## **Visual Enhancements:**

- **Subtle Hover Effects** - Tree nodes slide slightly when hovered
- **Better Selection Colors** - More accessible selection highlighting
- **Enhanced Scrollbars** - Better styled scrollbars with hover effects
- **Improved Form Elements** - Better focus states for inputs

## Installation

You can install this theme in two ways: by importing the ZIP file (the easier method) or by manually creating a CSS note.

### Method 1: Import from ZIP File (Recommended)

1. **Download the Theme**: Go to the [Releases](https://github.com/ahmeddwalid/custom-trilium-dark-theme) page of this repository and download the latest `.zip` file.

2. **Open Trilium Notes**

3. **Import the File**: In the note tree on the left, right-click on any note (or the root note) and select **Import into note**.

4. **Choose the ZIP File**: Find and select the `.zip` file you just downloaded.

5. **Activate the Theme**:
   
   - Click on the Trilium menu icon (top-left) and go to **Options**
   - Select the **Appearance** tab
   - From the "Theme" dropdown menu, choose the new theme you just imported

### Method 2: Manually Create a CSS Note

1. **Copy the CSS Code**: Click [here](custom-dark-theme.css) to open the raw CSS file. Select all of the text (Ctrl+A or Cmd+A) and copy it (Ctrl+C or Cmd+C).

2. **Create a New Note in Trilium**:
   
   - Create a new note and give it a name, like "Custom Dark Theme"
   - In the "Note Info" panel on the right, change the **Type** from "Text" to **Code**
   - Set the **Mime type** to `text/css`

3. **Paste the Code**: Paste the CSS code you copied into the note's content area.

4. **Add the Theme Attribute**:
   
   - In the "Owned Attributes" section, add a new attribute with the name `#appTheme`
   - Give it a value that will be its name in the theme list, like "Custom Dark Theme"

5. **Activate the Theme**:
   
   - Go to **Options** > **Appearance**
   - Select your new theme from the dropdown list

## Credits

This theme was created by combining and modifying two excellent themes:

- **Base Theme**: https://github.com/SiriusXT/trilium-theme-blue
- **Tree Coloring**: https://github.com/perfectra1n/custom-trilium-themes

## Contributing

Feel free to open issues or submit pull requests if you have suggestions for improvements or find any bugs.

The enhanced-custom-dark-theme.css still needs some fixes

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Enjoy your new theme!**
