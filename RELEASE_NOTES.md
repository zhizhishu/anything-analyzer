# Anything Analyzer v3.6.43

## 修复

- **Responses API 工具调用回填** — 使用协议字段 call_id 回传 function_call_output
  - 工具调用结果回填时不再误用 function_call.id 作为 call_id
  - 新增回归测试覆盖 function_call.id 与 call_id 不一致的路径

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.43.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.43-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.43-x64.dmg |
| Linux | Anything-Analyzer-3.6.43.AppImage |
