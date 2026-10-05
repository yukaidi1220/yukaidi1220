<div align="center">

# Yukaidi

**网盘 / CDN / 自动化运维** — Cloud storage, CDN and automation plumbing

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-BF1B1B?style=flat-square&logo=gnu-bash&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</div>

---

把网盘、CDN、证书和 GitHub Actions 拼成一套能自己跑起来的下载与分发链路。多数仓库是长期实测的产物，README 里通常一并记下了踩过的坑。

## 精选项目

| 项目 | Stars | 说明 |
| :-- | --: | :-- |
| [rclone](https://github.com/yukaidi1220/rclone) | ![s](https://img.shields.io/github/stars/yukaidi1220/rclone?style=flat-square&label=) | 自维护 rclone：CDN 预签名 `download_host` 与 `head_object`，回源只走 CDN 出口 IP |
| [openlist-to-rclone](https://github.com/yukaidi1220/openlist-to-rclone) | ![s](https://img.shields.io/github/stars/yukaidi1220/openlist-to-rclone?style=flat-square&label=) | Actions 上的网盘搬运工具集：OpenList 批量下载、rclone 多目标 / 分批同步、ISO 重打包 |
| [EEEOS-GET](https://github.com/yukaidi1220/EEEOS-GET) | ![s](https://img.shields.io/github/stars/yukaidi1220/EEEOS-GET?style=flat-square&label=) | Astro 静态站，读取 OpenList 构建元数据，展示系统镜像分发与版本比对 |
| [huaweidns-ddns](https://github.com/yukaidi1220/huaweidns-ddns) | ![s](https://img.shields.io/github/stars/yukaidi1220/huaweidns-ddns?style=flat-square&label=) | 华为云 DNS 双栈 DDNS，IPv4 / IPv6 自动更新，Windows 单文件 exe |
| [Cloudreve-V4-AfdianPay](https://github.com/yukaidi1220/Cloudreve-V4-AfdianPay) | ![s](https://img.shields.io/github/stars/yukaidi1220/Cloudreve-V4-AfdianPay?style=flat-square&label=) | Cloudreve v4 Pro 自定义支付网关，对接爱发电收款 |
| [MSUpdate](https://github.com/yukaidi1220/MSUpdate) | ![s](https://img.shields.io/github/stars/yukaidi1220/MSUpdate?style=flat-square&label=) | fork of xrgzs/MSUpdate，自建 Actions 批量产出集成系统更新的多版本镜像 |
| [aria2](https://github.com/yukaidi1220/aria2) | ![s](https://img.shields.io/github/stars/yukaidi1220/aria2?style=flat-square&label=) | aria2 实验副本：HTTP/2 下载、测试修复与 resolver 调整 |

## 方向

- rclone 与自建后端在 CDN 回源场景下的鉴权方式
- 大规模文件搬运的稳定性实测，据此确定同步 / 分批的边界条件

## Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=yukaidi1220&show_icons=true&count_private=true&hide_rank=true&hide_border=true" alt="GitHub stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs?username=yukaidi1220&layout=compact&langs_count=8&hide_border=true" alt="Top languages" height="165" />

</div>

<div align="center">

![Followers](https://img.shields.io/github/followers/yukaidi1220?style=flat-square&label=follow&color=2ea44f)

</div>
