# Version 1.0 CHANGELOG

**CURRENT VERSION: ** *[v1.0.1](https://github.com/lhy0403/Qv2ray/releases/tag/v1.0.1)*

-------

**2019-07-14**: *v1.0.1* 修复一个拼写错误，该错误源自 [`0e9b90f`](https://github.com/lhy0403/Qv2ray/commit/0e9b90fb116b790156314a21a6ef1abc8d60fa63#diff-c3f4a6d32c4ab34067ba5fa647341c6aR12) 提交

**2019-07-11**: *v1.0.0* 发布第一个 RC 修改 MacOS 默认文件位置

**2019-07-09**: *v0.9.9b* 发布第一个公开测试版本 [v0.9.9b](https://github.com/lhy0403/Qv2ray/releases/tag/v0.9.9b)

**2019-07-08**: dev 分支的 [`v0.9.2a`](https://github.com/lhy0403/Qv2ray/releases/tag/v0.9.2a) 版本现在可以使用 GUI 修改配置，并做到动态重载配置（包括入站设置，日志，Mux选项）此版本完成了所有翻译工作，添加了双击配置列表即可启动对应配置的功能

**2019-07-07**: [Commit: [9b02ff](https://github.com/lhy0403/Qv2ray/commit/9b02ff9da8f96325bafa08958ba12c0dff66e715) ] 现在可以启动导入的配置文件 (包括导入现有文件和 `vmess://` 协议)，手动添加配置尚未实现，入站设置现在只能通过编辑配置文件完成 (Linux: `~/.qv2ray/Qv2ray.conf`, MacOS & Windows: 程序当前文件夹)，此版本部分翻译不完整

**2019-07-04**: 我们终于摆脱了对于 Python 的依赖，现在 Qv2ray 可以自行解析 `vmess://` 协议 [WIP]

**2019-07-03**: 主配置文件序列化/反序列化工作完成，并添加更多协议配置

**2019-07-02**: 等待上游依赖完成更新 [JSON 序列化 std::list](https://github.com/xyz347/x2struct/issues/11#issuecomment-507671091)

**2019-07-01**: 休息了几天，主要是去关注别的项目了。现在开始重构 v2ray 交互部分。

**2019-06-24**: Mac OS 测试构建完成，合并到开发分支 [dev](https://github.com/lhy0403/Qv2ray/tree/dev)

**2019-06-24**: 新建分支 MacOS-Build 开始测试 MacOS 构建，当前状态：![Build Status](https://travis-ci.com/lhy0403/Qv2ray.svg?branch=MacOS-Build)

**2019-06-23**: UI 结构已经固定，新建分支 translations 进行翻译 UI

**2019-06-23**: 基本 UI 完成，切换到 [dev](https://github.com/lhy0403/Qv2ray/tree/dev) 分支进行代码实现

**2019-06-22**: 当前开发分支[ui-implementation](https://github.com/lhy0403/Qv2ray/tree/ui-implementation) - 用于实现基本 UI
