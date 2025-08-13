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

## Conversion Plan

This repository is currently being converted to a VS Code theme. The plan is as follows:

1.  **Update `README.md`**: Modify the `README.md` to state that this is a VS Code theme based on the original Atom theme and outline the conversion plan.
2.  **Create the VS Code theme file**: Create a new file, `themes/monokai-zebra-stripes-color-theme.json`, which is the standard format for VS Code themes.
3.  **Translate the theme colors and styles**: Convert the colors from `styles/colors.less` and the syntax rules from `index.less` and `styles/syntax-variables.less` into the JSON format required for a VS Code theme. This will involve mapping the Atom-specific syntax selectors to their VS Code equivalents.
4.  **Update `package.json`**: Modify the `package.json` to make it a valid VS Code theme package. This includes adding a `contributes` section to register the theme.
5.  **Clean up old files**: Once the conversion is complete, remove the now-obsolete Atom theme files (`index.less`, `styles/`).
