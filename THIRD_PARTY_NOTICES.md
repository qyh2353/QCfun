# 第三方许可与来源

QCfun 采用 GPL-3.0。项目此前基于 Predidit/Kazumi 2.3.8 的网页实现扩展，原项目与公开规则来源的许可及版权声明继续有效。

- 原项目：https://github.com/Predidit/Kazumi
- 公开规则：https://github.com/Predidit/KazumiRules
- 原有来源、第三方库及其许可证不因界面品牌调整而变更。

此文件保留必要的来源信息；产品界面统一使用 QCfun。
# 影视资料预览（2026-10-15）

独立快照位于 `public/data/cinema-preview.json`，不进入动漫规则注册表。中文别名仅用于界面展示，作品身份以来源 ID 为准。未匹配到明确条目的查询不会生成占位作品。

- **TVmaze**：电视剧、综艺、纪录片资料及图片地址来源于 https://www.tvmaze.com/api 。API 数据遵循 CC BY-SA，按相同许可提供这部分资料快照；评分标注为 TVmaze。图片依照其 API 文档进行链接与缓存。地区为来源明确的播出机构地区，不推断为制作地区。
- **Blender Open Movies**：作品资料与文件地址来自 https://video.blender.org/ 。当前仅收录官方开放电影频道且标记 Attribution 的作品，原片尾署名保留，具体许可与作者信息以作品原页面为准。本轮验证了文件片段读取，不宣称所有设备完整播放通过。
- **NASA**：科教影像资料来自 https://images-api.nasa.gov ，按 https://www.nasa.gov/nasa-brand-center/images-and-media/ 核验使用条件。本预览只展示资料并链接原页面，不将第三方素材视为统一获得授权。
- **IPTV-org database**：频道身份和分类资料来自 https://github.com/iptv-org/database 。不附带直播信号，不将目录资料许可解释为频道转播许可。



## Flutter Android 发布包

- Flutter/Dart：BSD 类许可证，详见 https://github.com/flutter/flutter/blob/stable/LICENSE 与各 SDK 声明。
- Supabase Flutter：MIT，详见 https://github.com/supabase/supabase-flutter 。
- AndroidX Media3：Apache-2.0；Node.js Mobile：其发行包附带的许可证。
- Noto / QCfunSans 字体：保留源码包 assets/fonts/OFL.txt，不因文件名调整而改变字体授权。
- 浏览器运行库、ONNX 模型、规则和元数据：分别保留对应的原作者、许可及来源说明。

完整随附声明与构建依赖位于每个版本对应源码包。应用许可不授予第三方影视、图片或文字内容的额外使用权。
