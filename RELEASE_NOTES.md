---
author: yewwung
authorEmail: yewwung@163.com
lastModifiedBy: yewwung
lastModified: 2026-09-14
---

# Per Todo v1.0.11

发布日期：2026-09-14

- 修复两个已保存待办之间切换时误报“请先保存或关闭当前待办”。
- 未修改内容时可直接切换；真实修改未保存时仍会保护草稿。
- 同一待办重复点击时保留当前编辑器和草稿状态。
- 兼容空格或 `T` 分隔的本地日期时间，避免格式初始化制造虚假修改。
- 更新过程保留本机 `%LOCALAPPDATA%\per-todo\data.db` 待办数据。
- 提供 Windows x64 安装包、签名文件及跨平台 Release 产物。
