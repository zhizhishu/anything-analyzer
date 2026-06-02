# Anything Analyzer v3.6.37

## 修复

- **Responses API 工具调用格式校验** — 避免缺少 call_id 的 function_call 继续进入工具执行轮次
  - 工具调用入站阶段直接拒绝缺失 call_id 的畸形响应
  - 新增回归测试覆盖 Responses API function_call 缺少调用 ID 的异常路径

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.37.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.37-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.37-x64.dmg |
| Linux | Anything-Analyzer-3.6.37.AppImage |
