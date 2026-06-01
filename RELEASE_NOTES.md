# Anything Analyzer v3.6.20

## 修复

- **Anthropic 兼容流式错误显式报错** — 修复 MiniMax/Anthropic SSE 返回 `type: "error"` 时被忽略并产生空成功响应的问题
  - 流式错误事件会携带服务端错误信息抛出异常
  - 保留 malformed JSON 容错逻辑，避免影响正常流式增量解析

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.20.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.20-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.20-x64.dmg |
| Linux | Anything-Analyzer-3.6.20.AppImage |
