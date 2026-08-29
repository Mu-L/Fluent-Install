# 打开后准备

如果之前用过别的入库软件，请到设置净化steam
然后点击安装内核DLL
安装好后就可以到入库界面入库了

可选：ost云存档：

很久很久以前，有一个叫SteamTools的工具。SteamTools 支持云保存，算是吧。

后来，Valve修补了SteamTools用来同步存档的（罪恶的）问题。具体来说，SteamTools 将请求重写为 AppID 760，也就是 Steam 截图。它把所有非拥有的 Steam Cloud AppID 请求都发到了那里。它没有为每款单独游戏创建前缀，这意味着每个lua应用都与其他所有应用共享存档。如果多个游戏使用同一个存档文件名，可能会导致存档冲突。这也意味着你的存档会被复制到每个Lua应用的文件夹里。

它也完全不支持 Steam AutoCloud 游戏。这只是显示那些游戏的假成功信息。

所以，一个工具CloudRedirect诞生了！

首先，我们需要下载ost-1.4.9版本(软件内置的是1.4.8)，把三个dll复制到steam根目录

然后打开pvz大佬魔改的CloudRedirect.exe，部署DLL

<img width="1313" height="950" alt="image" src="https://github.com/user-attachments/assets/73feffe0-fe0e-427e-b344-9fa236f35555" />

提供商选创意工坊

<img width="1313" height="950" alt="image" src="https://github.com/user-attachments/assets/ba471ae1-33da-42c6-8c4d-c95933356576" />

最后重启steam，工具就可以关了

下载地址：

https://1823125279.share.123pan.cn/123pan/Gk8wjv-5EBCd

---

[下一步：安装 FluentInstall →](/guide/install)
