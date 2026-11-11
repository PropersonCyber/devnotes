# DevNotes · 开发手记

面向前端开发者的 Go 全栈技术博客项目。

当前交付为**项目设计起点**，包含产品 PRD 与首页 UI 效果图；尚无可运行的前后端业务，不需要安装依赖。

## 文件导航

- [产品设计与验收标准](prd.md)
- [首页效果图](docs/design/home.png)
- [视觉说明](docs/design/design-notes.md)
- [图片生成提示词](docs/design/home-prompt.txt)

## 目录规划

```text
apps/web/       阅读站与管理后台（前端待实现）
apps/server/    Go API（待实现）
sql/            数据库 SQL 迁移（待实现）
deploy/         部署与配置模板（待实现）
docs/design/    UI 效果图与设计说明
prd.md          产品范围、流程、数据、接口、验收标准
```

## 技术边界

前端建议 Next.js + TypeScript；Go 独立处理业务及权限；PostgreSQL 持久化；兼容 S3 的对象存储保存图片。Go 框架尚未指定，实施时与公司规范对齐。

先实施 PRD 的 M1 发布闭环；效果图展示 M2 完整首页，示例内容不是已发布文章。
