# [![？？？](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)                   



# 简介介绍
GuiCommandBan 是一款 Gui 界面的便捷禁止世界命令插件


# 命令
|命令|说明|
|----|----|
|/CmdBan c <参数> |创建一个禁止命令的项目|
|/CmdBan e <参数> |编辑一个禁止命令的项目|
|/CmdBan list <参数> |查询所有禁止命令的项目名称|
|/CmdBan reload <参数> |重新加载配置|

# 权限
|命令|权限|
|----|----|
|/CmdBan c <参数> |GuiCommandBan.create|
|/CmdBan e <参数> |GuiCommandBan.edit|
|/CmdBan list <参数> |GuiCommandBan.list|
|/CmdBan reload <参数> |GuiCommandBan.reload|


# 配置
Config:
```
Gui:
  #界面名字
  menu_title: "&0&LGuiCommandBan"
  #配置
  default:
    material: "STAINED_GLASS_PANE"
    data: 15
    display_name: "&8"
  name:
    material: "SIGN"
    data: 0
    display_name: "&f项目名: "
  world:
    material: "COMPASS"
    data: 0
    display_name: "&f禁止世界名: "
  command:
    material: "BOOK_AND_QUILL"
    data: 0
    display_name: "&f禁止命令: "
  Permission:
    material: "NAME_TAG"
    data: 0
    display_name: "&f权限绕过: "
  Global:
    material: "TOTEM"
    data: 0
    display_name: "&f全局禁止: "
  Msg:
    material: "PAPER"
    data: 0
    display_name: "&f消息: "
  accept:
    material: "STAINED_GLASS_PANE"
    data: 13
    display_name: "&a创建"
    lore:
      - "&c▪ &7请确保菜单内容修改完整再点击创建"
  stop:
    material: "STAINED_GLASS_PANE"
    data: 14
    display_name: "&c关闭"
    lore:
      - "&c▪ &7如不需要创建请使用这个关闭否则会遗留数据"
  save:
    material: "STAINED_GLASS_PANE"
    data: 13
    display_name: "&a保存"
    lore:
      - "&c▪ &7请确保菜单内容修改完整再点击保存"
  remove:
    material: "STAINED_GLASS_PANE"
    data: 14
    display_name: "&c删除"
    lore:
      - "&c▪ &7删除当前项目"

```
# 图片

