# Anything Analyzer v3.6.17

## 修复

- **OpenAI Chat 流式错误不再被吞掉** — 修复 Chat Completions SSE 返回 `error` payload 时被当成空成功响应的问题
  - 将流式 JSON 容错解析与 API 错误判断拆开，保留 malformed chunk 跳过逻辑
  - 增加错误 payload 回归测试，确保限流、鉴权等流式错误会抛给调用方

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.17.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.17-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.17-x64.dmg |
| Linux | Anything-Analyzer-3.6.17.AppImage |
