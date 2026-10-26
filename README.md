# 视频分镜提示词

把粗略剧情、参考图和视觉要求整理成可执行的 AI 视频分镜与提示词。未指定平台时提供通用版本；指定平台时再按已确认的规则适配。

这个 skill 负责设计和撰写提示词，不会调用视频生成工具或提交生成任务。

## 安装

### 使用 Skillshare

```bash
skillshare install knockkeykey/video-shot-prompt -s video-shot-prompt
```

### 手动安装

从 GitHub 下载 ZIP 并解压，把包含 `SKILL.md` 的整个文件夹复制到你所用 AI 工具的 skills 目录。保留 `references/` 和 `agents/` 子目录；不同工具的 skills 目录位置可能不同。完成后按工具说明重新加载 skills。

## 文件

- `SKILL.md`：主要工作规则
- `references/prompt-structure.md`：提示词的输出结构与颗粒度
- `references/platform-adaptation.md`：指定视频平台时的适配规则
- `agents/openai.yaml`：显示名称与简短描述

## 许可证

本仓库采用 MIT License，详见 [`LICENSE`](LICENSE)。
