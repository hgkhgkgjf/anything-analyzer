# Anything Analyzer v3.6.31

## 修复

- **Responses API 非流式空文本诊断** — 避免 `completed` 响应缺少 `output_text` 文本时被误判为空成功结果
  - 非流式 Responses 响应现在要求顶层 `output_text` 或 `output[].content[]` 至少提取到一个文本块
  - 工具调用最终文本轮次复用同一校验，避免无文本结果静默通过

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.31.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.31-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.31-x64.dmg |
| Linux | Anything-Analyzer-3.6.31.AppImage |
