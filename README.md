# Shortcuts Guard

![prettier code style](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)

English | [简体中文](./README-zh_CN.md)

The shortcuts of the OpenSumi IDE conflict with those of the Chrome, which makes the corresponding actions of OpenSumi IDE unable to take effect. Shortcuts Guard solve the most common used shortcuts conflict.

## Usage

- Click the Chrome Extension icon, and then there is a popup page.
- Add the URL in the popup page where you want to guard the OpenSumi IDE shortcuts.
- Click the keyboard icon in the upper right corner of the popup page to go to [the shortcut settings page](chrome://extensions/shortcuts), and then input the conflicting shortcuts.

## Guarded shortcuts

| **Windows Shortcut** | **Mac Shortcut** | **OpenSumi IDE Action** | **Chrome Action**                                           |
| :------------------- | :--------------- | :---------------------- | :---------------------------------------------------------- |
| Ctrl + n             | ⌘ + n            | New file                | Open a new window                                           |
| Ctrl + w             | ⌘ + w            | Close editor            | Close the current tab                                       |
| Ctrl + t             | ⌘ + t            | Show all Symbols        | Open a new tab, and jump to it                              |
| Ctrl + Shift + t     | ⌘ + Shift + t    | Reopen closed editor    | Reopen previously closed tabs in the order they were closed |
| Ctrl + Shift + w     | ⌘ + Shift + w    | Close the current tab   | Close the current window                                    |

> Reference [Chrome keyboard shortcuts](https://support.google.com/chrome/answer/157179?hl=en&co=GENIE.Platform%3DDesktop) and [VS Code keyboard shortcuts](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)

