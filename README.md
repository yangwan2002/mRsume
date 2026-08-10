# 万洋的个人简历

面向 AI 应用开发、Agent 工程与后端开发岗位的中文 LaTeX 简历。

## 在线查看

[下载最新 PDF](./output/pdf/万洋-简历-2026-照片版.pdf)

## 编辑位置

- `texs/sections.tex`：教育背景、实习经历、项目经历与专业技能
- `texs/header_with_photo.tex`：姓名、联系方式与照片
- `resume-zh_CN.tex`：主入口与全局样式配置

## 本地编译

需要安装 XeLaTeX。在项目根目录执行：

```powershell
xelatex -interaction=nonstopmode -halt-on-error resume-zh_CN.tex
xelatex -interaction=nonstopmode -halt-on-error resume-zh_CN.tex
```

生成的文件为 `resume-zh_CN.pdf`。

## 隐私说明

`project/` 中的本地工作资料、构建中间文件和渲染缓存已通过 `.gitignore` 排除，不会提交到公开仓库。

## 模板来源

本简历基于 [billryan/resume](https://github.com/billryan/resume) 及其中文模板修改，模板代码遵循仓库中的 MIT License；字体文件遵循各自许可证。
