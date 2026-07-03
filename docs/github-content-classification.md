# GitHub 内容分类体系

这套分类适合长期使用：以后无论是工作内容、个人作品、小游戏、PPT、网站、工具、学习笔记，都可以按同一套规则归档。

## 总体原则

- 一个可以独立运行、独立展示、独立部署的内容，优先单独建仓库。
- 一组同类型的小作品，可以先放在合集仓库里，成熟后再拆成独立仓库。
- 仓库名用英文，README 标题和介绍可以用中文。
- GitHub Topics 用英文标签，方便 GitHub 搜索和自动分类。
- 每个仓库至少保留 `README.md`，写清楚项目类型、用途、技术栈、在线地址和截图。

## 一级分类

| 大类 | 用途 | 推荐仓库前缀 | 示例 |
|---|---|---|---|
| 工作项目 | 工作流程、业务项目、客户方案、内部工具 | `work-` | `work-sales-dashboard` |
| 个人作品 | 代表你能力的作品集、设计、网站、创意项目 | `portfolio-` / `work-` | `portfolio-website` |
| 游戏项目 | H5 小游戏、Canvas 游戏、互动游戏、原型游戏 | `game-` | `game-dasheng-runner` |
| PPT / 演示 | 商业计划书、汇报、课程、路演、产品介绍 | `deck-` / `ppt-` | `deck-ai-business-plan` |
| 网站 / 页面 | 官网、落地页、活动页、展示页 | `site-` / `web-` | `site-personal-brand` |
| 工具应用 | 小工具、计算器、生成器、管理面板 | `tool-` / `app-` | `tool-prompt-manager` |
| AI 生成内容 | AI 图片、提示词、角色设定、素材包 | `ai-` | `ai-image-assets` |
| 设计资产 | Logo、图标、UI 素材、海报、视觉系统 | `design-` | `design-brand-kit` |
| 参考案例库 | 用于生成新内容前读取的案例、样板、灵感资料 | `ref-` | `ref-ppt-cases` |
| 学习笔记 | 教程、练习、课程笔记、代码实验 | `learn-` | `learn-javascript-canvas` |
| 模板库 | 可复用模板、脚手架、README 模板、PPT 模板 | `template-` | `template-html5-game` |
| 实验原型 | 不确定是否长期维护的想法、Demo、测试项目 | `lab-` | `lab-game-mechanics` |
| 归档内容 | 已完成但不再维护的旧项目 | `archive-` | `archive-old-landing-pages` |

## 二级分类建议

### 1. 工作项目 Work

适合放：
- 工作汇报
- 客户方案
- 数据看板
- 内部自动化工具
- 运营资料
- 流程文档

推荐 Topics：

```text
work
business
dashboard
workflow
automation
report
```

### 2. 个人作品 Portfolio

适合放：
- 个人作品集网站
- 精选项目展示
- 设计作品
- 商业案例
- 创意展示页

推荐 Topics：

```text
portfolio
personal-website
showcase
creative-work
case-study
```

### 3. 游戏项目 Games

适合放：
- HTML5 Canvas 游戏
- 跑酷游戏
- 休闲小游戏
- 微信/H5 可玩 Demo
- 游戏原型

推荐 Topics：

```text
html5-game
canvas-game
javascript-game
runner-game
mobile-game
web-game
game-demo
github-pages
```

你当前仓库 `kitchengoewang-v2` 最适合放在这一类：

```text
分类：游戏项目 / HTML5 Canvas 竖屏跑酷小游戏
推荐显示名：大圣跑酷
推荐仓库名：game-dasheng-runner
推荐部署：GitHub Pages
```

### 4. PPT / 演示 Decks

适合放：
- 商业计划书
- 项目路演
- 产品发布会
- 工作汇报
- 培训课程
- 投资人 Pitch Deck

推荐 Topics：

```text
presentation
pitch-deck
business-plan
slides
powerpoint
canva
figma
```

### 5. 网站 / 页面 Websites

适合放：
- 品牌官网
- 个人主页
- 产品落地页
- 活动页
- 展示页面

推荐 Topics：

```text
website
landing-page
static-site
html-css-javascript
github-pages
```

### 6. 工具应用 Tools

适合放：
- 计算器
- 表单工具
- 数据整理工具
- 提示词生成器
- 小型管理后台

推荐 Topics：

```text
tool
web-app
productivity
automation
utility
```

### 7. AI 生成内容 AI

适合放：
- AI 图片资产
- 提示词库
- 角色设定
- 图片生成方案
- 视频脚本
- 文案素材

