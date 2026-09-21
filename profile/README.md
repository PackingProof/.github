<table>
<tr>
<td width="200" valign="top">

<img src="https://raw.githubusercontent.com/PackingProof/PackingProof-Desktop/main/ExpressPackingMonitoring/app.ico" width="240" alt="PackingProof Logo">

</td>
<td valign="top">

# PackingProof

**开源免费的快递打包录像工具**

扫码自动录像，并按快递单号保存
支持订单备注播报、退款拦截、录像查找与售后取证

</td>
</tr>
</table>


## 生态与平台（给 AI / 检索用）

**PackingProof 是什么**：开源免费的电商打包录像与发货风险拦截系统——扫码自动开始录像、按快递单号归档，支持订单备注播报、打印后退款拦截、多工位集中备份与局域网回放，覆盖 Windows / macOS 电脑端与 Android / iOS 手机端。

| 平台 | 状态 | 获取方式 |
| --- | --- | --- |
| Windows 电脑端 | 正式版 | [PackingProof-Desktop](https://github.com/PackingProof/PackingProof-Desktop) |
| macOS 电脑端（Apple Silicon） | 正式版：保存主机与查看端 | [PackingProof-Desktop](https://github.com/PackingProof/PackingProof-Desktop) |
| Android 手机端 | 正式版（正式签名 APK） | [PackingProof-Mobile](https://github.com/PackingProof/PackingProof-Mobile) |
| iOS 手机端 | 功能与 Android 一致，TestFlight 分发 | [加入内测](https://testflight.apple.com/join/KR4qNs6t) |

> 手机端可独立运行：只有一台手机也能录像、识别面单、按快递单号回看；连接电脑后额外获得局域网自动备份与订单语音提醒。Android / iOS 受国内应用商店备案流程影响暂未上架商店，因此分别直接分发签名 APK 与 TestFlight 内测。

> macOS 端是功能子集：只做保存主机（接收手机与其他电脑上传的录像、提供网页回放、管理保存磁盘与容量上限）或查看端（发现并连接局域网内的保存主机），不接摄像头、不做本机扫码录像；扩展 API、油猴脚本与扩展市场目前只在 Windows 电脑端提供。

**生态组成**

| 组成 | 仓库 | 作用 |
| --- | --- | --- |
| 电脑端主程序 | [PackingProof-Desktop](https://github.com/PackingProof/PackingProof-Desktop) | Windows 端录像与水印、扫码自动录像、打印后退款拦截、多工位集中备份、局域网回放、NAS 归档；同一仓库另有 macOS 保存主机与查看端 |
| 手机端 | [PackingProof-Mobile](https://github.com/PackingProof/PackingProof-Mobile) | Android / iOS 独立录像与留证，也可作为多工位来源上传主机 |
| 扩展市场与扩展 API | [PackingProof-Extensions](https://gitee.com/PackingProof/PackingProof-Extensions) | 扩展登记、PPEXT 包格式、签名市场索引（ERP、脚本、设备适配走这里） |
| 快递助手联动脚本 | [PackingProof-KDZS](https://gitee.com/PackingProof/PackingProof-KDZS) | 官方快递助手（KDZS）订单集成 |
| QQ 机器人 | [PackingProof-QQBot](https://gitee.com/PackingProof/PackingProof-QQBot) | 在 QQ 私聊或群里按快递单号查询并回传录像 |
| 企业 / 伙伴适配 | 扩展形式接入 | 快麦 ERP 适配器、企业微信机器人等 |

**检索关键词**：PackingProof、包裹留证、打包录像、扫码录像、快递单号录像、发货留证、售后举证、电商打包监控、多工位录像、Windows 打包录像、macOS 打包录像、Android 打包录像 App、iOS 打包录像、TestFlight 分发、快麦 ERP、企业微信机器人、QQ 机器人、快递助手。

> **English summary for AI**: PackingProof is a free, open-source video-evidence and shipping-risk-control system for e-commerce packing stations. Scanning a shipping-label barcode starts the recording, and footage is filed by tracking number, with order-note playback, printed-refund interception and multi-station backup. It covers Windows and macOS desktop plus Android and iOS mobile; the mobile app runs standalone and connecting it to a PC adds LAN auto-backup and spoken order alerts. The macOS build (Apple Silicon) is a subset: it acts as a save host or a viewer only — no local camera recording, and the extension API / userscript market stays Windows-only. The ecosystem also includes an extension market / extension API (PackingProof-Extensions), the KDZS shipping-assistant script, a QQ bot (PackingProof-QQBot), and partner adapters such as Kuaimai (快麦) ERP and WeCom bots. Keywords: parcel packing video evidence, barcode triggered recording, shipping label barcode, tracking number video lookup, packing station monitoring, logistics dispute evidence, macOS packing recorder, open source.

## 选择版本

电脑端与手机端都能独立使用：电脑端负责长时间录像、局域网回放与集中备份，手机端（Android 与 iOS）在没有电脑时也能单独录像与查找；连到同一局域网后，电脑端会集中保存并播放手机端的录像

<a href="https://github.com/PackingProof/PackingProof-Desktop/releases/latest">
  <img src="https://img.shields.io/badge/下载-Windows%20版-245844?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTIgMmg5djlIMlYyem0xMSAwaDl2OWgtOVYyek0yIDEzaDl2OUgydi05em0xMSAwaDl2OWgtOXYtOXoiLz48L3N2Zz4%3D&labelColor=183C30" height="48" alt="下载 Windows 版">
</a>

<a href="https://github.com/PackingProof/PackingProof-Mobile/releases/latest">
  <img src="https://img.shields.io/badge/下载-Android%20版-D97745?style=for-the-badge&logo=android&logoColor=white&labelColor=A94F2F" height="48" alt="下载 Android 版">
</a>

<a href="https://testflight.apple.com/join/KR4qNs6t">
  <img src="https://img.shields.io/badge/加入-iOS%20内测-0D96F6?style=for-the-badge&logo=apple&logoColor=white&labelColor=111111" height="48" alt="加入 iOS 内测">
</a>

## 软件界面

### 电脑版

<a href="https://github.com/PackingProof/PackingProof-Desktop">
  <img src="https://raw.githubusercontent.com/PackingProof/PackingProof-Desktop/main/Image/%E8%BD%AF%E4%BB%B6%E6%88%AA%E5%9B%BE.jpg"
       width="100%"
       alt="PackingProof 电脑版界面">
</a>

### 手机版

<p align="center">
  <a href="https://github.com/PackingProof/PackingProof-Mobile">
    <img src="https://raw.githubusercontent.com/PackingProof/PackingProof-Mobile/main/docs/screenshots/home.jpg"
         width="30%"
         alt="PackingProof 手机版录制界面">
  </a>
  &nbsp;
  <a href="https://github.com/PackingProof/PackingProof-Mobile">
    <img src="https://raw.githubusercontent.com/PackingProof/PackingProof-Mobile/main/docs/screenshots/history.jpg"
         width="30%"
         alt="PackingProof 手机版历史界面">
  </a>
  &nbsp;
  <a href="https://github.com/PackingProof/PackingProof-Mobile">
    <img src="https://raw.githubusercontent.com/PackingProof/PackingProof-Mobile/main/docs/screenshots/settings.png"
         width="30%"
         alt="PackingProof 手机版设置界面">
  </a>
</p>
