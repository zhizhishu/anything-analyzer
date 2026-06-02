# Anything Analyzer v3.6.26

## 修复

- **Responses API 非流式响应校验** — 修复兼容服务返回 completed 但缺少 `output_text` 和 `output` 时被误判为空成功结果的问题
  - 普通 Responses API 非流式请求现在会显式拒绝缺少输出字段的畸形响应
  - 新增回归测试覆盖 malformed Responses API completed payload

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.26.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.26-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.26-x64.dmg |
| Linux | Anything-Analyzer-3.6.26.AppImage |
