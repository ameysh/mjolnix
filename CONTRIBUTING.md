# Contributing to Mjolnix

Thank you for considering contributing to **Mjolnix**. Your help is greatly appreciated in making this theme better for all users.

## How to Contribute

### 1. Reporting Issues

If you find a bug, visual inconsistency, or have suggestions for improvements, please open an [issue](https://github.com/ameysh/mjolnix/issues) and include:

- A clear description of the issue
- Steps to reproduce (if applicable)
- Screenshots (if relevant)
- Your VSCode version and OS details

### 2. Requesting Features

If you have an idea for a new feature or theme enhancement, feel free to open a feature request as an issue. Please provide:

- A detailed description of the feature
- Potential use cases
- Mockups or examples (if possible)

### 3. Making Changes & Submitting Pull Requests

#### Prerequisites

- Ensure you have Node.js installed
- Install `vsce` (VSCode Extension Manager) by running:
  ```sh
  npm install -g @vscode/vsce
  ```
- Fork the repository and clone your fork
- Install dependencies
  ```sh
  npm install
  ```

#### Getting Started

The extension structure is straightforward:

- `package.json` - manifest file defining theme location and base theme specifications
- `themes/Mjolnix-color-theme.json` - the color theme definition file

To start development:

Press `F5` to open a new window with the extension loaded. Any changes you make to the theme will appear here.

You can also:

1. Test the theme:
   - Use `File > Preferences > Theme > Color Theme` or `Ctrl+K Ctrl+T`
   - Select "Mjolnix" from the theme picker
2. Inspect token colors:
   - Open a file with syntax highlighting
   - Use `Developer: Inspect Editor Tokens and Scopes` (Command Palette: `Ctrl+Shift+P` or `Cmd+Shift+P`)
     to examine token scopes

Things to keep in mind:

- Changes to the theme file are automatically applied in the Extension Development Host window
- Token colorization uses standard TextMate themes
- Colors are matched against one or more scopes

#### Making Changes

1. Create a new branch for your changes:
   ```sh
   git checkout -b feature-or-bugfix-name
   ```
2. Test your changes
3. Ensure your changes align with the theme's design principles
4. Commit your changes with a clear message
5. Push your branch and open a Pull Request (PR)

For more details on scopes and theme development, see the [VSCode Theme Documentation](https://code.visualstudio.com/api/extension-guides/color-theme).

### 4. Code Style & Guidelines

- Keep colors consistent with the existing theme aesthetic
- Follow the [VSCode Theme Documentation](https://code.visualstudio.com/api/extension-guides/color-theme)
- Ensure changes do not break existing functionality
- Keep PRs focused and concise

### 5. Community & Discussions

Feel free to join discussions in the issues section. Collaboration is encouraged!

---

Thank you for contributing to Mjolnix! Your support helps improve the experience for all users.
