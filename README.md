# AppleBlockWebsit
AppleBlock我的世界服务器官网开源
[体验DEMO](https://mxmilu666.github.io/AppleBlockWebsite/)

## 🛠️ 部署
部署前需要拥有WEB引擎等必要应用
(部署独立MOTD需要PHP环境)
``` shell
#拉取并解压资源
unzip AppleBlockWebsit_{{VERSION}}.zip
```

## ⚙️ 配置
使用任意文本编辑器打开`index.html`

修改MOTD:
``` code
#找到
<div class="playercount mdui-text-color-white-text" style="font-weight:300;">目前有<span class="sip" data-ip="mc.appleblock.cn" data-port="25565"></span>位小伙伴正在游玩"<span class="ip">mc.appleblock.cn</span>"<br>AppleBlock生存服,期待您成为下一位！(点击ip复制)
#修改mc.appleblock.cn为你的IP 25565为你的端口
```
修改基岩快速进服:
``` code
#找到
<p data-aos="fade-up" data-aos-delay="200"><a href="minecraft:?addExternalServer=AppleBlock纯生存|mc.appleblock.cn:19132" onclick="alert('我们将唤起本地的 MinecraftBE 客户端并自动添加服务器信息，若无法唤起请检查浏览器权限或更换浏览器。')" class="btn btn-primary py-3 px-4" >基岩版快速加入</a></p>
#修改mc.appleblock.cn为你的IP 19132为你的端口 AppleBlock纯生存为你服务器的名字
```
开启黑白默哀:
``` code
#找到
    <!-- .
    <style>
        body {
            filter: grayscale(1);
        }
    </style>
    -->
#删除注释即可
```
## 🎈 部署独立版MOTD
在Releases中下载最新版jmotd.zip

解压并放在index.html的根目录中(./jmotd/index.php)

## 📖许可证
项目采用`Apache-2.0 license`协议开源

## 🚗使用项目/第三方库
[Webmain](https://www.go176.net/post-2546.html)

Bootstrap/Aos/Hamburgers/Owl Carousel/Icomoon icon/Animate/Animsition/Theme Style/Mdui
