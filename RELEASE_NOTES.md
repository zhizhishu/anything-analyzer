# Anything Analyzer v3.6.11

## 修复

- **macOS 发布工作流补齐双架构元数据与签名校验** — 修复发布流水线未在同一个 macOS 构建中产出 `x64/arm64` 更新元数据、且未显式校验签名 secrets 的问题
  - macOS job 改为单次执行 `electron-builder --mac --x64 --arm64`
  - 增加 `latest-mac.yml` 架构产物检查与 `codesign --verify` 校验
- **数据库迁移测试在原生绑定缺失时给出明确信号** — 修复 `better-sqlite3` 原生模块不可用时测试直接崩溃、清理阶段二次报错的问题
  - 使用真实 `:memory:` 探针判断 SQLite 绑定是否可用
  - 不可用时跳过迁移断言并保留单独环境信号测试

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.11.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.11-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.11-x64.dmg |
| Linux | Anything-Analyzer-3.6.11.AppImage |
