# README

[![Installs](https://img.shields.io/visual-studio-marketplace/i/jorgecortesdev.web-development-essentials-extension-pack)](https://marketplace.visualstudio.com/items?itemName=jorgecortesdev.web-development-essentials-extension-pack)
[![Visit Website](https://img.shields.io/badge/Visit-jorgecortes.dev-blue)](https://jorgecortes.dev?utm_source=vscode-marketplace&utm_medium=extension&utm_campaign=web-development-essentials-extension-pack&utm_content=badge)

A collection of extensions for web development in VS Code.

These are some of my favorite extensions for web development to make development easier and fun.

## Extensions included

- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) - Automatically rename paired HTML/XML tag.
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) - Launch a local development server with live reload feature for static & dynamic pages.
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) - Visual Studio Code plugin that autocompletes filenames.
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) - This plugin attempts to override user/workspace settings with settings found in `.editorconfig` files.
- [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) - This extension styles css/web colors found in your document.
- [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv) - VSCode `.env` syntax highlighting.
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - Prettier is an opinionated code formatter.
- [Readme Pattern](https://marketplace.visualstudio.com/items?itemName=thomascsd.vscode-readme-pattern) - Generates `README.md` files.
- [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore) - Assists you in working with `.gitignore` files.
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)-Supercharges the Git capabilities built into Visual Studio Code.
- [W3C Web Validator](https://marketplace.visualstudio.com/items?itemName=CelianRiboulet.webvalidator) - W3C Web Validator.
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) - A basic spell checker that works well with camelCase code.
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) - Autocomplete npm modules in import statements.
- [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) - Code snippets for JavaScript in ES6 syntax.
- [stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint) - A Visual Studio Code extension to lint CSS/SCSS/Less with stylelint.
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integrates ESLint JavaScript into VS Code.
- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) - Improve your code commenting by annotating with alert, informational, TODOs, and more!.
- [Material Theme Icons](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme-icons) - Material Theme Icons, the most epic icons theme for Visual Studio Code and Material Theme.
- [Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme) - The most epic theme now for Visual Studio Code.

## For more information

- [Github](https://github.com/jorgecortesdev/web-development-essentials-extension-pack)
- [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=jorgecortesdev.web-development-essentials-extension-pack)

## Contributing

Want to add your favorite extension to this pack or improve something? Follow these steps:

### Clone the Project

```bash
git clone https://github.com/jorgecortesdev/web-development-essentials-extension-pack.git
cd web-development-essentials-extension-pack
```

### Add Your Extension

Open the `package.json` file and add your extension's identifier (e.g. `publisher.extension-id`) to the `extensionPack` array.

Example:

```json
"extensionPack": [
  "formulahendry.auto-rename-tag",
  "yourpublisher.your-extension-id"
]
```

### Generate a New `.vsix` File

Install the [VSCE tool](https://code.visualstudio.com/api/working-with-extensions/publishing-extension#getting-started-with-vsce):

```bash
npm install -g vsce
```

Then run:

```
vsce package
```

This will generate a `.vsix` file like `web-development-essentials-extension-pack-1.0.1.vsix`.

### Test the Extension Locally

#### Option 1: Using VS Code UI

1. Open VS Code.
2. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS).
3. Run: `Extensions: Install from VSIX...`
4. Choose the `.vsix` file you just created.

#### Option 2: Using the Command Line

From the project directory, run:

```bash
code --install-extension web-development-essentials-extension-pack-1.0.1.vsix
```

To uninstall the extension pack:

```bash
code --uninstall-extension web-development-essentials-extension-pack-1.0.1.vsix
```

### Submit a Pull Request

If you want to share your work with the rest of us and make this extension pack even greater, please submit a pull request.

Here’s how:

1. **Fork and Clone the Repository**

   - Click the **Fork** button at the top right of the [GitHub repo](https://github.com/jorgecortesdev/web-development-essentials-extension-pack).
   - Then clone your forked copy:

     ```bash
     git clone https://github.com/your-username/web-development-essentials-extension-pack.git
     cd web-development-essentials-extension-pack
     ```

2. **Create a New Branch**
   ```bash
   git checkout -b add-my-extension
   ```
3. **Make Your Changes**<br>
   Edit package.json to add your extension to the extensionPack array.
4. **Commit Your Changes**
   ```bash
   git commit -m "Add [extension-name] to the pack"
   ```
5. **Push to Your Fork**
   ```bash
   git push origin add-my-extension
   ```
6. **Open a Pull Request**<br>
   Go to your fork on GitHub and click **"Compare & pull request"**. Submit it against the `main` branch of this repository.
   Please provide a brief summary explaining why you're suggesting the extension and how it benefits the pack.

All contributions are welcome!

## Learn More

Check out my site for tutorials, and other open-source projects: [https://jorgecortes.dev](https://jorgecortes.dev?utm_source=vscode-marketplace&utm_medium=extension&utm_campaign=web-development-essentials-extension-pack&utm_content=readme-link) ✨

**Happy coding 😎**
