# 词刻 · 专注背单词

一个纯前端、无需登录的浏览器背单词工具，使用轻量卡片帮助记忆，并根据答题情况自动安排后续复习。

## 在线体验

- 应用首页：<https://dky00.github.io/>
- 背单词页面：<https://dky00.github.io/vocab.html>

## 功能

- 15,633 个单词和 9 个学习词库
- 自动间隔复习与错词巩固
- 卡片回忆和拼写练习
- 学习趋势、日期范围和年度热力图
- 浅色与深色主题
- 学习数据导出与导入
- 桌面端和移动端适配

## 学习数据

学习进度、错词、收藏、统计和设置保存在当前浏览器的 `localStorage` 中，不会上传到 GitHub。

同一浏览器可以长期保留记录；换设备、换浏览器或清理网站数据前，请在设置中导出备份。

## 静态文件

```text
.
├── index.html
├── vocab.html
├── assets/
├── data/
├── vocab-favicon.svg
└── .nojekyll
```

`assets/` 包含页面运行所需的 JavaScript 和 CSS，`data/` 包含柯林斯与计算机英语词库，二者不能省略。

## 词库来源

- Collins Star Vocabulary
- ECDICT
- Computer English Learning

详细来源和授权信息见 `data/ATTRIBUTION.md` 与 `data/LICENSE-COLLINS.txt`。