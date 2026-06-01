# Anything Analyzer v3.6.24

## 修复

- **Responses API 工具调用失败状态** — 修复 `completeWithTools()` 使用 Responses API 时，`status: failed/incomplete` 被误报为缺少 `output` 的格式错误
  - 工具调用轮次现在会明确返回 `Responses API failed` 或 `Responses API incomplete`
  - 与普通 Responses API 非流式请求保持一致的错误语义

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.24.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.24-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.24-x64.dmg |
| Linux | Anything-Analyzer-3.6.24.AppImage |
