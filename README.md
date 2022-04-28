# eslint-prettier

Eslint+Prettier+husky+lint-staged

## 分为代码格式规范 和 代码提交规范

- 代码格式规范： eslint+prettier
  - elint: 代码风格
  - prettier: 修复eslint

- 代码提交规范： 使用gitHooks来防止一些不规范的代码提交到仓库中
 - 常见的Hooks
   - commit-msg 提交信息规范 git commit -m 'chore: /fix: /update: /',用来阻止提交
   - pre-commit 提交代码规范 使用husky来监测pre-commit钩子
   - husky 是一个gitHooks工具 作用：在代码提交前，允许我们做一些事情，防止不符合规范的代码被提交到仓库中

- lint-staged 自动修复暂存区的文件格式错误
