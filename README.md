# 蛋白质预测项目完整交接

完整工程在本仓库的 **[Release 附件](https://github.com/xzt985/DSJ/releases/tag/handoff-20260928)**中，不在自动生成的 Source code ZIP 中。

## 下载和恢复

1. 打开最新 Release，下载8个 `project-handoff-20260928.zip.part01`～`part08` 分卷，
   以及 `parts-manifest.json`、`join-parts.ps1`、`JOIN.cmd`，放在同一个非C盘文件夹。
2. 双击 `JOIN.cmd`。脚本先校验各分卷，再合并成 `project-handoff-20260928.zip`，
   最后验证完整ZIP。请不要单独解压某个分卷。
3. 解压完整ZIP，得到 `dashuju` 文件夹。分卷、合并ZIP和解压内容同时保留时，
   建议预留至少 **70GB** 空间。
4. 阅读 `dashuju/新电脑先读.md` 和 `dashuju/new/HANDOFF_2026-09-28.md`。
5. 双击 `dashuju/打开工作终端.cmd`，准备便携Python环境，再按文档恢复任务。

第三折match在打包时已暂停：校准8239条全部完成，验证进度7024/20596。
恢复前确认原电脑没有同时运行同一个任务，不要互相覆盖断点。

包含代码、官方数据、训练模型、ESM/OOF缓存、预测、断点、旧作品和今日候选。
旧虚拟环境、临时缓存、离线安装包和重复验收副本已排除；自带可准备的Windows x64
CPU运行环境。它不会自动训练或上传比赛。

线上最高分v6为42.9143。9月27日v9单折融合40.5325。9月28日的v6主导融合候选
已生成，交接时线上成绩未知，不保证超过最高分。

完整ZIP大小：14684159239字节。

SHA256：`a057aab9d22adfd1862b8f2fd31537b6609a3a4b5b7d3b6a031dc07c14e205a4`

若仓库为私有，接手人需要先获得仓库访问权限才能下载。
