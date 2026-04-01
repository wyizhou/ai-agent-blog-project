# ai-agent-blog-project

## 项目目标

一个个人博客系统，基于本地http服务提供编辑和查看的，同时支持markdown渲染、文件上传、图片上传以及文本排版等编辑器，支持本地一键生成纯静态博客，一键上传并部署到公开到指定的github page仓库。

网站风格为Hacker news风格。


## 技术栈
1. 核心语言：使用Python3+的最新稳定版
2. 代码检查：使用Python 对应的Linter进行检查代码规范。

## Agents职责

1. Planner：规划项目人物，决定模块化开发以及开发顺序，同时生成任务清单，交由Generator实现。
2. Generator：根据Planner提供的任务清单，完成开发工作。
3. Evaluator：负责评估Generator输出的质量、包括语法检查，SEO评分以及代码质量等。



