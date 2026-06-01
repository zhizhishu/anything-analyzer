# Anything Analyzer v3.6.12

## 修复

- **Responses API 流式失败事件不再被吞掉** — 修复 `response.failed` / `error` SSE 事件被 JSON 容错逻辑吞掉，导致上层误判为空成功响应的问题
  - 将 SSE JSON 解析容错和 API 失败事件处理分离
  - 增加流式失败事件回归测试，确保失败信息会向调用方抛出

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.12.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.12-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.12-x64.dmg |
| Linux | Anything-Analyzer-3.6.12.AppImage |
