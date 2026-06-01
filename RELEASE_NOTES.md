# Anything Analyzer v3.6.25

## 修复

- **Responses API 非流式文本解析** — 修复兼容服务只返回 `output` 消息内容、缺少顶层 `output_text` 时被误判为空成功结果的问题
  - 普通 Responses API 非流式请求现在会从 `output[].content[]` 提取 `output_text`
  - 工具调用轮次和普通请求共用同一段 Responses 文本提取逻辑

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.25.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.25-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.25-x64.dmg |
| Linux | Anything-Analyzer-3.6.25.AppImage |
