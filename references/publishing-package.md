# Publishing Package

## Contents
- [Quick Input Checklist](#quick-input-checklist)
- [Pain Point Extraction](#pain-point-extraction)
- [Deliverable Structure](#deliverable-structure)
- [Page Structure](#page-structure)
- [Markdown Sections](#markdown-sections)
- [Xiaohongshu Copy](#xiaohongshu-copy)
- [Quality Checks](#quality-checks)
- [File Naming](#file-naming)

## Quick Input Checklist
- 内容类型：图文轮播 / 情绪故事 / 两格漫画 / 单图海报 / 产品种草 / 教程清单 / 视频脚本 / 互动运营
- 主题：用户给定主题
- 目标人群：年龄、身份、场景、需求
- 内容目标：涨粉 / 收藏 / 转化 / 互动 / 复盘
- 图片数量：1张 / 6张 / 8张 / 10张
- 文字风格：正常口语 / 治愈短句 / 轻松吐槽 / 稍微扎心
- 是否带字：AI直接带字 / 无字图后期加字
- 输出尺寸：1024x1536 或 1024x1024

## Pain Point Extraction
Prompt pattern:

```text
围绕主题【{主题}】和目标人群【{目标人群}】，提炼10个真实痛点、需求或使用场景。
要求：具体、像真人会说的话、不空泛、不营销腔、每条20字以内、适合小红书图文表达。
```

Good outputs:

```text
买之前不知道怎么选
看了很多攻略还是很乱
第一次用容易踩坑
预算有限但想要质感
收藏了很多但没行动
别人说好用，我不知道适不适合我
```

## Deliverable Structure

```text
选题文件夹/
├─ 选题名-小红书发布包.md
├─ assets/          # 可选：参考图、原始素材、无字底图
└─ output/          # 可选：最终图片或视频
   ├─ 00-首页图.png
   ├─ 01-页面标题.png
   ├─ 02-页面标题.png
   └─ ...
```

## Page Structure
Default carousel:

```text
00 首页图：主题封面，一眼说明内容
01 主题钩子：为什么要看
02-04 具体痛点、需求或误区
05-07 方法、故事推进或对比
08-10 案例、步骤、清单或验证
最后一页：总结、收藏点、评论引导
```

Two-panel comic page:

```text
上格：现实处境
下格：反应、补刀、转折、方法或安慰
```

Video:

```text
镜头1：3秒钩子
镜头2-4：核心内容
镜头5：结论
镜头6：评论互动
```

## Markdown Sections
Use this order for a full publishing pack:

```text
## 选题
## 目标人群
## 内容目标
## 发布标题
## 备选标题
## 首页图脚本
## 分页脚本或视频脚本
## 小红书正文
## 评论区引导
## 话题标签
## 统一视觉规范
## 基础绘图提示词模板
## 每页完整绘图提示词
## 发布前质检清单
## 可复用内容公式
```

## Xiaohongshu Copy
Title options:

```text
新手第一次做{主题}，先看这一篇
我把{主题}踩过的坑整理好了
{目标人群}真的需要这份清单
别急着买，先确认这几点
```

Body:

```text
这篇整理给和我一样刚开始研究{主题}的人。

一开始我也以为只要照着别人推荐选就行，
后来发现真正容易踩坑的地方，
其实都藏在细节里。

这篇先把判断方法、常见误区和适合人群写清楚。
收藏起来，下次需要的时候可以直接对照。
```

Comment prompt:

```text
你现在最想解决的是哪一步？
```

Hashtags:

```text
#小红书运营 #内容创作 #新手攻略 #干货整理 #避坑指南 #实用清单
```

## Quality Checks
- Topic is clear at first glance.
- Cover explains the benefit or emotional hook.
- Page order has logic, not random fragments.
- Each page is readable on mobile.
- Words sound human and specific.
- Images use consistent dimensions and visual direction.
- No private IP, personal data, unauthorized logos, or watermarks.
- Claims are not exaggerated.

## File Naming
Use descriptive names such as:

```text
00-首页图.png
01-主题钩子.png
02-具体痛点.png
03-避坑重点.png
04-方法步骤.png
05-案例说明.png
06-总结收藏.png
```
