# Ng-alain Extension Pack

专注于 ng-alain 开发的扩展包。

# 扩展说明

## Angular推荐

- [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=angular.ng-template)
  - Angular 模板魔法：语法补全、错误检查、跳转等
- [TSLint](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin)
  - TypeScript代码规范

## NG-ALAIN推荐

- [NG-ZORRO Snippets](https://marketplace.visualstudio.com/items?itemName=cipchk.ng-zorro-vscode)
  - ng-zorro-antd 代码片断，支持自动补全组件名、属性，支持悬停文档
- [NG-ALAIN Snippets](https://marketplace.visualstudio.com/items?itemName=cipchk.ng-alain-vscode)
  - NG-ALAIN 代码片断（包含 `@delon/*`）
- [Angular Schematics](https://marketplace.visualstudio.com/items?itemName=cyrilletuzi.angular-schematics)
  - Angular Cli 界面化，不需要再记住那么多指令，当然也支持 ng-alain 命令行
- [angular2-switcher](https://marketplace.visualstudio.com/items?itemName=infinity1207.angular2-switcher)
  - Angular 文件快速切换，例如（Window）：
    - 按 `alt+o` 快速切换 `.ts` 和 `.html`
    - 按 `alt+u` 快速切换 `.ts` 和 `.spec.ts`
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    - [Prettier](https://github.com/prettier/prettier) 代码格式化，ng-alain 内置[配置文件](https://github.com/ng-alain/ng-alain/blob/master/.prettierrc)
- [Move TS - Move TypeScript files and update relative imports](https://marketplace.visualstudio.com/items?itemName=stringham.move-ts)
  - 移动 TypeScript 文件时自动同步更新导入路径
- [Markdown Table Prettifier](https://marketplace.visualstudio.com/items?itemName=darkriszty.markdown-table-prettify)
  - 美化 Markdown 的 Table
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