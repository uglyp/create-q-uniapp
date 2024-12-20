
<h1 align="center">✨create q-uniapp</h1>

## 📖 介绍

`create-q-uniapp` 是一个用于快速创建 `q-uniapp` 项目的轻量脚手架工具，它可以帮助你快速创建一个基于 `vite` + `vue3` + `TS` 的 `uni-app` 项目，同时提供了一些模板供你选择。

## 🚤 快速使用

```shell
pnpm create q-uniapp <项目名称> # 默认用 base 模板
pnpm create q-uniapp <项目名称> -t <模板名>
```

`create q-uniapp` 支持 `-t` 参数选择模板，目前已有 `6` 个模板，分别是 `base`、`demo`、`i18n`、`ucharts`、`hbx-base`、`hbx-demo`。

```sh
# VS Code 模板
pnpm create q-uniapp my-project # 默认用 base 模板
pnpm create q-uniapp my-project -t base # 基础模板
pnpm create q-uniapp my-project -t demo # 所有demo的模板(包括i18n)
pnpm create q-uniapp my-project -t i18n # 多语言模板
pnpm create q-uniapp my-project -t ucharts # 秋云图表模板

# HBuilderX 模板，方便使用 uniCloud 云开发
pnpm create q-uniapp my-project -t hbx-base # hbx的base模板
pnpm create q-uniapp my-project -t hbx-demo # hbx的demo模板，包含所有的demo
```
