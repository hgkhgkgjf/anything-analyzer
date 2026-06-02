# Anything Analyzer v3.6.44

## 修复

- **LLM 工具调用参数校验** — OpenAI/Responses 工具参数必须是合法 JSON 对象
  - 工具调用 arguments 格式错误时直接在协议边界拒绝，不再包装成工具错误继续下一轮
  - 新增回归测试覆盖 OpenAI Chat Completions 与 Responses API 的坏 JSON 参数

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.44.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.44-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.44-x64.dmg |
| Linux | Anything-Analyzer-3.6.44.AppImage |
