# Monokai Yusu79
![GitHub License](https://img.shields.io/github/license/yusu79/vscode-monokai-yusu79)
![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/yusu79.vscode-monokai-yusu79)
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/yusu79.vscode-monokai-yusu79)
![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/yusu79.vscode-monokai-yusu79)

Monokai Yusu79 is a custom theme based on the Monokai color scheme, designed for syntax highlighting in Visual Studio Code. This theme supports specific Markdown plugins to enhance the coding experience.

<!-- omit in toc -->
## Table of Contents
- [Installation](#installation)
- [Supported Syntax Highlighting](#supported-syntax-highlighting)

## Installation
To install the theme, search for "**Monokai Yusu79**" in the Visual Studio Code Marketplace.

<p align="center">
<img src="images/setup.png" width="70%"/>
</p>

## Supported Syntax Highlighting
The theme supports the following Markdown plugins:

| Plugin                                                                                   | Input Format                |
| ---------------------------------------------------------------------------------------- | --------------------------- |
| [markdown-it-info](https://www.npmjs.com/package/markdown-it-info)                       | `:::note info Title`      |
| [markdown-it-mojicolor](https://www.npmjs.com/package/markdown-it-mojicolor)             | `%Text%{Color}`                |

### markdown-it-info
This plugin generates an Info box when using the format `:::note info Title`. The theme customizes colors for each type of box.

![](./images/markdown-it-info_en.png)

### markdown-it-mojicolor
Using `%Text%{Yellow}` renders the text with the specified color, such as `<span style="color: Yellow;">Text</span>`. The theme highlights symbols in orange.

![](./images/markdown-it-mojicolor_en.png)
