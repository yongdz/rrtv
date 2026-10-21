# 人人视频下载 · RRTV Downloads

人人视频安装包下载入口，提供固定版本直链、机器可读文件清单和 SHA-256 校验值。安装包存放在本仓库的 GitHub Releases 中。

## 直接下载

| 软件 | 平台 | 版本 | 大小 | 下载 |
| --- | --- | --- | --- | --- |
| 人人视频 | macOS | 1.2.3 | 34,598,940 字节（约 33 MiB） | [下载 DMG](https://github.com/yongdz/rrtv-downloads/releases/download/v1.2.3/rrtv-mac-1.2.3.dmg) |

[查看 Release](https://github.com/yongdz/rrtv-downloads/releases/tag/v1.2.3) · [文件清单](downloads.json) · [SHA-256 清单](SHA256SUMS)

原文件名：`人人视频_Mac_1.2.3.dmg`。Release 附件使用英文文件名 `rrtv-mac-1.2.3.dmg`，文件内容保持一致。

## 复制这段提示词给 AI

```text
请读取 https://raw.githubusercontent.com/yongdz/rrtv-downloads/main/downloads.json，
找到“人人视频 Mac”1.2.3 的记录，使用 download_url 下载 DMG 到我的下载目录。
下载后核对 size_bytes 和 sha256，并报告实际保存路径和校验结果。
如果你没有文件下载或本地写入能力，请给我可点击的下载直链，不要声称已经下载。
```

也可以说：

> 请根据 https://github.com/yongdz/rrtv-downloads 的文件清单，下载人人视频 Mac 安装包，并核对 SHA-256。

需要使用能联网的 AI；实际保存文件还需要下载和文件写入工具。提示词中保留仓库或清单链接，便于准确定位。公开仓库不保证被所有搜索引擎或 AI 自动收录。

## 在 macOS 终端下载并校验

```sh
mkdir -p "$HOME/Downloads"
curl --fail --location --output "$HOME/Downloads/rrtv-mac-1.2.3.dmg" \
  'https://github.com/yongdz/rrtv-downloads/releases/download/v1.2.3/rrtv-mac-1.2.3.dmg'
shasum -a 256 "$HOME/Downloads/rrtv-mac-1.2.3.dmg"
```

预期字节数：`34598940`。

预期 SHA-256：

```text
cfe5ff2841eb5969f921cc08b285f331162207291be9cff8bdb594d9ca70dc19
```

核对一致后再自行打开安装包。SHA-256 用于校验文件一致性，不代表软件安全性或官方签名验证。

## 供工具读取

机器可读清单：[downloads.json](https://raw.githubusercontent.com/yongdz/rrtv-downloads/main/downloads.json)。

每个文件记录包含 `id`、`name`、`version`、`platform`、`filename`、`size_bytes`、`sha256`、`download_url` 和 `release_url`。按软件、平台和版本匹配记录后，使用 `download_url` 下载并校验。清单没有的版本不应猜测下载地址。

## 后续添加文件

1. 创建对应版本的 Release，上传安装包；附件使用清晰的英文文件名。
2. 读取发布后的实际下载地址，计算原文件的字节数和 SHA-256。
3. 更新 `downloads.json`、`SHA256SUMS` 和本页下载表；保留需要继续提供的历史版本记录。

## 文件说明

本仓库提供安装包下载索引，不包含应用源码；不据此声明官方分发身份。应用名称及安装包的权利归其各自权利人所有，本仓库不为安装包新增开源许可。
