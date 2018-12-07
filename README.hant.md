<div align="center">

<img width="150" height="150" src="extras/icon.png">

# wslu - 一套Windows 10 Linux子系統工具組

[![GitHub license](https://badgen.net/github/license/wslutilities/wslu?icon=github&label=&color=cyan)](https://github.com/wslutilities/wslu/blob/master/LICENSE)
[![GitHub (pre-)release](https://badgen.net/github/release/wslutilities/wslu?icon=github&label=&color=yellow)](https://github.com/wslutilities/wslu)
[![Circle CI master](https://badgen.net/circleci/github/wslutilities/wslu/master?label=master&icon=circleci)](https://circleci.com/gh/wslutilities/wslu/tree/master)
[![Circle CI develop](https://badgen.net/circleci/github/wslutilities/wslu/develop?label=develop&icon=circleci)](https://circleci.com/gh/wslutilities/wslu/tree/develop)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fpatrick330602%2Fwslu.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fpatrick330602%2Fwslu?ref=badge_shield)
[![Donate](https://badgen.net/badge/Donate/Paypal/purple)](https://www.paypal.me/callmepk/)
[![Backers on Open Collective](https://opencollective.com/wslu/backers/badge.svg)](#backers)
[![Sponsors on Open Collective](https://opencollective.com/wslu/sponsors/badge.svg)](#sponsors) 

[English](README.md) | [简体中文](README.hans.md) | 繁體中文

</div>

這是一套適用於Windows 10 Linux子系統的工具組，可以在Windows 10 Linux子系統下完成諸如將Windows路徑轉換為WSL專屬路徑或者建立你最喜愛的Linux程式桌面快捷方式等工作。需要Windows 10創造者更新或更高。

**目前支援的Linux發行版：**
- [WLinux][1]和其[企業版][2]
- Ubuntu[最新版][3]，[16.04 LTS][4]和[18.04 LTS][5]
- OpenSUSE Leap [42][6]和[15.0][7]
- SUSE Linux Enterprise Server [12][8]和[15][9]
- [Debian GNU/Linux][10]
- [Kali Linux][11]
- 通過[ArchWSL][12]實現的Arch Linux
- 通過[AlpineWSL][13]或[Alpine WSL][14]實現的Alpine Linux
[1]: https://www.microsoft.com/store/productId/9NV1GV1PXZ6P
[2]: https://www.microsoft.com/store/productId/9N8LP0X93VCP
[3]: https://www.microsoft.com/store/productId/9NBLGGH4MSV6
[4]: https://www.microsoft.com/store/productId/9PJN388HP8C9
[5]: https://www.microsoft.com/store/productId/9N9TNGVNDL3Q
[6]: https://www.microsoft.com/store/productId/9NJVJTS82TJX
[7]: https://www.microsoft.com/store/productId/9N1TB6FPVJ8C
[8]: https://www.microsoft.com/store/productId/9P32MWBH6CNS
[9]: https://www.microsoft.com/store/productId/9PMW35D7FNLX
[10]: https://www.microsoft.com/store/productId/9MSVKQC78PK6
[11]: https://www.microsoft.com/store/productId/9PKR34TNCV07
[12]: https://github.com/yuk7/ArchWSL
[13]: https://github.com/yuk7/AlpineWSL
[14]: https://www.microsoft.com/store/productId/9P804CRF0395

舊版Ubuntu不再被支援。

## 功能

**wslusc**
這是用於建立Linux程式Windows桌面捷徑的工具。

**wslsys**
這是可以展示Windows和Linux下的系統資訊的工具。

**wslfetch**
這是類似於screenfetch的系統資訊展示工具。

**wslvar**
這是用於轉換Windows/WSL路徑的工具。

**wslview**
這是一個將Windows預設網路瀏覽器繫結為WSL網路瀏覽器的包裝工具。

## 安裝

### WLinux

WLinux已內建。

### Ubuntu/Debian/Kali Linux

執行以下命令:
```bash
sudo apt install apt-transport-https
wget -O - https://api.patrickwu.space/public.key | sudo apt-key add -
echo "deb https://apt.patrickwu.space/ stable main" | sudo tee -a /etc/apt/sources.list 
sudo apt update
sudo apt install wslu
```

或者你可以從Releases介面下載.deb進行安裝：`sudo dpkg -i wslu*`。

### OpenSUSE/SLES

執行以下命令:執行以下命令:
```bash
sudo zypper ar https://rpm.patrickwu.space/ ruapm
sudo zypper ref
sudo zypper in wslu
```

或者你可以從Releases介面下載.rpm進行安裝：`sudo rpm -ivh "wslu*"`。

## 貢獻者

沒有你們，這個項目不可能存在。[[為這項目作出貢獻](CONTRIBUTING.md)]。
<img src="https://opencollective.com/wslu/contributors.svg?width=890&button=false" />


## 支持者

感謝所有的支持者！ 🙏 [[成為支持者](tps://opencollective.com/wslu#backer)]。

<a href="https://opencollective.com/wslu#backers" target="_blank"><img src="https://opencollective.com/wslu/backers.svg?width=890"></a>


## 贊助者

支援這個項目，成為贊助者。你的logo和網站連結會在此顯示。[[成為贊助者](https://opencollective.com/wslu#sponsor)]。

<a href="https://opencollective.com/wslu/sponsor/0/website" target="_blank"><img src="https://opencollective.com/wslu/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/wslu/sponsor/1/website" target="_blank"><img src="https://opencollective.com/wslu/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/wslu/sponsor/2/website" target="_blank"><img src="https://opencollective.com/wslu/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/wslu/sponsor/3/website" target="_blank"><img src="https://opencollective.com/wslu/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/wslu/sponsor/4/website" target="_blank"><img src="https://opencollective.com/wslu/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/wslu/sponsor/5/website" target="_blank"><img src="https://opencollective.com/wslu/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/wslu/sponsor/6/website" target="_blank"><img src="https://opencollective.com/wslu/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/wslu/sponsor/7/website" target="_blank"><img src="https://opencollective.com/wslu/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/wslu/sponsor/8/website" target="_blank"><img src="https://opencollective.com/wslu/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/wslu/sponsor/9/website" target="_blank"><img src="https://opencollective.com/wslu/sponsor/9/avatar.svg"></a>

## 許可（英文）

本項目使用[GPLv3](LICENSE)許可。

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fpatrick330602%2Fwslu.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fpatrick330602%2Fwslu?ref=badge_large)

