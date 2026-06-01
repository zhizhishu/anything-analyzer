# Anything Analyzer v3.6.22

## 修复

- **LLM 限流重试可立即取消** — 修复 LLM 返回 429 后等待 `retry-after` 期间取消不生效的问题
  - 重试等待现在会响应 `AbortSignal`，取消分析时不会继续卡在限流等待中
  - Responses API 非流式 `status: "failed"` 现在返回明确的 `Responses API failed: ...` 错误

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.22.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.22-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.22-x64.dmg |
| Linux | Anything-Analyzer-3.6.22.AppImage |
