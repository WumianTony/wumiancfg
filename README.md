# **注意事项**

## **本 CFG 配置文件由 Wumian_Tony 编写，欢迎交流但禁止商用**
## **唯一[下载链接](https://bjea.lanzouo.com/csgocfg) `https://bjea.lanzouo.com/csgocfg` 防伪**
## **务必按照下方[`[配置说明]`](#1-配置说明)，录入自己的参数，否则会同步成我的参数**

---

## 1 配置说明：
你需要对 `user` 文件夹内的两个文件进行修改，其他文件能看懂也可以改  
1. `args.cfg` 是个人参数，包括准星、鼠标、画面等诸多设置  
    你需要将你的个人参数录入进来  
    *游戏内打开控制台，输入对应参数，系统会告诉你你这项参数的值*
2. `binds.cfg` 是绑定的按键，包括 `WSAD`、一键跳投、滚轮跳等各种按键  
    你需要将你的按键录入进来  
    *游戏内打开控制台，输入 `key_listboundkeys` 查看你已绑定的按键*
3. `commands.cfg` 是中枢指令，请谨慎修改  
    如果你想更换某一条指令，可以改紧随 `alias` 指令的第一个字符串  
    *不建议修改，除非你明白自己在干什么*

## 2 自启动说明：
你需要找到 `Counter-Strike Global Offensive\csgo\cfg` 目录下的 `autoexec.cfg`  
加入这行指令  
```cfg
exec custom/default
```
如果不希望自启动，需要每次启动后使用一次指令

## 3 简单控制台指令普及：  
|指令|功能|
|:-|:-|
|`recfg`|重启配置文件（修改配置之后 / 配置错乱时使用）|
|`cfghelp`|帮助列表|

---
## [附录1] [更新日志](https://github.com/WumianTony/custom/blob/main/UPDATE_LOGS.md)

## [附录2] 项目内容（目录树）
```FPT
.
│  default.cfg          @ 中控配置 (等效于 main 函数)
│  help.cfg             . 帮助指令
│  README.md            . Read Me Markdown 文件
│  tree.bash            . File Path Tree 脚本
│  UPDATE_LOGS.md       . 更新日志 Markdown 文件
│
├─ call                 # 呼出游戏内聊天（暂时废弃）
│      anubis.cfg           X 已废弃
│      bug_molly.cfg        X 已废弃（22年12月 bug火失效）
│      scam.cfg             . 诈骗信息 Rick-roll
│
├─ hack                 # 自建房，需要 Host 权限
│      antibhop.cfg         . 禁用空格连跳
│      antigyro.cfg         . 禁用陀螺
│      antilock.cfg         . 禁用锁头（仅对机器人）
│      antixray.cfg         . 禁用模型透视
│      bunnyhop.cfg         . 启用空格连跳
│      enable-recoil.cfg    . 启用精准弹道
│      gyro.cfg             . 启用陀螺
│      high-speed.cfg       . 启用时间轴加速
│      hitbox.cfg           . 启用地形碰撞箱渲染
│      knife.cfg            . 发一把蝴蝶刀（模型）
│      lock.cfg             . 启用锁头（仅对机器人）
│      low-speed.cfg        . 禁用时间轴加速
│      no-hitbox.cfg        . 禁用地形碰撞箱渲染
│      no-knife.cfg         . 禁用发刀
│      no-radar.cfg         . 禁用全图雷达
│      norecoil.cfg         . 禁用精准弹道
│      radar.cfg            . 启用全图雷达
│      xray.cfg             . 启用模型透视
│
├─ training             # 训练用的配置
│      clutch.cfg           X 残局（还没调通）
│      hell.cfg             . 全经济
│      projectile.cfg       . 跑图 / 道具
│
└─ user                 # 用户的配置
       args.cfg             $ 游戏内参数，需要用户 DIY
       binds.cfg            $ 游戏内键位，需要用户 DIY
       commands.cfg         . 指令（请勿修改，除非你清除你在做什么）
```