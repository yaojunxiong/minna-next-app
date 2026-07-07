# Lesson 11 vertical storyboard v2

参考布局：`/assets/storyboards/lesson-11/vertical-v2/sb-11-001.png`。

本目录已经整理为同类竖版分镜资产：上半部为动漫场景，下半部为留白字幕/对白区域，方便后续在视频剪辑或前端页面中叠加台词。

## 资产路径

- `public/assets/storyboards/lesson-11/vertical-v2/sb-11-001.svg`：入口寒暄，建立场景与人物关系。
- `public/assets/storyboards/lesson-11/vertical-v2/sb-11-002.svg`：AI 老师讲解第 11 课数量词。
- `public/assets/storyboards/lesson-11/vertical-v2/sb-11-003.svg`：咖啡店点单，练习 `杯`。
- `public/assets/storyboards/lesson-11/vertical-v2/sb-11-004.svg`：课堂卡片，练习 `人/枚/時間`。
- `public/assets/storyboards/lesson-11/vertical-v2/sb-11-005.svg`：双人会话练习，配合手机互动。
- `public/assets/storyboards/lesson-11/vertical-v2/sb-11-006.svg`：课程完成与奖励反馈。

## 画面规范

- 画布：600 × 1000，竖版。
- 插画区：0 到 640px。
- 字幕/对白留白区：640 到 1000px。
- 风格：原创日系动漫分镜，线条清晰，色块柔和，保留纸质底纹。
- 文件格式：SVG，便于 Git 版本管理、前端直接引用、后续批量替换为 PNG。

## 前端引用示例

```tsx
const frames = [
  '/assets/storyboards/lesson-11/vertical-v2/sb-11-001.svg',
  '/assets/storyboards/lesson-11/vertical-v2/sb-11-002.svg',
  '/assets/storyboards/lesson-11/vertical-v2/sb-11-003.svg',
  '/assets/storyboards/lesson-11/vertical-v2/sb-11-004.svg',
  '/assets/storyboards/lesson-11/vertical-v2/sb-11-005.svg',
  '/assets/storyboards/lesson-11/vertical-v2/sb-11-006.svg',
]
```
