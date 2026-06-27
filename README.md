# 前端打磨 Pass

打磨前端界面，并验证响应式布局、状态、可访问性和视觉质量。

这是一个独立发布的中文 Codex skill。整个仓库本身就是一个 skill 目录，可以直接复制到 Codex 的 skills 目录中使用。

## 安装

PowerShell:

```powershell
.\install.ps1
```

macOS/Linux:

```bash
./install.sh
```

默认安装到 ~/.codex/skills/frontend-polish-pass。如需安装到其他 Codex home，请设置 CODEX_HOME。

## 使用

```text
使用 $(System.Collections.Hashtable.name) 处理这个任务。
```

## 文件

- SKILL.md：skill 的触发描述和执行说明。
- gents/openai.yaml：Codex UI 展示元数据。

## License

MIT.