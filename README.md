# cpa-usage-keeper-compat

[CPA Usage Keeper](https://github.com/Willxup/cpa-usage-keeper) 的 Linux amd64 兼容构建。

上游 v2.0.1 起的官方 Linux amd64 二进制要求 x86-64-v3（AVX2），在未开放 AVX2 的 VPS 上会因 `CPU ISA level is lower than required` 无法启动。本仓库每天检查上游最新正式版，从源码按基础 x86-64 编译后发布到 Releases，包结构与官方一致，可直接替换。

也可在 Actions 中手动运行 `Build compatible release`，指定上游版本号。
