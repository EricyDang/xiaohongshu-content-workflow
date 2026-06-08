# Visual Prompt Templates

## Contents
- [Cover Image](#cover-image)
- [Carousel Page](#carousel-page)
- [Two-panel Comic](#two-panel-comic)
- [Single Poster](#single-poster)
- [Product Or Venue Post](#product-or-venue-post)
- [Short Video Storyboard](#short-video-storyboard)

## Cover Image

Use for the first page of a Xiaohongshu carousel.

```text
Create a vertical Xiaohongshu cover image, 1024x1536.

Topic:
{主题}

Target audience:
{目标人群}

Main title exact Chinese text:
"{主标题}"

Subtitle exact Chinese text:
"{副标题}"

Visual subject:
{视觉主体}

Scene:
{封面画面}

Style:
{风格方向}. Clean Xiaohongshu layout, strong title hierarchy, readable on phone, enough blank space, cohesive colors.

Avoid:
unauthorized logos, watermark, copied characters, private IP, cluttered layout, tiny unreadable text, exaggerated clickbait look.
```

## Carousel Page

Use one prompt per content page.

```text
Create one vertical Xiaohongshu carousel page, 1024x1536.

Page title exact Chinese text:
"{页面标题}"

Main content exact Chinese text:
"{页面正文}"

Visual subject:
{视觉主体}

Scene or layout:
{画面说明}

Style:
{风格方向}. Clear mobile typography, consistent with the rest of the carousel, strong visual order, not crowded.

Avoid:
unauthorized logos, watermark, copied characters, private IP, overly small text, random decorative elements.
```

## Two-panel Comic

Use only when the user wants a comic workflow. If no authorized character is provided, use a generic original person, object, or scene subject.

```text
Create one vertical Xiaohongshu two-panel comic image, 1024x1536.
Use two equal stacked panels with clear separation.

Visual subject:
{视觉主体}

Panel 1 exact Chinese text:
"{第一格文字}"

Panel 1 scene:
{第一格画面}

Panel 2 exact Chinese text:
"{第二格文字}"

Panel 2 scene:
{第二格画面}

Style:
original light comic style, clean lines, simple scene, readable Chinese text, consistent colors, mobile-first layout.

Avoid:
private IP, copied character designs, unauthorized logos, watermark, crowded background, tiny unreadable text.
```

## Single Poster

```text
Create a single Xiaohongshu poster, {尺寸}.

Main sentence exact Chinese text:
"{主文案}"

Supporting text exact Chinese text:
"{辅助文案}"

Visual subject:
{视觉主体}

Mood:
{情绪}

Style:
{风格方向}. Minimal, readable, high save value, enough blank space.

Avoid:
unauthorized logos, watermark, copied characters, private IP, excessive text, low contrast.
```

## Product Or Venue Post

```text
Create a Xiaohongshu image for a product, venue, or service recommendation, 1024x1536.

Subject:
{产品/地点/服务}

User scenario:
{使用场景}

Key details to show:
{细节}

Text exact Chinese:
"{页面文字}"

Style:
clean lifestyle, real-use feeling, bright but natural colors, mobile-readable text hierarchy.

Avoid:
fake logos, unrealistic claims, private user data, watermark, cluttered product placement.
```

## Short Video Storyboard

```text
Create a Xiaohongshu short video storyboard for {主题}.

Target audience:
{目标人群}

Video length:
{时长}

Output:
1. 0-3s hook shot
2. scene-by-scene visual plan
3. narration
4. on-screen captions
5. cover title
6. comment prompt

Style:
{风格方向}, clear rhythm, no over-explaining, strong first 3 seconds.
```
