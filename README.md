# PrettierLearn

+ 本地安装 Prettier
+ 创建一个空的配置文件，让编辑器和其他工具知道您正在使用 Prettier：
    + echo {}> .prettierrc.json
+ 创建一个.prettierignore文件，让 Prettier CLI 和编辑器知道哪些文件不要格式化
    + echo {}> .prettierignore
+ npx prettier --write .
    + npx附带npm并允许您运行本地安装的工具
    + 会将整个项目里除了ignore文件忽略的之外的地方的代码整个格式化
+ prettier --write src/
    + 格式化某个目录
+ prettier --write src/test.js
    + 格式化某个文件
+ npx prettier --check .
    + 检查文件是否已格式化
通过编辑器运行prettier
