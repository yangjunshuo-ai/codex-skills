# Codex Skills

这个仓库用于保存个人常用的 Codex skills。

## 当前包含

### paper-final-check-skill

用于检查论文、课程报告、设计报告或终稿材料，重点关注：

- 逻辑结构是否连贯
- 方法、实验和结论是否对应
- 公式编号和符号是否统一
- 图表引用是否准确
- 摘要、关键词和缩写是否规范
- 是否适合提交

### course-ppt-content-skill

用于根据论文、PDF、Word 或课程材料生成课程汇报内容，重点输出：

- 汇报主线
- PPT 每页标题和页面文字
- 图示建议
- 每页讲解重点
- 口头汇报稿
- 时间分配

## 使用方式

将 `.agents/skills` 目录放到 Codex 当前工作目录或用户目录下，然后在 Codex 中通过 skill 名称调用。

示例：

使用 paper-final-check-skill，检查当前目录下的报告 PDF，重点关注方法、实验和结论是否对应。

使用 course-ppt-content-skill，根据当前目录下的论文或报告，生成 5 分钟课程汇报 PPT 内容和口头稿。

## 注意事项

本仓库只保存 skill 文件，不包含课程报告、论文原文、实验数据或个人材料。