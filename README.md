# minna-next-app

《みんなの日本語 初級》AI 互动学习系统的 Next.js 项目仓库。

## 已整理的动漫视频图片资产

本仓库已加入一套参考竖版分镜图布局制作的原创动漫风格 SVG 图片资产。

路径：

```text
public/assets/storyboards/lesson-11/vertical-v2/
├─ sb-11-001.svg
├─ sb-11-002.svg
├─ sb-11-003.svg
├─ sb-11-004.svg
├─ sb-11-005.svg
└─ sb-11-006.svg
```

配套说明：

```text
docs/anime-video/
├─ lesson-11-vertical-v2.md
└─ lesson-11-vertical-v2.manifest.json
```

## 画面规范

- 竖版画布：600 × 1000。
- 上半部：动漫化课程场景。
- 下半部：纸质留白区，用于后期叠加旁白、台词或字幕。
- 文件格式：SVG，适合 Git 版本管理，也可以在前端中直接以 `/assets/storyboards/...` 路径引用。

## 前端引用示例

```tsx
const frame = '/assets/storyboards/lesson-11/vertical-v2/sb-11-001.svg'
```
