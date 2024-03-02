# CompassCommand

## Introduction 
#### A Plugin for Minecraft server

* This plugin aim to line command to one item.When player act with the item,the command would be executed.
* The plugin will try to avoid player to drop the item(You can choose whether enable this)
* When player join, it will give one item to player.

## Command
```/cpcreload``` reload the config

## config File are like below:
```

# enable the plugin?
Enable: true

# set the lores,one or more lines will also be accepted
Lores:
  - "§4右键点击§e打开主菜单"
  - ""

DisplayName: "§e主菜单"

# which material the hand can act.
Material: "COMPASS"

# one of these below must be "true" otherwise the plugin will not be enabled.
LeftClick: false
RightClick: true

# when player join will check if they have had the item,if not ，then give them one.
GivePlayOnJoin: true
AllowPlayerDrop: false

# command when the item was used
# just simulating player chatting like("/"+xxx)
Command: "Menu"
# message sent to player when item was used.
CmdMessage: "§e你打开了主菜单"

```

## Other Words
* if you find any bugs ,please connect me or leave a comment below
* i'm a chinese if there are grammatical error，hope you can understand:)

## contect
* 2964361672@qq.com(China)  QQ同号
* 2964361672@outlook.com
