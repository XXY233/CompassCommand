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

```

## Other Words
* if you find any bugs ,please connect me or leave a comment below
* i'm a chinese if there are grammatical error，hope you can understand:)

## contact me
* 2964361672@qq.com(China)  QQ同号
* 2964361672@outlook.com
