<p align="center">
  <a href="https://v2.nonebot.dev/"><img src="https://v2.nonebot.dev/logo.png" width="200" height="200" alt="nonebot"></a>
</p>

<div align="center">
  
# Nonebot_Plugin_Jrrp2
  
_✨ 基于OneBot适配器的[NoneBot2](https://v2.nonebot.dev/)每日人品插件 ✨_
_添加了基于sqlite数据库的历史查询功能_
  
</div>

## 功能

- 每天查询今日人品
- 查询本周获取人品次数，查询本周人品指数
- 查询本月获取人品次数，查询本月人品指数
- 查询历史获取人品次数，查询历史平均运势
- 未来可能还会添加pk排行功能，敬请期待

## 安装

- 使用 nb-cli

```
nb plugin install nonebot_plugin_jrrp2
```

- 使用 pip

```
pip install nonebot_plugin_jrrp2
```

## 数据库
本插件使用sqlite作为数据库来保存历史查询数据    
保存位置为/data/jrrp2/jrrpdata.db


## 指令

使用以下指令触发

```
/jrrp获取你的今日人品（命令别称：`jp`，`今日人品`，`今日运势`）
/weekjrrp获取你的本周平均人品（命令别称：`本周人品`，`本周运势`，`周运势`）
/monthjrrp获取你的本月平均人品（命令别称：`本月人品`，`本月运势`，`月运势`）
/alljrrp获取你的历史平均人品（命令别称：`历史人品`，`平均人品`，`平均运势`）
```