# onedarkpro-rust README

## Introduction

This theme has been modified based on [One Dark Pro](https://github.com/Binaryify/OneDark-Pro) to make it more compatible with Rust.

I just use vscode command: `>Developer: Generate Color Theme From Current Settings` to make a json copy and modify this file.

## Effect
The brackets are not rendered correctly in CodeSnap and other is correct. You can download the theme plugin to exprirence it by youself.

![attribute](/imgs/attribute.png)
![attribute](/imgs/const-namespce.png)
![attribute](/imgs/macro.png)
![attribute](/imgs/struct-enum.png)

## Where did you find the color scheme?

I found a useful website [coolors.co](https://coolors.co/), there are many palettes you can try.

## How did I achieve it?

Almost every programming language have a .tmLanguage.json file to describe how to analyze its tokens. The `"name"` in `/syntax/rust.tmLanguage.json` is the `"scope"` in `/themes/OneDarkPro-Rust.json`, then you can provide some settings to describe how to render the `"scope"` in editor.

Here is the link to rust.tmLanguage.json

[vscode/extensions/rust/syntaxes/rust.tmLanguage.json at main · microsoft/vscode (github.com)](https://github.com/microsoft/vscode/blob/main/extensions/rust/syntaxes/rust.tmLanguage.json)

In every theme.json in `/themes/...`, I add line 2740 - 3151 to it.