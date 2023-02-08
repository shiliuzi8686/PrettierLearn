# PrettierLearn

- 本地安装 Prettier
- 创建一个空的配置文件，让编辑器和其他工具知道您正在使用 Prettier：
  - echo {}> .prettierrc.json
- 创建一个.prettierignore 文件，让 Prettier CLI 和编辑器知道哪些文件不要格式化
  - echo {}> .prettierignore
- npx prettier --write .
  - npx 附带 npm 并允许您运行本地安装的工具
  - 会将整个项目里除了 ignore 文件忽略的之外的地方的代码整个格式化
- prettier --write src/
  - 格式化某个目录
- prettier --write src/test.js
  - 格式化某个文件
- npx prettier --check . + 检查文件是否已格式化通过编辑器运行 prettier
- js 文件保存后，自动给格式化
  - 1.vscode 设置-> settings-> text edit-> format on save 选中
  - 2.项目的根目录下创建 .prettierrc.js 文件，并进行配置
- 其它项目没有配置.prettier.js 文件，为啥保存也会自动格式化代码？？？
- 并且格式化的时候还会默认加上分号

* 是读取的 vscode 的 prettier 插件的配置文件吗？？？
