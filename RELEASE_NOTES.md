# Anything Analyzer v3.6.35

## 修复

- **流式文本增量格式校验** — 避免 SSE 文本增量不是字符串时被拼成 `[object Object]`
  - OpenAI Chat、Responses API、Anthropic/MiniMax 流式解析现在都会拒绝非字符串文本 delta
  - 新增回归测试覆盖三个流式接口的非字符串增量异常路径

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.35.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.35-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.35-x64.dmg |
| Linux | Anything-Analyzer-3.6.35.AppImage |
