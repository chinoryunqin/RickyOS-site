# RickyOS 网站

Ricky AI Studio 为 MindReset 小纸 Read Pico 打造的 RickyOS 官方品牌网站。
RickyOS 是第三方固件，并非 MindReset 官方固件。

访问：<https://chinoryunqin.github.io/RickyOS-site/>。

## 当前状态

网站先上线，正式固件待发布。现阶段只展示系统界面和安全的安装流程演示，
不连接设备、不读取备份、不执行 Flash 写入。发行目录为空，没有固件可下载。

设备在线更新目录为 [ota.json](./ota.json)，与网页发行目录同源生成。
当前明确返回 RickyOS / Read Pico 正式频道的 `no_update`，不提供镜像，
也不跳转或回退至其他品牌的固件。

本公开仓库只保存审核后的静态网站成品，源项目另行维护；不包含设备固件源码、
开发固件、备份或私人照片。网页中的界面图片是原生模拟器截图，并已注明。

## 发布与许可

GitHub Pages 仅发布 `gh-pages` 分支的根目录。网站更新须保持完整资源包，
不得单独上传 HTML，也不得将固件开发候选混入当前预览站。
公开网站内容包括 HTML、浏览器 JS/CSS、品牌展示素材及许可文本。

品牌 logo 和原创展示素材属于 Ricky AI Studio；第三方组件许可见
[开源与隐私说明](./licenses.html)及 [许可原文](./third-party-licenses.txt)。
