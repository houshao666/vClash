<h1 align="center">
  <img src="https://github.com/learnhard-cn/clash/raw/main/res/icon-clash.png" alt="Clash" width="200">
  <br>vClash科学上网插件<br>
</h1>

# vClash项目说明
>这个项目插件适用于`Koolshare的华硕官改、梅林改版 380/384/386固件`。会不会有openwrt版本呢？有时间再考虑吧。

项目两个分支：
- main分支： 支持380固件，能用，不再更新新功能了。
- ksmerlin386分支： 支持384/386固件，持续更新。

## 使用前说明
> 由于GoLang版本Clash启动时分配内存空间较大，对于小内存路由器最容易出现**启动失败问题**,以`RT-AC68U`为例，启动时分配虚拟内存(VIRT)有600-700MB左右，对于512MB物理内存路由器直接起不来。

启动失败问题解决：

1. 挂载虚拟内存: 支持**USB接口路由器**可以插入一个1GB以上的优盘作为虚拟内存挂载，当然速度越快越好了。[阅读挂载虚拟内存教程文章](https://vlike.work/VPS/router-mount-swap.html)。



## 为什么有这个项目

由于种种原因，某些路由器的固件停留在了`梅林380改版`，但是现在很多插件开发都不再支持`梅林380改版`了，例如`Clash`没有找到一个支持版本。

因此，就产生了这个项目。

之后，用着用着就过渡到了`华硕官改386固件`,进而又开发了支持`386版本`的插件。

但实测路由器型号不多，一些小问题在所难免，如果希望本项目可以使用到自己的路由器上，有两个方法：

1. 详细描述或截图出现的问题提交个issue，回复不一定及时，看到必回。
2. 自己有开发能力，把问题解决，分享修改代码内容给这个项目，让你的问题不再出现，也让这个插件可以更稳定。


## 主界面

![](./images/demo.png)

