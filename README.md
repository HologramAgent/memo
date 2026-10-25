# memo

待办与备忘录插件。待办（todo_add/todo_complete/todo_list）会主动提醒；备忘录（memo_create/memo_list/memo_delete）纯记事不提醒。

HologramAgent 插件，随 SDK `1.1.0` 的示例插件拆分而来。

## 构建

```bash
hmapdev build
```

产物 `dist/memo_bundle.hmap` 经 `plugin_install` 安装。

## 自动更新

本仓库地址登记在 `plg.json` 的 `repo` 字段，安装后随产物写入
`plugin.json` 的 `repository` 字段 —— 内核的 `plugin_update` 靠它
从本仓库拉最新源码并重编安装。
