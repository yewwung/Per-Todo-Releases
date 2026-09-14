---
author: yewwung
authorEmail: yewwung@163.com
lastModifiedBy: yewwung
lastModified: 2026-09-14
---

# Per Todo v1.0.12

发布日期：2026-09-14

- 修复点击“已完成”时误报“请先保存或关闭当前待办”。
- 已保存或进入编辑但未修改时可直接打开已完成列表；真实未保存草稿仍受保护。
- 关闭已完成列表后恢复原待办编辑器，从已完成列表打开待办后也能正确返回。
- 修复 Windows 窗口折叠失败和重复错误提示，快速点击时不再堆叠提示。
- 后续桌面安装包与自动更新仅面向 Windows，不再构建 macOS、Linux 版本。
- 更新过程保留本机 `%LOCALAPPDATA%\per-todo\data.db` 待办数据。
- 提供 Windows x64 NSIS、MSI、便携包、签名文件及自动更新清单。
