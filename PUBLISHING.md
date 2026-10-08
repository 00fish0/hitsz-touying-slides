# 发布建议

本模板已放在个人 GitHub 仓库，标题和简介注明“非官方”。代码和可编译示例不内置学校图形素材；README 中的两张效果预览含校徽字标，内容页使用通用山地湖泊示例。独立校徽文件与答辩稿留在毕设工作区，不放进公开仓库。MIT 许可证仅覆盖模板代码，不授予使用学校标识的权利。

暂不直接提交 Typst Universe，原因是：

1. [Typst Universe 的许可要求](https://github.com/typst/packages/blob/main/docs/licensing.md)规定，非开源的大学标识只有在权利人政策允许将其随包分发时才可打包。本模板没有找到这样的明确授权，所以代码包不含独立校徽文件；提交 Universe 前还应核对预览图中的标识能否用于包展示。
2. Universe 模板还需要符合[包清单和模板缩略图要求](https://github.com/typst/packages/blob/main/docs/manifest.md)，并使用不会暗示其为学校官方模板的名称。当前 GitHub 版不预设包名与仓库 URL。
3. 目前锁定的是已在本机验证的 Touying 0.7.4。Touying 的[现行版本](https://typst.app/universe/package/touying/)已到 0.8.0；提交 Universe 前宜针对新版本再做兼容性验证。

个人仓库更新前检查：

- `typst compile --root . example.typ example.pdf` 成功，逐页检查 PDF。
- 仓库仅包含本目录的模板代码、通用示例、配图、两张预览图、文档与许可证；检查 `assets/local/` 和个人答辩内容没有被提交。
- README 写明“非官方”，仓库描述避免让读者误认为是学校发布。
- 若日后取得学校对标识再分发的明确许可，再决定是否把校徽作为包素材纳入；否则继续由使用者自行提供。

计划提交 Typst Universe 时，再补 `typst.toml`、确认包名与作者信息、生成符合尺寸要求的缩略图，并按官方文档测试 `typst init` 流程。
