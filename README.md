# Ng-alain Extension Pack

专注于 ng-alain 开发的扩展包。

# 扩展说明

## Angular推荐

- [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=angular.ng-template)
  - Angular 模板魔法：语法补全、错误检查、跳转等
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  - ESLint代码规范

## NG-ALAIN推荐

- [NG-ZORRO Snippets](https://marketplace.visualstudio.com/items?itemName=cipchk.ng-zorro-vscode)
  - ng-zorro-antd 代码片断，支持自动补全组件名、属性，支持悬停文档
- [NG-ALAIN Snippets](https://marketplace.visualstudio.com/items?itemName=cipchk.ng-alain-vscode)
  - NG-ALAIN 代码片断（包含 `@delon/*`）
- [Angular Schematics](https://marketplace.visualstudio.com/items?itemName=cyrilletuzi.angular-schematics)
  - Angular Cli 界面化，不需要再记住那么多指令，当然也支持 ng-alain 命令行
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    - [Prettier](https://github.com/prettier/prettier) 代码格式化，ng-alain 内置[配置文件](https://github.com/ng-alain/ng-alain/blob/master/.prettierrc.js)
    - [stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint) Less样式格式化
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
  - 高亮 `TODO:`，推荐配置：
  ```json
  // settings.json
  "todo-tree.highlights.customHighlight": {
    "TODO:": {
      "foreground": "#fff",
      "background": "#ffbd2a",
      "iconColour": "#ffbd2a"
    },
    "FIXME:": {
      "foreground": "#fff",
      "background": "#f06292",
      "icon": "flame",
      "iconColour": "#f06292"
    }
  }
  ```