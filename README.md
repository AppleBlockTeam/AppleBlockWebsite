# AppleBlockWebsit
我的世界服务器官网开源
[体验DEMO](https://AppleBlock.cn/)

## 🛠️ 部署
部署前需要拥有Nginx等必要依赖
``` shell
#解压资源
unzip AppleBlockWebsit_{{VERSION_OS_ARCH}}.zip
```

## ⚙️ 配置
使用任意文本编辑器打开`index.html`

修改MOTD:
``` code
#找到
<p>现在有 <span class="sip" data-ip="mc.appleblock.cn" data-port="25565">
</span> 个人正在服务器内游玩 <span class="ip">mc.appleblock.cn</span></p>
#修改mc.appleblock.cn为你的IP 25565为你的端口
```
修改基岩快速进服:
``` code
#找到
            <p data-aos="fade-up" data-aos-delay="200"><a href="minecraft:?addExternalServer=AppleBlock纯生存|mc.appleblock.cn:19132" onclick="alert('我们将唤起本地的 MinecraftBE 客户端并自动添加服务器信息，若无法唤起请检查浏览器权限或更换浏览器。')" class="btn btn-primary py-3 px-4" >基岩版快速加入</a></p>
#修改mc.appleblock.cn为你的IP 19132为你的端口 AppleBlock纯生存为你服务器的名字
```
## 📖许可证
项目采用`Apache-2.0 license`协议开源

## 🚗使用项目
[MDUI](https://www.mdui.org/)
[MOTD](https://www.spigotmc.org/resources/minecraft-website-template-portal-%E2%98%85-responsive-%E2%98%85-easy.48410/)
[源码](https://www.go176.net/post-2546.html)
