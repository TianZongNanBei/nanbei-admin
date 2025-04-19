# Prettier 代码格式化配置说明

| 配置项                             | 默认值/推荐值 | 作用说明                                                     | 注意事项                      |
| ---------------------------------- | ------------- | ------------------------------------------------------------ | ----------------------------- |
| **`arrowParens`**                  | `"always"`    | 箭头函数参数始终加括号<br>（例：`(a) => {}` 而非 `a => {}`） | 避免单参数场景的歧义          |
| **`bracketSameLine`**              | `true`        | HTML/JSX 标签的闭合 `>` 放在最后一行末尾                     | 改善多属性标签的可读性        |
| **`objectWrap`**                   | `"preserve"`  | 对象换行时保持原格式（不强制自动折行）                       | 适合手动优化长对象结构        |
| **`bracketSpacing`**               | `true`        | 对象大括号内保留空格<br>（例：`{ a: 1 }` 而非 `{a:1}`）      | 与 Airbnb 风格一致            |
| **`semi`**                         | `false`       | 不自动添加行尾分号                                           | 需与 ESLint `semi` 规则配合   |
| **`experimentalOperatorPosition`** | `"end"`       | 换行的操作符（如 `+` `=`）放在行尾                           | 实验性特性，可能变动          |
| **`experimentalTernaries`**        | `false`       | 禁用三目运算符特殊换行规则                                   | 保持传统简洁格式              |
| **`singleQuote`**                  | `true`        | 使用单引号代替双引号                                         | 需与 ESLint `quotes` 规则同步 |
| **`jsxSingleQuote`**               | `false`       | JSX 中仍使用双引号                                           | 符合 JSX 社区惯例             |
| **`quoteProps`**                   | `"as-needed"` | 对象属性名仅在必要时加引号                                   | 减少冗余符号                  |
| **`trailingComma`**                | `"none"`      | 不添加行尾逗号                                               | 适合简约风格项目              |
| **`singleAttributePerLine`**       | `false`       | 允许多个属性在同一行（JSX）                                  | 避免过度换行                  |
| **`htmlWhitespaceSensitivity`**    | `"css"`       | HTML 空格处理规则与 CSS 一致                                 | 防止破坏布局敏感内容          |
| **`vueIndentScriptAndStyle`**      | `false`       | 不缩进 Vue 文件的 `<script>` 和 `<style>`                    | 与 Vue 官方风格一致           |
| **`proseWrap`**                    | `"preserve"`  | Markdown 文本不自动折行                                      | 保留段落自然换行              |
| **`printWidth`**                   | `120`         | 每行最大 120 字符后换行                                      | 适合小屏或严格风格            |
