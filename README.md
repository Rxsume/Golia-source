# Golia 私人源

全能签 / 轻松签 / ESign 软件源，GitHub Pages 静态托管，零后端。

## 在全能签里添加

打开全能签 → 软件源 → 添加，粘贴下面任一地址：

**GitHub Pages（推荐）：**

```
https://rxsume.github.io/Golia-source/apps.json
```

**Raw 直链（备用）：**

```
https://raw.githubusercontent.com/Rxsume/Golia-source/main/apps.json
```

添加后列表里出现 Golia，点下载 → 用自己的证书签名安装。

## 当前收录

| App | 版本 | 包名 | 下载 |
| --- | --- | --- | --- |
| Golia | 0.7.28-lx9 | top.izuna.goliaios | [Folia_0.7.28-lx9.ipa](https://github.com/Rxsume/Golia/releases/download/v0.7.28-lx9/Folia_0.7.28-lx9.ipa) |

IPA 不放在本仓库，直接引用 `Rxsume/Golia` Release 的永久下载地址。

## 更新新版

1. 在 `Rxsume/Golia` 发新版 Release，拿到新的 `releases/download/...` 直链
2. 改本仓库 `apps.json` 里的 `version`、`versionDate`、`size`、`downloadURL`
3. 提交后全能签里下拉刷新源即可看到新版

## 格式

ESign / AltStore 兼容格式：顶层 `name` + `identifier` + `apps` 数组，每项必需 `name`、`bundleIdentifier`、`version`、`downloadURL`。
