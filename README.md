# PDF Master Release

This repository hosts public release artifacts for PDF Master.

- Latest version: [PDF Master 0.1.1+11](https://github.com/chengjie-jlu/pdf_master_release/releases/tag/v0.1.1%2B11)
- All releases: [GitHub Releases](https://github.com/chengjie-jlu/pdf_master_release/releases)
- 中文说明见下方：[中文版本](#中文版本)

## Downloads

### Android

| Device / CPU | Package |
| --- | --- |
| Most modern Android phones and tablets, 64-bit ARM | [app-arm64-v8a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.1.1%2B11/app-arm64-v8a-release.apk) |
| Older 32-bit ARM Android devices | [app-armeabi-v7a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.1.1%2B11/app-armeabi-v7a-release.apk) |
| Android emulators or x86_64 devices | [app-x86_64-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.1.1%2B11/app-x86_64-release.apk) |

After downloading the APK, open it on the device to install. If Android blocks the installation, allow installs from the browser or file manager you used to download the file.

### Linux

| System / CPU | Package |
| --- | --- |
| Debian / Ubuntu, Intel or AMD 64-bit | [pdf-master_0.1.1+11_amd64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.1.1%2B11/pdf-master_0.1.1%2B11_amd64.deb) |
| Debian / Ubuntu, ARM 64-bit | [pdf-master_0.1.1+11_arm64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.1.1%2B11/pdf-master_0.1.1%2B11_arm64.deb) |

Install the amd64 package:

```sh
curl -L -o "pdf-master_0.1.1+11_amd64.deb" "https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.1.1%2B11/pdf-master_0.1.1%2B11_amd64.deb"
sudo apt install "./pdf-master_0.1.1+11_amd64.deb"
```

Install the arm64 package:

```sh
curl -L -o "pdf-master_0.1.1+11_arm64.deb" "https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.1.1%2B11/pdf-master_0.1.1%2B11_arm64.deb"
sudo apt install "./pdf-master_0.1.1+11_arm64.deb"
```

## Checksums

Verify a downloaded file with SHA256:

```sh
sha256sum <downloaded-file>
```

Current release checksums:

| File | SHA256 |
| --- | --- |
| app-arm64-v8a-release.apk | `c97189801388331540c08b6daa0c535f9383b83ec2ac57b505151feed8259a13` |
| app-armeabi-v7a-release.apk | `a0c69adf26a28e50ec8b7ae4e1d1f123a4c6c09bed15e7129e8c75b73d82dac7` |
| app-x86_64-release.apk | `c2e0729789a17b1cadc78b6b9f1eea66145bb6a492f07c1969d92258707c1d57` |
| pdf-master_0.1.1+11_amd64.deb | `c2ffd182b8dae5c0eecfd2de60dc79e340c66e2ae508e729d2b0f72f81743f49` |
| pdf-master_0.1.1+11_arm64.deb | `0530813906a1c441fcdaf4013b89820336176c9a9d9713969d52a83d2fe9e521` |

## Previous Releases

Older builds are available from the [release history](https://github.com/chengjie-jlu/pdf_master_release/releases).

## 中文版本

这个仓库用于存放 PDF Master 的 Linux 和 Android 公开发布包。

- 最新版本：[PDF Master 0.1.1+11](https://github.com/chengjie-jlu/pdf_master_release/releases/tag/v0.1.1%2B11)
- 全部版本：[GitHub Releases](https://github.com/chengjie-jlu/pdf_master_release/releases)

## 下载

### Android

| 设备 / CPU | 安装包 |
| --- | --- |
| 大多数新款安卓手机和平板，64 位 ARM | [app-arm64-v8a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.1.1%2B11/app-arm64-v8a-release.apk) |
| 较老的 32 位 ARM 安卓设备 | [app-armeabi-v7a-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.1.1%2B11/app-armeabi-v7a-release.apk) |
| 安卓模拟器或 x86_64 设备 | [app-x86_64-release.apk](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.1.1%2B11/app-x86_64-release.apk) |

下载 APK 后，在设备上打开文件即可安装。如果系统提示不允许安装未知来源应用，请在浏览器或文件管理器的权限设置里允许安装。

### Linux

| 系统 / CPU | 安装包 |
| --- | --- |
| Debian / Ubuntu，Intel 或 AMD 64 位 | [pdf-master_0.1.1+11_amd64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.1.1%2B11/pdf-master_0.1.1%2B11_amd64.deb) |
| Debian / Ubuntu，ARM 64 位 | [pdf-master_0.1.1+11_arm64.deb](https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.1.1%2B11/pdf-master_0.1.1%2B11_arm64.deb) |

安装 amd64 包：

```sh
curl -L -o "pdf-master_0.1.1+11_amd64.deb" "https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.1.1%2B11/pdf-master_0.1.1%2B11_amd64.deb"
sudo apt install "./pdf-master_0.1.1+11_amd64.deb"
```

安装 arm64 包：

```sh
curl -L -o "pdf-master_0.1.1+11_arm64.deb" "https://github.com/chengjie-jlu/pdf_master_release/releases/download/v0.1.1%2B11/pdf-master_0.1.1%2B11_arm64.deb"
sudo apt install "./pdf-master_0.1.1+11_arm64.deb"
```

## 校验文件

下载后可以用 SHA256 校验文件：

```sh
sha256sum <downloaded-file>
```

当前版本的 SHA256：

| 文件 | SHA256 |
| --- | --- |
| app-arm64-v8a-release.apk | `c97189801388331540c08b6daa0c535f9383b83ec2ac57b505151feed8259a13` |
| app-armeabi-v7a-release.apk | `a0c69adf26a28e50ec8b7ae4e1d1f123a4c6c09bed15e7129e8c75b73d82dac7` |
| app-x86_64-release.apk | `c2e0729789a17b1cadc78b6b9f1eea66145bb6a492f07c1969d92258707c1d57` |
| pdf-master_0.1.1+11_amd64.deb | `c2ffd182b8dae5c0eecfd2de60dc79e340c66e2ae508e729d2b0f72f81743f49` |
| pdf-master_0.1.1+11_arm64.deb | `0530813906a1c441fcdaf4013b89820336176c9a9d9713969d52a83d2fe9e521` |

## 历史版本

旧版本可以在 [release history](https://github.com/chengjie-jlu/pdf_master_release/releases) 查看。