推荐 Topics：

```text
ai-generated
prompt-engineering
image-generation
content-creation
assets
```

### 8. 设计资产 Design

适合放：
- Logo
- 图标
- 色彩系统
- UI 组件
- 品牌视觉
- 海报模板

推荐 Topics：

```text
design
brand-kit
ui-design
visual-assets
figma
canva
```

### 9. 参考案例库 Reference Library

适合放：
- 优秀 PPT 案例
- 网站设计参考
- 游戏玩法参考
- UI / 视觉风格样板
- 商业计划书结构案例
- README / 项目文档范例
- 交互体验和动效样板
- 行业案例、竞品分析、参考链接清单

推荐 Topics：

```text
reference
case-study
inspiration
examples
best-practices
design-reference
template-reference
```

推荐目录结构：

```text
reference-library/
  ppt-cases/
  website-cases/
  game-cases/
  design-styles/
  business-cases/
  readme-examples/
  interaction-patterns/
  links.md
```

使用规则：
- 这里放“给后续创作参考的案例”，不放最终交付作品。
- 每个案例最好写清楚来源、亮点、适合参考什么、可复用结构。
- 需要生成 PPT、网站、游戏、工具时，可以先读取对应参考库，再开始创作。

### 10. 学习笔记 Learning

适合放：
- 编程学习
- 课程练习
- 技术笔记
- 小案例
- 复盘文档

推荐 Topics：

```text
learning
notes
tutorial
practice
javascript
frontend
```

### 11. 模板库 Templates

适合放：
- HTML5 游戏模板
- PPT 模板
- README 模板
- 网站模板
- 项目初始化模板

推荐 Topics：

```text
template
starter
boilerplate
readme-template
slides-template
```

## 推荐仓库命名规则

统一使用：

```text
大类前缀-项目名称-版本或用途
```

示例：

```text
game-dasheng-runner
deck-restaurant-business-plan
site-personal-portfolio
tool-ppt-outline-generator
design-brand-assets
ref-ppt-cases
learn-canvas-game-dev
template-html5-runner-game
```

## 推荐 README 固定结构

每个仓库可以统一使用这个结构：

```markdown
# 项目名称

一句话介绍这个项目。

## 分类

- 大类：
- 子类：
- 技术栈：
- 状态：
- 在线地址：

## 预览

放截图或演示 GIF。

## 功能

- 功能 1
- 功能 2
- 功能 3

## 使用方法

说明如何打开、运行或部署。

## 更新记录

- 2026-07-03：初始化项目
```

## 你当前仓库的最佳分类

仓库：`13860909640wzh-prog/kitchengoewang-v2`

推荐分类：

```text
大类：游戏项目
子类：HTML5 Canvas 网页小游戏
游戏类型：竖屏跑酷 / 休闲动作
技术栈：HTML + CSS + JavaScript + Canvas
部署方式：GitHub Pages
适配方向：移动端竖屏优先
```

推荐 GitHub Description：

```text
大圣跑酷：一款基于 HTML5 Canvas 的竖屏移动端跑酷小游戏
```

推荐 GitHub Topics：

```text
html5-game
canvas-game
javascript-game
runner-game
mobile-game
web-game
github-pages
html
css
javascript
```

## 后续新增内容放哪里

| 新内容 | 应该放入 |
|---|---|
| 新做一个小游戏 | `Games / 游戏项目` |
| 新做一个 PPT | `Decks / PPT 演示` |
| 新做一个工作汇报 | `Work / 工作项目` 或 `Decks / PPT 演示` |
| 新做一个个人主页 | `Websites / 网站页面` |
| 新做一个工具网页 | `Tools / 工具应用` |
| 新生成一批 AI 图片 | `AI / AI 生成内容` 或 `Design / 设计资产` |
| 新做一个品牌 Logo | `Design / 设计资产` |
| 新收集一批参考案例 | `Reference Library / 参考案例库` |
| 新学一个技术案例 | `Learning / 学习笔记` |
| 新做一个可复用模板 | `Templates / 模板库` |
| 临时测试想法 | `Labs / 实验原型` |

## 最推荐的长期结构

如果你未来内容很多，建议账号首页做一个总索引仓库：

```text
13860909640wzh-prog/profile-home
```

里面放：

```text
README.md
categories/
  games.md
  decks.md
  work.md
  portfolio.md
  tools.md
  design.md
  references.md
  learning.md
```

这样你的 GitHub 就会像一个作品管理系统，而不是零散仓库列表。
