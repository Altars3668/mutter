# AltarsCN mutter 修改版

本仓库属于 [AltarsCN GRD 软件栈](https://github.com/Altars3668/altarscn-debs)，不是上游官方仓库。

- 目标系统：Ubuntu 26.04（resolute），amd64，GNOME 50。
- 下游打包基线：`50.1-0ubuntu2.4+altarscn3`。
- 源码模型：原版源码 + `debian/patches/series`；`dpkg-source --before-build .` 应用补丁。
- 来源及原版档案 SHA256：`SOURCE_PROVENANCE.json`。
- 源码 CI 会调用中央只读整栈构建；签名 APT 与 Release 仅由中央仓库发布。
- 安装、签名指纹、版本组合及回滚：[中央说明](https://github.com/Altars3668/altarscn-debs#安装签名-apt-源)。

首次公开导入为干净源码快照，保留原版权与许可证，不导出私有历史、运行凭据或构建产物。


不要把这些包安装到其他 Ubuntu / Debian 发行版。GPU 编码、物理屏隐私与多用户真机验收不能由普通 GitHub runner 替代。
