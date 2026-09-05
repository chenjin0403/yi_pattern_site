网站 assets 素材目录

此文件夹需要与 index.html 放在同一级。上传网站时，请整体上传 assets 文件夹，不要改变内部文件夹名称。

目录说明：

- pattern-data.js：彝族元素纹样库数据与图片路径
- traditional-data.js：中华传统纹样专题数据与图片路径
- repair-vessel.jpg：纹样修复模块使用的原始/修复对照素材
- patterns：彝族元素纹样图片（61 张）
- traditional：中华传统纹样资料图片（65 张）

正确的网站目录结构：

网站根目录/
├─ index.html
└─ assets/
   ├─ pattern-data.js
   ├─ traditional-data.js
   ├─ repair-vessel.jpg
   ├─ patterns/
   └─ traditional/

图片文件名采用原始哈希名，数据文件中的路径已经与目录对应。替换图片时，请同步修改对应 JS 数据文件中的 image 或 images 字段。
