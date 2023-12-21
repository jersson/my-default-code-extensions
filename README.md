# my-default-code-extensions

- [Recommended extensions](#recommended-extensions)
  1.  [Material Icon Theme](#1-material-icon-theme)
  2.  [GitLens — Git supercharged](#2-gitlens--git-supercharged)
  3.  [Live Server](#3-live-server)
  4.  [Docker](#4-docker)
  5.  [Prettier Formatter for Visual Studio Code](#5-prettier-formatter-for-visual-studio-code)
  6.  [Todo Tree](#6-todo-tree)
  7.  [Markdown All in One](#7-markdown-all-in-one)
- [How to use it](#how-to-use-it)

## Recommended extensions
### 1. Material Icon Theme
A really Visual Studio explorer Theme to improve the icons and folders look & feel, more information in this [link](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

![](https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/main/images/commandPalette.png)

### 2. GitLens — Git supercharged
Improved visual toolkit to handle git features, like file history or something better, in this [link](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

![](https://raw.githubusercontent.com/eamodio/vscode-gitlens/master/images/docs/gitlens-preview.gif)

### 3. Live Server
I'm sure this one doesn't need any other explanation, more information [here](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

![](https://github.com/ritwickdey/vscode-live-server/raw/master/images/Screenshot/vscode-live-server-animated-demo.gif)

### 4. Docker

I'm sure this one doesn't need any other explanation either, more information [here](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

![](https://github.com/microsoft/vscode-docker/raw/HEAD/resources/readme/overview.gif)

### 5. Prettier Formatter for Visual Studio Code
Interesting formatter for variety of programming languages, more information in this [link](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)


### 6. Todo Tree
In case you need to see how many `TODO` statements have in your code, link [here](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

![](https://raw.githubusercontent.com/Gruntfuggly/todo-tree/master/resources/screenshot.png)

### 7. Markdown All in One
To improve the markdown default support, more information in this [link](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

![](https://github.com/yzhang-gh/vscode-markdown/raw/master/images/gifs/toggle-bold.gif)

## How to use it

You can clone this repo, open it and accept the default intstallation process, or just copy the [extensions.json](.vscode/extensions.json) content:

```javascript
  {
    "recommendations": [
      "Gruntfuggly.todo-tree", 
      "esbenp.prettier-vscode",
      "ritwickdey.LiveServer", 
      "eamodio.gitlens", 
      "ms-azuretools.vscode-docker", 
      "yzhang.markdown-all-in-one",
      "pkief.material-icon-theme"
    ]
  }
```
