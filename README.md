# PDF Master Release

这个仓库只用于存放 PDF Master 的 Linux 和 Android 安装包。

最新版本：[PDF Master 0.0.8+8](https://github.com/chengjie-jlu/pdf_master_release/releases/tag/v0.0.8%2B8)

## 下载

### Android

| 设备 / CPU | 下载 |
| --- | --- |
| 大多数新款安卓手机和平板，64 位 ARM | [app-arm64-v8a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.0.8%2B8/app-arm64-v8a-release.apk) |
| 较老的 32 位 ARM 安卓设备 | [app-armeabi-v7a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.0.8%2B8/app-armeabi-v7a-release.apk) |
| 安卓模拟器或 x86_64 设备 | [app-x86_64-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.0.8%2B8/app-x86_64-release.apk) |

下载 APK 后直接安装即可。如果系统提示不允许安装未知来源应用，请在浏览器或文件管理器的权限设置里允许安装。

### Linux

| 系统 / CPU | 下载 |
| --- | --- |
| Debian / Ubuntu，Intel 或 AMD 64 位 | [pdf-master_0.0.8+8_amd64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.0.8%2B8/pdf-master_0.0.8%2B8_amd64.deb) |
| Debian / Ubuntu，ARM 64 位 | [pdf-master_0.0.8+8_arm64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.0.8%2B8/pdf-master_0.0.8%2B8_arm64.deb) |

在 Debian / Ubuntu 上安装：

```bash
sudo dpkg -i pdf-master_0.0.8+8_amd64.deb
sudo apt-get install -f
```

ARM 设备请把命令里的 `amd64` 包换成 `arm64` 包。

## 校验文件

下载后可以用 SHA256 校验文件：

```bash
sha256sum <downloaded-file>
```

当前版本的 SHA256：

| 文件 | SHA256 |
| --- | --- |
| app-arm64-v8a-release.apk | `1647ee1e8134c105e56e2e859107e90ca2712df141e96fcb2f65caf7a2ab77e5` |
| app-armeabi-v7a-release.apk | `b036786c51f1cc788785c8092498a7154e4537cbf368d7fbd89b252747c17297` |
| app-x86_64-release.apk | `74b780144f53afc4967c085cf113733fc26934d8ce10d5f8dc6c3162132db8d4` |
| pdf-master_0.0.8+8_amd64.deb | `a711acb1c2feb57f5ae26b355488ad1bb2127d15c0aa759cefeb67099282e2f3` |
| pdf-master_0.0.8+8_arm64.deb | `105cb91260d3771ab112a115523ef3ab0ad2364d6d0988772290bc020391d5c5` |

## 历史版本

全部版本在这里：

https://github.com/chengjie-jlu/pdf_master_release/releases
