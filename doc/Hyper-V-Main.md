
为了在windows上运行docker，需要开启Hyper-V,
而处理器的硬件虚拟化是独占功能，所以Hyper-V与VirtualBox虚拟机不能共存，市面上大部分安卓模拟器都是基于VirtualBox开发，开启Hyper-V会导致导致模拟器运行效率低下或无法运行。

解决方法很多，我选择开启Hyper-V并使用基于Hyper-V的安卓模拟器。

[开启Hyper-V](doc/Hyper-V-Enable.md)


### 支持Hyper-V的模拟器
- Bluestacks

[https://support.bluestacks.com/hc/zh-tw](https://support.bluestacks.com/hc/zh-tw)

网站支持繁中，模拟器有简中

但是竖屏时会自动缩放（缩小），不便于我日常游戏脚本使用，放弃

其他方面暂未研究

- Genymotion

[https://www.genymotion.com/](https://www.genymotion.com/)

不支持简中

root权限需要付费版（订阅付费，非一次性）

试了一下，给4核2G内存，用系统浏览器打开百度会卡死，具体原因未知。
