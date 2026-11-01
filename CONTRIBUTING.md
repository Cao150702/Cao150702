# CONTRIBUTING

本仓用于维护 GitHub 个人主页，重点展示兴趣、作品与持续投入；它不是岗位简历的替代品，两者请分别维护。更新文字时优先保证自然可读，避免堆砌术语。

## 维护范围与同步项

涉及以下主视觉资产时，需同时检查桌面与手机两种尺寸版本：

- `assets/header.svg` ↔ `assets/header-mobile.svg`
- `assets/monitor.svg` ↔ `assets/monitor-mobile.svg`
- `assets/station.svg` ↔ `assets/station-mobile.svg`
- `assets/pintu.svg` ↔ `assets/pintu-mobile.svg`

每次改文案请一并核对：README 中对应图片 `alt`、SVG `<title>`、项目跳转链接与描述是否一致。

## 视觉与动效约束

保持当前深色基调、强调色与圆角体系；无明确设计需求时，不替换图标、不重画拼途几何图形。保留现有动画，并保留“减少动态效果”规则（`@media (prefers-reduced-motion: reduce)`）。

## 对外表述边界

对外描述请先说明用途、本人工作和事实边界：明确区分示意图与实拍、历史联调与当前全面验收、个人贡献与团队成果。禁止发布工作单位内部代号、客户资料、私有源码、频点/位置信息或任何凭据。

## 提交前检查

发布前请在 GitHub 实际页面与手机尺寸下复核显示，遵守 GitHub Markdown/HTML 限制；不要添加本仓不存在的构建或测试命令。除非另有需求，本仓改动应保持最小范围。
