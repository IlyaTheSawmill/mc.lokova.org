title: 加入
layout: default
---

# 加入LokovaMC服务器

## 客户端的选择

LokovaMC服务器目前的服务端核心为[Leaves](https://leavesmc.org) 1.21.8，且ViaVersion等插件不支持使用，故必须使用与服务端核心相同版本，即Java版1.21.8的客户端加入服务器。

并没有对客户端类型（Fabric、NeoForge、Meteor、Wurst、原版等）的限制。

## 身份验证

LokovaMC支持两种身份验证模式：LittleSkin验证和正版验证。

### LittleSkin验证

请参考[LittleSkin用户手册](https://manual.littlesk.in/)。

在LittleSkin中设置的皮肤必须安装[CustomSkinLoader](https://littleskin.cn/user/config "CustomSkinLoader") Mod才能看见，无论是自己的还是别人的。如果显示的皮肤与设置的不同，请将CustomSkinLoader配置文件中的`CustomSkinLoader.json`设为[此内容](/csl-cfg)。（事实上即使没有此类问题，也建议将其设为此内容，以确保LittleSkin的加载优先级高于正版，从而践行社区高于官方的原则。）

如果持有正版Minecraft，请勿在未[绑定正版](https://manual.littlesk.in/newbee/premium "绑定正版")的情况下使用与正版玩家名相同的LittleSkin玩家加入服务器，否则会导致同一个玩家名称对应不同UUID的情况。绑定正版后LittleSkin玩家的UUID与正版相同。这也能防止在LittleSkin皮肤加载优先级高于正版的情况下显示同名LittleSkin玩家使用的皮肤而不是自己设置的皮肤——绑定正版会强制将该玩家名置于自己名下。

使用LittleSkin比起使用正版有两个好处：一个是能使用Mojang没有的自定义披风，另一个是能防止Mojang审核皮肤（因为LittleSkin支持上传其他人包括运营方都不能看到的私密材质）。缺点是如果其他情况下需要正版，切换会比较麻烦。

### 正版验证

正常使用即可。

## 加入后

加入成功！现在你应该可以正常游戏了。可以通过`/info`查看帮助、`/help`查看指令用法。

详细的帮助可以在[教程](/tutorials)页面找到。