# 文档

## 配置文档

### eslint

主要用例是检测代码

- [eslint](https://eslint.org/docs/user-guide/configuring)
- .eslintrc.cjs javascript 代码检测配置文件
- .eslintignore 忽略检测的文件

### prettier

主要用例是格式化代码

- [prettier](https://prettier.io/docs/en/options.html)
- .prettierrc.json prettier 配置文件
- .prettierignore 忽略格式化的文件
  通过 pnpm run lint 去检测语法，如果出现不规范格式,通过 pnpm run fix 修改

### stylelint

主要用例是检测样式

- [stylelint](https://stylelint.io/user-guide/configuration)
- .stylelintrc.json stylelint 配置文件
- .stylelintignore 忽略检测的文件

### commitlint

主要用例是检测 git 提交信息

- [commitlint](https://commitlint.js.org/#/reference-configuration)
- commitlint.config.cjs commitlint 配置文件
