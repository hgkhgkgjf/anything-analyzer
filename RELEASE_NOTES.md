# Anything Analyzer v3.6.23

## 修复

- **OpenAI 非流式响应格式校验** — 修复 Chat Completions 返回异常 JSON 但缺少 `choices` 时被误判为空成功结果的问题
  - 非流式 OpenAI 响应现在会和工具调用路径一致校验 `choices`
  - 缺少 `choices` 时返回明确的 `LLM 响应格式异常` 错误

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.23.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.23-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.23-x64.dmg |
| Linux | Anything-Analyzer-3.6.23.AppImage |
