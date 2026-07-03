# PDF Master Release

This repository hosts public release artifacts for PDF Master.

- Latest version: [PDF Master 0.2.8+28](https://github.com/chengjie-jlu/pdf_master_release/releases/tag/v0.2.8%2B28)
- All releases: [GitHub Releases](https://github.com/chengjie-jlu/pdf_master_release/releases)
- 中文说明见下方：[中文版本](#中文版本)

## Downloads

### Android

| Device / CPU | Package |
| --- | --- |
| Most modern Android phones and tablets, 64-bit ARM | [app-arm64-v8a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.8%2B28/app-arm64-v8a-release.apk) |
| Older 32-bit ARM Android devices | [app-armeabi-v7a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.8%2B28/app-armeabi-v7a-release.apk) |
| Android emulators or x86_64 devices | [app-x86_64-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.8%2B28/app-x86_64-release.apk) |

After downloading the APK, open it on the device to install. If Android blocks the installation, allow installs from the browser or file manager you used to download the file.

### Linux

| System / CPU | Package |
| --- | --- |
| Debian / Ubuntu, Intel or AMD 64-bit | [pdf-master_0.2.8+28_amd64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.8%2B28/pdf-master_0.2.8%2B28_amd64.deb) |
| Debian / Ubuntu, ARM 64-bit | [pdf-master_0.2.8+28_arm64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.8%2B28/pdf-master_0.2.8%2B28_arm64.deb) |

Install the amd64 package:

```sh
curl -L -o "pdf-master_0.2.8+28_amd64.deb" "https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.8%2B28/pdf-master_0.2.8%2B28_amd64.deb"
sudo apt install "./pdf-master_0.2.8+28_amd64.deb"
```

Install the arm64 package:

```sh
curl -L -o "pdf-master_0.2.8+28_arm64.deb" "https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.8%2B28/pdf-master_0.2.8%2B28_arm64.deb"
sudo apt install "./pdf-master_0.2.8+28_arm64.deb"
```

## Checksums

Verify a downloaded file with SHA256:

```sh
sha256sum <downloaded-file>
```

Current release checksums:

| File | SHA256 |
| --- | --- |
| app-arm64-v8a-release.apk | `1f52ca95510ce6f8773b48eb47a7713cdca3b27bd27049dcf4d86cd2faf97cdf` |
| app-armeabi-v7a-release.apk | `f2e2eed975313756315af4483bbe2cc95f62d5f0fbab1909a2f0c921e90cb3a1` |
| app-x86_64-release.apk | `a88b9f454bf85cb62ee077e31cab784fc97a0457cdc75df0228bf8f41655c7fd` |
| pdf-master_0.2.8+28_amd64.deb | `9688d385caccc58bbf6c6fa2113a4440422193ee5fb7e6130db63f75aef1c6e5` |
| pdf-master_0.2.8+28_arm64.deb | `469b12afdfa549410cb2d6a19008bca38d3b15e9941e932bb1d0a93afa939bea` |

## Previous Releases

Older builds are available from the [release history](https://github.com/chengjie-jlu/pdf_master_release/releases).

## 中文版本

这个仓库用于存放 PDF Master 的 Linux 和 Android 公开发布包。

- 最新版本：[PDF Master 0.2.8+28](https://github.com/chengjie-jlu/pdf_master_release/releases/tag/v0.2.8%2B28)
- 全部版本：[GitHub Releases](https://github.com/chengjie-jlu/pdf_master_release/releases)

## 下载

### Android

| 设备 / CPU | 安装包 |
| --- | --- |
| 大多数新款安卓手机和平板，64 位 ARM | [app-arm64-v8a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.8%2B28/app-arm64-v8a-release.apk) |
| 较老的 32 位 ARM 安卓设备 | [app-armeabi-v7a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.8%2B28/app-armeabi-v7a-release.apk) |
| 安卓模拟器或 x86_64 设备 | [app-x86_64-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.8%2B28/app-x86_64-release.apk) |

下载 APK 后，在设备上打开文件即可安装。如果系统提示不允许安装未知来源应用，请在浏览器或文件管理器的权限设置里允许安装。

### Linux

| 系统 / CPU | 安装包 |
| --- | --- |
| Debian / Ubuntu，Intel 或 AMD 64 位 | [pdf-master_0.2.8+28_amd64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.8%2B28/pdf-master_0.2.8%2B28_amd64.deb) |
| Debian / Ubuntu，ARM 64 位 | [pdf-master_0.2.8+28_arm64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.8%2B28/pdf-master_0.2.8%2B28_arm64.deb) |

安装 amd64 包：

```sh
curl -L -o "pdf-master_0.2.8+28_amd64.deb" "https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.8%2B28/pdf-master_0.2.8%2B28_amd64.deb"
sudo apt install "./pdf-master_0.2.8+28_amd64.deb"
```

安装 arm64 包：

```sh
curl -L -o "pdf-master_0.2.8+28_arm64.deb" "https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.8%2B28/pdf-master_0.2.8%2B28_arm64.deb"
sudo apt install "./pdf-master_0.2.8+28_arm64.deb"
```

## 校验文件

下载后可以用 SHA256 校验文件：

```sh
sha256sum <downloaded-file>
```

当前版本的 SHA256：

| 文件 | SHA256 |
| --- | --- |
| app-arm64-v8a-release.apk | `1f52ca95510ce6f8773b48eb47a7713cdca3b27bd27049dcf4d86cd2faf97cdf` |
| app-armeabi-v7a-release.apk | `f2e2eed975313756315af4483bbe2cc95f62d5f0fbab1909a2f0c921e90cb3a1` |
| app-x86_64-release.apk | `a88b9f454bf85cb62ee077e31cab784fc97a0457cdc75df0228bf8f41655c7fd` |
| pdf-master_0.2.8+28_amd64.deb | `9688d385caccc58bbf6c6fa2113a4440422193ee5fb7e6130db63f75aef1c6e5` |
| pdf-master_0.2.8+28_arm64.deb | `469b12afdfa549410cb2d6a19008bca38d3b15e9941e932bb1d0a93afa939bea` |

## 历史版本

旧版本可以在 [release history](https://github.com/chengjie-jlu/pdf_master_release/releases) 查看。
