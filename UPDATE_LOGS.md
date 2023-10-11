# 更新日志

 ## `[v1.7] 2023-10-11`

  1. 优化了自建房的锁头指令，现在锁除了自己之外的所有头
  1. 优化发刀
  1. 补上之前被 `CSConfig` 工具吞掉的五个键位设置
    - 滚轮跳（2个）
    - 跳投
    - 切换亮度（和狙击镜虚化）
    - 切换左右手
  1. 尝试适配 `CSGod` 社区服，但暂未发现可优化的空间
    （点歌、选枪等没法优化，因为 `CFG` 是非线性阻塞的，所有指令同时生效）

 ## `[v1.6] 2023-06-18`

  1. 将 `Plain Text` 改为 `Markdown` 格式
  1. 优化 `File Path Tree`
  1. 创建 `git repo`

  ### `patch 1`
   1. 尝试修复 `github release` 路径引起的一些问题

 ## `[v1.5] 2023-03-08`

  1. 完善 `README.txt`
  1. 新增 `Update Logs.txt` 用于记录
  1. 新增 `commands.cfg` 用于储存指令
  1. 诈骗指令 `scam`（Rick-roll 整活）
  1. 按键 `V L Z X C Alt + -` 等已经统一挪到 `wumiancfg-csgo/user/binds.cfg` 内
  1. `default.cfg` 中残余的参数已经统一挪到 `wumiancfg-csgo/user/args.cfg` 内

 ## `[v1.4] 2023-02-18`

  1. 新增 `README.txt` 用于引导用户使用
  1. 新增 `args.cfg` 用于储存参数
  1. 新增 `binds.cfg` 用于储存键位
  1. 大部分参数与键位支持自定义
  1. 内置按键 `V L` 需要到 `default.cfg` 第 `13-14` 行修改
  1. 跑图按键 `Z X C Alt + -` 需要到 `wumiancfg-csgo/training/projectile.cfg` 第 `31-36` 行修改

 ## `[v1.3] 2023-01`

  1. 道具专属象限准星
  1. 左键/右键 `HUD`界面变色
  1. `V` 键切换屏幕亮度（目前档位只有 `1.6` 亮和 `2.0` 暗，自行修改 `default.cfg` 第 `13` 行）
  1. `L` 键切换左右手持枪

 ## `[v1.2] 2022-10`

  1. 人机作弊系列指令
  1. 重启指令 `recfg`
  1. 帮助指令 `cfghelp`

 ## `[v1.1] 2022-07`

  1. 跑图指令 `projectile`
  1. 呼出指令 `call` 系列（已经废弃，待翻新）
