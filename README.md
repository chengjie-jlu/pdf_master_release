# PDF Master Release

This repository hosts public release artifacts for PDF Master.

- Latest version: [PDF Master 0.2.5+25](https://github.com/chengjie-jlu/pdf_master_release/releases/tag/v0.2.5%2B25)
- All releases: [GitHub Releases](https://github.com/chengjie-jlu/pdf_master_release/releases)
- 中文说明见下方：[中文版本](#中文版本)

## Downloads

### Android

| Device / CPU | Package |
| --- | --- |
| Most modern Android phones and tablets, 64-bit ARM | [app-arm64-v8a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.5%2B25/app-arm64-v8a-release.apk) |
| Older 32-bit ARM Android devices | [app-armeabi-v7a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.5%2B25/app-armeabi-v7a-release.apk) |
| Android emulators or x86_64 devices | [app-x86_64-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.5%2B25/app-x86_64-release.apk) |

After downloading the APK, open it on the device to install. If Android blocks the installation, allow installs from the browser or file manager you used to download the file.

### Linux

| System / CPU | Package |
| --- | --- |
| Debian / Ubuntu, Intel or AMD 64-bit | [pdf-master_0.2.5+25_amd64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.5%2B25/pdf-master_0.2.5%2B25_amd64.deb) |
| Debian / Ubuntu, ARM 64-bit | [pdf-master_0.2.5+25_arm64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.5%2B25/pdf-master_0.2.5%2B25_arm64.deb) |

Install the amd64 package:

```sh
curl -L -o "pdf-master_0.2.5+25_amd64.deb" "https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.5%2B25/pdf-master_0.2.5%2B25_amd64.deb"
sudo apt install "./pdf-master_0.2.5+25_amd64.deb"
```

Install the arm64 package:

```sh
curl -L -o "pdf-master_0.2.5+25_arm64.deb" "https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.5%2B25/pdf-master_0.2.5%2B25_arm64.deb"
sudo apt install "./pdf-master_0.2.5+25_arm64.deb"
```

## Checksums

Verify a downloaded file with SHA256:

```sh
sha256sum <downloaded-file>
```

Current release checksums:

| File | SHA256 |
| --- | --- |
| app-arm64-v8a-release.apk | `5a5cab54009ba98b3eb1dc263563c8fb0e9fb82474f53b574548ec789473ba64` |
| app-armeabi-v7a-release.apk | `425bd693f9de7af199fbb2f8eda3fea6e45a40c190f9f92e77e0141b2f708e87` |
| app-x86_64-release.apk | `bfe2212dfdc4ef7bbe389be2eb5a891634559ed7768f4319d13f9cb407d612f5` |
| pdf-master_0.2.5+25_amd64.deb | `f0be5cb8676095502cfdcef376f8c436a29b88957fa7b244f3763b6ab0bd69b9` |
| pdf-master_0.2.5+25_arm64.deb | `cca1d420abea770c3cf97658fb215baa26ccde22ea6e32b841f44280a9934208` |

## Previous Releases

Older builds are available from the [release history](https://github.com/chengjie-jlu/pdf_master_release/releases).

## 中文版本

这个仓库用于存放 PDF Master 的 Linux 和 Android 公开发布包。

- 最新版本：[PDF Master 0.2.5+25](https://github.com/chengjie-jlu/pdf_master_release/releases/tag/v0.2.5%2B25)
- 全部版本：[GitHub Releases](https://github.com/chengjie-jlu/pdf_master_release/releases)

## 下载

### Android

| 设备 / CPU | 安装包 |
| --- | --- |
| 大多数新款安卓手机和平板，64 位 ARM | [app-arm64-v8a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.5%2B25/app-arm64-v8a-release.apk) |
| 较老的 32 位 ARM 安卓设备 | [app-armeabi-v7a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.5%2B25/app-armeabi-v7a-release.apk) |
| 安卓模拟器或 x86_64 设备 | [app-x86_64-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.5%2B25/app-x86_64-release.apk) |

下载 APK 后，在设备上打开文件即可安装。如果系统提示不允许安装未知来源应用，请在浏览器或文件管理器的权限设置里允许安装。

### Linux

| 系统 / CPU | 安装包 |
| --- | --- |
| Debian / Ubuntu，Intel 或 AMD 64 位 | [pdf-master_0.2.5+25_amd64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.5%2B25/pdf-master_0.2.5%2B25_amd64.deb) |
| Debian / Ubuntu，ARM 64 位 | [pdf-master_0.2.5+25_arm64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.5%2B25/pdf-master_0.2.5%2B25_arm64.deb) |

安装 amd64 包：

```sh
curl -L -o "pdf-master_0.2.5+25_amd64.deb" "https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.5%2B25/pdf-master_0.2.5%2B25_amd64.deb"
sudo apt install "./pdf-master_0.2.5+25_amd64.deb"
```

安装 arm64 包：

```sh
curl -L -o "pdf-master_0.2.5+25_arm64.deb" "https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.2.5%2B25/pdf-master_0.2.5%2B25_arm64.deb"
sudo apt install "./pdf-master_0.2.5+25_arm64.deb"
```

## 校验文件

下载后可以用 SHA256 校验文件：

```sh
sha256sum <downloaded-file>
```

当前版本的 SHA256：

| 文件 | SHA256 |
| --- | --- |
| app-arm64-v8a-release.apk | `5a5cab54009ba98b3eb1dc263563c8fb0e9fb82474f53b574548ec789473ba64` |
| app-armeabi-v7a-release.apk | `425bd693f9de7af199fbb2f8eda3fea6e45a40c190f9f92e77e0141b2f708e87` |
| app-x86_64-release.apk | `bfe2212dfdc4ef7bbe389be2eb5a891634559ed7768f4319d13f9cb407d612f5` |
| pdf-master_0.2.5+25_amd64.deb | `f0be5cb8676095502cfdcef376f8c436a29b88957fa7b244f3763b6ab0bd69b9` |
| pdf-master_0.2.5+25_arm64.deb | `cca1d420abea770c3cf97658fb215baa26ccde22ea6e32b841f44280a9934208` |

## 历史版本

旧版本可以在 [release history](https://github.com/chengjie-jlu/pdf_master_release/releases) 查看。
