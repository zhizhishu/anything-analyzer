# Anything Analyzer v3.6.30

## 修复

- **Anthropic/MiniMax 非流式空文本诊断** — 避免兼容服务只返回工具块或非文本块时被误判为空成功结果
  - 非流式 Anthropic 兼容响应现在要求至少包含一个文本内容块
  - MiniMax 回归测试覆盖无 `text` 内容的响应，确保给出明确格式错误

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.30.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.30-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.30-x64.dmg |
| Linux | Anything-Analyzer-3.6.30.AppImage |
