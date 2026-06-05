# PDF Master Release

这个仓库只用于存放 PDF Master 的 Linux 和 Android 安装包。

最新版本：[PDF Master 0.0.4+4](https://github.com/chengjie-jlu/pdf_master_release/releases/tag/v0.0.4%2B4)

## 下载

### Android

| 设备 / CPU | 下载 |
| --- | --- |
| 大多数新款安卓手机和平板，64 位 ARM | [app-arm64-v8a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.0.4%2B4/app-arm64-v8a-release.apk) |
| 较老的 32 位 ARM 安卓设备 | [app-armeabi-v7a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.0.4%2B4/app-armeabi-v7a-release.apk) |
| 安卓模拟器或 x86_64 设备 | [app-x86_64-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.0.4%2B4/app-x86_64-release.apk) |

下载 APK 后直接安装即可。如果系统提示不允许安装未知来源应用，请在浏览器或文件管理器的权限设置里允许安装。

### Linux

| 系统 / CPU | 下载 |
| --- | --- |
| Debian / Ubuntu，Intel 或 AMD 64 位 | [pdf-master_0.0.4+4_amd64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.0.4%2B4/pdf-master_0.0.4%2B4_amd64.deb) |
| Debian / Ubuntu，ARM 64 位 | [pdf-master_0.0.4+4_arm64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.0.4%2B4/pdf-master_0.0.4%2B4_arm64.deb) |

在 Debian / Ubuntu 上安装：

```bash
sudo dpkg -i pdf-master_0.0.4+4_amd64.deb
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
| app-arm64-v8a-release.apk | `04c24b7d191b9653e073705cd194efe4b41ea687c4a5accdba15a2a4bcfaa7c7` |
| app-armeabi-v7a-release.apk | `75c5d66ebd633d2da0d4668a8a9b76f61bc8d4e29e4d1d3b5cf49dff52f3a600` |
| app-x86_64-release.apk | `f54b406a28621ff6f82c8921fcdd2bbef2e3ca632b967165ed461b95efa0e35d` |
| pdf-master_0.0.4+4_amd64.deb | `63a35a71fcf4c9f331a4648fba5f01f43beffa58e51dfbd8ef6698b17150175f` |
| pdf-master_0.0.4+4_arm64.deb | `a4a536ef7a7095f651a58b2869529ad74dbd15865bd729bbe7de062504574ac8` |

## 历史版本

全部版本在这里：

https://github.com/chengjie-jlu/pdf_master_release/releases
