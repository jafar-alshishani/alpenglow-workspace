<p align="center">
  <img src="images/icon.png" width="120" alt="Alpenglow Workspace icon">
</p>

<p align="center">
  A flat, warm charcoal dark theme for Visual Studio Code, inspired by the timeless simplicity of Afterglow.
</p>

<p align="center">
  Alpenglow Workspace brings a consistent, distraction-free appearance to the entire VS Code workbench, including the editor, Explorer, tabs, panels, terminal, menus, and notifications.
</p>


## Preview

![Alpenglow Workspace](screenshots/alpenglow-workspace.png)

*Alpenglow Workspace running with C# and JavaScript side by side.*

![Alpenglow Sunset](images/alpenglow-sunset.png)

*The soft sunset colors that inspired the theme.*


## Install from source

1. Clone the repository:
   ```bash
   git clone https://github.com/jafar-alshishani/alpenglow-workspace.git
   ```
2. Open the project folder in VS Code.
3. Open the integrated terminal.
4. Install the packaging tool:
   ```bash
   npm install -g @vscode/vsce
   ```
5. Package the extension:
   ```bash
   vsce package
   ```
6. In VS Code, select **Extensions → ... → Install from VSIX...** and choose the generated `.vsix` file.

## Recommended Font

Roboto Mono is recommended for the best visual experience with Alpenglow Workspace.

Suggested VS Code settings:

```json
{
  "editor.fontFamily": "'Roboto Mono', Consolas, 'Courier New', monospace",
  "editor.fontSize": 14,
  "editor.fontLigatures": false
}
```

## Palette

| Role | Color Preview | Hex Code |
|:---|:---:|:---:|
| Workspace background | <img src="images/swatches/2E2E2E.png" width="48"> | `#2E2E2E` |
| Secondary surfaces | <img src="images/swatches/262626.png" width="48"> | `#262626` |
| Foreground | <img src="images/swatches/D6D6D6.png" width="48"> | `#D6D6D6` |
| Orange accent | <img src="images/swatches/CC7833.png" width="48"> | `#CC7833` |
| Function highlight | <img src="images/swatches/FFC66D.png" width="48"> | `#FFC66D` |
| Green | <img src="images/swatches/B4C973.png" width="48"> | `#B4C973` |
| Blue | <img src="images/swatches/6C99BB.png" width="48"> | `#6C99BB` |
| Selection | <img src="images/swatches/5A647E.png" width="48"> | `#5A647E` |

## Development

The theme uses VS Code's native `colors` and `tokenColors` contribution points.

## Acknowledgements

[Afterglow](https://github.com/YabataDesign/afterglow-theme) by [José María Clemente (@YabataDesign)](https://github.com/YabataDesign) was my personal theme in Sublime Text for many years. Its flat design, warm colors, and understated elegance have always made it special to me.

Alpenglow Workspace also draws inspiration from the [Alpenglow color palette](https://github.com/AlpenglowTheme/alpenglow-theme), particularly the colors featured in its `Alpenglow-markdown.tmTheme` color scheme. The palette was adapted and mapped independently to Visual Studio Code's workbench and syntax highlighting system.

My sincere thanks to the creators of both projects for their original work and inspiration.

## License

This project is licensed under the [MIT License](LICENSE).

