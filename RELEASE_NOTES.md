# Anything Analyzer v3.6.41

## 修复

- **Anthropic/MiniMax 工具参数校验** — 避免非对象 tool_use.input 被当作正常工具参数执行
  - 工具调用入站阶段直接拒绝字符串、数组等非对象 input
  - 新增回归测试覆盖 Anthropic 兼容工具调用参数类型异常路径

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.41.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.41-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.41-x64.dmg |
| Linux | Anything-Analyzer-3.6.41.AppImage |
