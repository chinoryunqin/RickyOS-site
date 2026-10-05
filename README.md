# RickyOS 网站

Ricky AI Studio 为 MindReset 小纸 Read Pico 打造的 RickyOS 官方品牌网站。
RickyOS 是第三方固件，并非 MindReset 官方固件。

访问：<https://chinoryunqin.github.io/RickyOS-site/>。

## 当前状态

正式版 `1.6.5-rickyos-pico.12` 已发布。

- 网页安装：电脑 Chrome / Edge 连接设备，先保存并校验完整备份，再更新应用。
  目前支持已装有 CrossMux 或 RickyOS 的设备；原厂系统的首次安装还在验收，暂未开放。
- 设备在线更新：读取 [ota.json](./ota.json)，与网页发行目录 [releases.json](./releases.json)
  同源生成，版本、大小和 SHA-256 一致，不跳转或回退至其他品牌的固件。

本公开仓库只保存审核后的静态网站成品和正式固件镜像，源项目另行维护；不包含设备固件源码、
开发固件、备份或私人照片。网页中的界面图片是原生模拟器截图，并已注明。

## 发布与许可

GitHub Pages 仅发布 `gh-pages` 分支的根目录。网站更新须保持完整资源包，
不得单独上传 HTML，也不得将固件开发候选混入网站。
公开网站内容包括 HTML、浏览器 JS/CSS、品牌展示素材及许可文本。

品牌 logo 和原创展示素材属于 Ricky AI Studio；第三方组件许可见
[开源与隐私说明](./licenses.html)及 [许可原文](./third-party-licenses.txt)。
