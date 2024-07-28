# CompassCommand

## Introduction 
#### A Plugin for Minecraft server

* This plugin aim to line command to one item.When player act with the item,the command would be executed.
* The plugin will try to avoid player to drop the item(You can choose whether enable this)
* When player join, it will give one item to player.

## Note
* If material compass conflict with other plugins,you can change the material to clock and other materials
but do change the material to ```Watch``` if you want band the plugin with clock cause clock in bukkit api has changed to material.WATCH!

## Command
```/cpcreload``` reload the config

## config File are like below:
```

# CommandCompass beta1.2
# Auther Hachett(Waterwood)
# mc version:1.12 - 1.16
# build date 24/7/25 build version JE1.8


# ===================================================================
# NOTES:
# to reload the config tpye:/cpcreload
# only CompassCommand.reload was given or server terminal or op.
#
# when you see note"/!\"
# this means those options will only check when server is loading;
# to make these specific changes(as mentioned above) effect,you need restart server.
#
# other options' changes can take effect while cpcreload command was type.
#
# placeholderAPI is available,if you install papi and registered papi vars will take effect.
#
# 'cpcreload'重载插件,需要 CompassCommand.reload 权限
# papi变量已经支持,可选papi是否安装
# 加"/!\"标记的只能在服务器加载的时候生效，重载插件无法生效。这时候要应用更改请重启服务端。
#=====================================================================

# enable the plugin?
# /!\
Enable: true

# set the lores,one or more lines will also be accepted
Lores:
  - "§a欢迎您!%player_name%"
  - "§4右键点击§e打开主菜单"

#set the menu's name
DisplayName: "§e%server_name% 主菜单"

# which material they hand can act.
# to use item clock type: WATCH
# /!\
Material: "COMPASS"

# one of these below must be "true" otherwise it will have no effect.
LeftClick: true
RightClick: true

# when player join will check if they have had the item,if not ，then give them one.
GivePlayOnJoin: true

# whether allow play drop the item,if player drop when this set to true ,delete and create a new one to player
AllowPlayerDrop: false

# command when the item was used just simulating player chatting like("/"+xxx)
# only one command and the command must be registered
PlayerCommand: "Menu"

# command that when the item was used and server is forced to do what(!!ignore permission!!)
# not like playercommand,this command comes from server.
# Assuming the command 'open <YourMenu> <PlayerName>' is used to open the menu for the player ↓
# use like: open <YourMenu> <PlayerName> - open the menu for player .
# this option is not necessary. cause usually playercommand can open most menu plugin's menu for player
ServerCommand: ""

# message sent to player when item was used.
CmdMessage: "§e你打开了服务器主菜单"


# 以下是中文的解释
# 是否启用此插件
# /!\
#Enable: true

# 菜单的lores(就是下面的多行的文本)
#Lores:
#  - "§4右键点击§e打开主菜单"
#  - ""

#给你的菜单设置标题
#DisplayName: "§e主菜单"

#绑定的指定物品，如果要用钟表请替换成:WATCH
# /!\
#Material: "COMPASS"

# 玩家在使用绑定的物品对空气进行互动是时候触发指令绑定是哪个手
#LeftClick: false
#RightClick: true

# 在玩家登录服务器的时候是否要给一个菜单给玩家。
#GivePlayOnJoin: true

# 是否允许玩家丢出菜单
#AllowPlayerDrop: false

# 给你的菜单绑定指令，不加"/"
# 这些指令必须被注册过并且未被其他插件指令绑定过(否则可能会造成冲突)
# 实际上就相当于自动帮玩家打了一个:"/+xxx"比如如下自动帮玩家打了一个"/Menu"回车
#PlayerCommand: "Menu"

# 当玩家对绑定物品交互的时候,服务器执行的指令(不需要权限)
# 与playercommand不同,此命令来自服务器
# 通常上方的playercommand一个就行了大部分菜单插件用户都有统一的用户菜单的指令。
#ServerCommand: ""

# 当玩家使用菜单的时候对他发出的消息
#CmdMessage: "§e你打开了服务器主菜单"



```

## Other Words
* if you find any bugs ,please connect me or leave a comment below
* i'm a chinese if there are grammatical error，hope you can understand:)

## contact me
* 2964361672@qq.com(China)  QQ同号
* 2964361672@outlook.com
