# MU-ty's Blog

简体中文文档站点，使用 MkDocs + Material 主题构建。

**快速开始**
- **前置条件**：已安装 `python`（建议 3.8+）和 `pip`。
- **安装依赖**：
  ```bash
  pip install mkdocs mkdocs-material pymdown-extensions
  ```
- **本地预览**：
  ```bash
  mkdocs serve
  # 打开浏览器访问 http://127.0.0.1:8000
  ```
- **打包构建静态站点**：
  ```bash
  mkdocs build
  # 产物位于 site/ 目录
  ```

**仓库结构（简要）**
- `mkdocs.yml`：站点配置与导航（nav）。
- `docs/`：站点源码（Markdown 文件、图片、子目录）。
- `README`：简短说明（保留），`README.md`：本文件。

**添加/更新页面**
- 在 `docs/` 下添加或编辑 `.md` 文件。
- 更新 `mkdocs.yml` 中的 `nav` 字段以包含新页面的路径（区分大小写，注意子目录）。

**常见问题**
- 导航条显示“not found”错误：检查 `mkdocs.yml` 中 `nav` 条目路径与 `docs/` 中的实际文件名是否完全一致（包括空格和标点）。
- 图片显示或链接错误：确保在 Markdown 中使用相对路径，且图片已提交到 `docs/` 下的对应位置。

**贡献**
- 使用分支和 Pull Request：修改内容后提交 PR，描述你的变更。

