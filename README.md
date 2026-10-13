# Web 编程课程实践 · 个人简历

深圳大学《Web 编程》课程作业仓库。页面是一个响应式个人简历，首页同时承载 JavaScript 练习
（Todo 列表）。

- 仓库地址：<https://github.com/kartwatt-cpu/web-week7>
- 直接本地运行：用浏览器打开 `index.html` 即可（所有资源都是相对路径，`file://` 也能跑）

## 目录结构

| 路径 | 说明 |
| --- | --- |
| `index.html` | 个人简历页面 + Todo 列表练习 |
| `style.css` | 全部样式：Grid 页面骨架 + Flex 局部排列 + Todo 组件 |
| `头像.jpg` | 页面头像资源 |
| `docs/` | 各周 AI 协作日志与实验课件 |
| `AGENTS.md` | 给 AI 编程助手的仓库说明 |

## 如何运行

不需要构建工具，也没有任何依赖：

```bash
# 方式一：直接双击 index.html，或用浏览器打开
# 方式二：起一个本地静态服务
python -m http.server 8000
# 然后访问 http://localhost:8000/
```

## Git 工作流

课程要求「分支开发 → 多次提交 → 合并回 main」，提交信息按 `feat:` / `refactor:` / `docs:` 前缀组织，
具体演进过程见下方提交历史。

## 相关记录

- `docs/第7周AI协作记录.docx` —— 本周实验记录模板
- `docs/第七周实验.pptx` —— 本周实验课件
- `docs/第6周AI协作记录.docx` —— 上周 AI 协作日志
