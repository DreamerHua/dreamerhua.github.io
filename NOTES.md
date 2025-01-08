# 网站维护笔记

## 常用操作流程

1. 更新作品信息：修改`_pages/about.md`中的**Research**部分


## 版本更新记录

| 版本名称 | 主要更新点 | Tag名称 |
|---------|------------|---------|
| v1.0.0  | 1. 收敛所有页面内容至About me页面，避免维护多个Tab<br> 2. 按照Research, Teaching Experience, Selected Honors & Awards, Miscellaneous分区维护内容<br> 3. Research按照Journal Publications, Peer-Reviewed Conference Proceedings, Work in Progress分别维护 | [Release_version1.0](https://github.com/dreamerhua/dreamerhua.github.io/releases/tag/Release_version1.0)


## 常用修改位置

### 1. 基础信息修改
- 网站配置：`_config.yml`
  - 网站名称：1 行，修改后会影响网站在浏览器Tab中的名称
  - 个人信息：13-28 行
  - 社交媒体链接：34-75 行

### 2. 新增静态资源
- 新增图片：`assets/images/` 目录
- 新增文档：`files/` 目录

### 3. 内容管理
- 博客文章：`_posts/` 目录
  - 格式：`YYYY-MM-DD-title.md`
- 个人页面：`_pages/` 目录
- 出版物：`_publications/` 目录
- 演讲：`_talks/` 目录
- 作品集：`_portfolio/` 目录
- 教学：`_teaching/` 目录

### 4. 样式修改
- 主题样式：`_sass/` 目录
- 页面布局：`_layouts/` 目录
- 页面组件：`_includes/` 目录

