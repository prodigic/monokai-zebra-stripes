# Monokai Zebra Stripes for VS Code

This is a Visual Studio Code theme ported from the Atom theme [Monokai Zebra Stripes](https://atom.io/themes/monokai-zebra-stripes).

## Original Atom Theme

> A monokai syntax theme for Atom with background zebra stripes
>
> Plugin : https://atom.io/themes/monokai-zebra-stripes
> Repo : https://github.com/prodigic/monokai-zebra-stripes
>
> based on monokai (https://github.com/kevinsawicki/monokai)
>
> ![](https://raw.githubusercontent.com/prodigic/monokai-zebra-stripes/master/monokai-zs.png)

### A Note on Zebra Stripes

The original Atom theme features alternating background colors for odd and even lines, creating a "zebra stripe" effect. Unfortunately, the Visual Studio Code theming engine does not support this type of styling directly in a theme file. Therefore, this feature has been omitted from this port. This theme provides the Monokai color palette from the original, but without the zebra stripes.

## Installation

You can install this theme from the [VS Code Marketplace](https://marketplace.visualstudio.com/) (once published) or directly from the source.

### Installation from Source

To install this theme from source, you will need to clone the repository and package the theme yourself.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/prodigic/monokai-zebra-stripes.git
    cd monokai-zebra-stripes
    ```

2.  **Install dependencies and packaging tool:**
    Make sure you have [Node.js](https://nodejs.org/) and npm installed. Then, install `vsce`, the official tool for packaging VS Code extensions.
    ```bash
    npm install -g vsce
    ```

3.  **Package the theme:**
    ```bash
    vsce package
    ```
    This will create a `.vsix` file, such as `vscode-monokai-zebra-stripes-1.0.0.vsix`.

4.  **Install the theme in VS Code:**
    *   Open VS Code.
    *   Go to the **Extensions** view (`Ctrl+Shift+X`).
    *   Click the **...** menu in the top-right corner and select **Install from VSIX...**.
    *   Choose the `.vsix` file you just created.

5.  **Activate the theme:**
    *   Open the Command Palette (`Ctrl+Shift+P`).
    *   Run the `Preferences: Color Theme` command.
    *   Select "Monokai Zebra Stripes" from the list.
