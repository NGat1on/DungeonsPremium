<div style="display: flex; align-items: center;">
    <img src="https://github.com/NGat1on/DungeonsPremium/blob/main/image/icon.png" align="left" width="35" height="35" />
    <div style="margin-left: 10px;">
        <h3 style="margin: 0;">神话地牢(DungeonsPremium)</h3>
    </div>
</div>

<hr>
<p>
  <img src="https://img.shields.io/badge/code size-1.06MB-blue" alt="code size"/>
  <img src="https://img.shields.io/badge/Bukkit-1.12.2-brightgreen" alt="Bukkit"/>
  <img src="https://img.shields.io/badge/Java Class-104-blue" alt="Java"/>
  <img src="https://img.shields.io/badge/releases-v1.1.0-blue" alt="releases"/><a href="http://wpa.qq.com/msgrd?v=3&uin=1320510756&site=qq&menu=yes">
    <img src="https://img.shields.io/badge/Get Plugin-click-brightgreen" alt="click"/>
  <img src="https://img.shields.io/badge/Author-念国-orange" alt="Author" />
</a>

</p>

> 此插件为付费插件<br>
> 购买后提供:售后服务，插件及Setup服务端请在售后群下载<br>
> 💫作者：念国（点击下方文字即可跳转主页）<br>
> 🌟全平台账号：[GitHub](https://github.com/NGat1on)、[爱发电](https://afdian.net/a/ngat1on)、[哔哩哔哩](https://space.bilibili.com/455695897/)、[QQ](http://wpa.qq.com/msgrd?v=3&uin=1320510756&site=qq&menu=yes)<br>
> 项目地址：<br>
> https://github.com/NGat1on/DungeonsPremium <br>
> 后台地址：<br>
> http://????????.???:???/

<details>
  <summary>点击此处查看更新日志</summary>

> v1.0.0 Date:2024/2/20 <br>
> 项目初始化 <br>

> v1.0.1 Date:2024/2/21 <br>
> 修复部分Bug

> v1.0.2 Date:2024/2/22 <br>
> 修复部分已知Bug<br>
> 完善指令帮助<br>
> 添加玩家前缀<br>
> 移除指令:/md [change/add] 的exp指令

> v1.0.3 Date:2024/2/23 <br>
> 修复一些已知Bug<br>
> 增加全息排行榜[顶级玩家排行榜]

> v1.0.4 Date:2024/3/02 <br>
> 修复一些已知Bug<br>
> 增加排行榜(击杀,精通,累计硬币)<br>
> 增加附魔之井(45%附魔所有属性)<br>
> 增加连杀助理(每次击杀+4%力量,有效时间8秒)<br>
> 新增特效(击杀特效,打击特效,进服特效)<br>
> 赏金|连杀系统加入<br>
> 优化指令|计分板<br>
> 新增指令:/md [invsee/give]<br>

> v1.0.5 Date:2024/3/09 <br>
> 修复一些已知Bug<br>
> 增加指令:/cdk [code/add/remove/list/set/give]<br>
> 增加指令:/spawn 与 /deleteFile [player] <br>
> 新增生成NPC指令

> v1.0.6 Date:2024/3/14 <br>
> 修复一些已知Bug<br>
> 发布第一个启动端<br>
> 插件菜单更新

> v1.0.7 Date:2024/3/15 <br>
> 修复一些已知Bug<br>
> 新增附魔属性<br>
> 插件菜单优化
  
> v1.0.8 Date:2024/3/17 <br>
> 修复一些已知Bug<br>
> 优化计分板(解决90%的闪烁问题)<br>
> 优化神话物品掉落<br>
> 第一张插件玩法图

> v1.0.9 Date:2024/3/21 <br>
> 修复一些已知Bug<br>
> 优化菜单(解决80%的问题)<br>
> 改进一些附魔

> v1.1.0 Date:2024/3/28 <br>
> 修复一些已知Bug<br>
> 新增魔法值系统 <br>
> 优化ActionBar <br>
> 新增指令:/wipe [player] <br>
> 新增事件

> v1.1.1 Date:2024/7/?? 即将来临 <br>
> 修复大部分已知Bug<br>
> 优化指令与菜单<br>
> 新增Boss及相应事件 <br>
> 对~~MySQL~~与MongoDB数据库的支持 <br>
> 配置文件优化 <br>
> 改进玩家数据
</details>

## 目录
- [上手指南](#上手指南)
  - [前置要求](#前置要求)
  - [安装步骤](#安装步骤)
- [已支持的数据库](#已支持的数据库)
- [版本控制](#版本控制)
- [贡献者](#贡献者)
- [作者](#作者)
- [鸣谢](#鸣谢)

### 上手指南
请先运行一次插件后,在生成的"license.yml"配置文件中的"license"修改为你的许可证,每个人只有一个许可证且绑定机械码。

### 前置要求
- 硬前置
  - [NametagEdit](https://www.spigotmc.org/resources/nametagedit.3836/)
  - [HolographicDisplays](https://dev.bukkit.org/projects/holographic-displays)
- 软前置
  - [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245)
<details>
  <summary>点击此处查看前置关系图</summary>
  <img src="https://github.com/NGat1on/DungeonsPremium/blob/main/image/depend.png" align="left" />
</details>
### 安装步骤
1.你需要在"地牢插件售后"的群文件下载"Setup服务端"<br />
2.将下载好的服务端解压至电脑,并修改插件的许可证<br />
3.修改计分板IP:"Scoreboard.yml"的server-ip<br />
4.你可以在Database.yml里修改你的存储方式[默认:YAML]

### 已支持的数据库
- ~~[MySQL](https://www.mysql.com/)~~
- [MongoDB](https://www.mongodb.com/)

### 版本控制
插件版本:1.12

### 作者
- <img src="https://img.shields.io/badge/Author-念国-orange" alt="Author" /><br>
- 邮箱 1320510756@qq.com<br>
- BiliBili:念国nation<br>
- qq:1320510756

*您也可以在贡献者名单中参看所有参与该项目的开发者。*

### 贡献者
- [白羽](http://wpa.qq.com/msgrd?v=3&uin=1326678767&site=qq&menu=yes)
- [Thegoodboy](http://wpa.qq.com/msgrd?v=3&uin=1512592535&site=qq&menu=yes)

*如果没有他们，也许这项的成就就不会存在。*

### 鸣谢
- [XingMC](http://wpa.qq.com/msgrd?v=3&uin=2603494537&site=qq&menu=yes)
- [白羽](http://wpa.qq.com/msgrd?v=3&uin=1326678767&site=qq&menu=yes)
- [GitHub](https://github.com)
- [Spigot](https://www.spigotmc.org/)
