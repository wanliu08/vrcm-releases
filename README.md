# vrcm 发布仓库

Android 客户端 **vrcm** 的发布产物（APK + 应用内更新清单）。

## 给 App 用的更新地址（固定，永远指向最新版本）

`
https://github.com/wanliu08/vrcm-releases/releases/latest/download/manifest.json
`

把上面这行填进 App 的 **设置 → 更新 → 更新清单地址**，以后每次发版都不用改。

## 每个 Release 包含

| 文件 | 说明 |
|---|---|
| rcm-x.y.z.apk | 安装包 |
| manifest.json | 更新清单（版本号、APK 地址、更新说明） |

## manifest.json 格式

``json
{
  "version": "0.11.2",
  "versionCode": 23,
  "url": "https://github.com/wanliu08/vrcm-releases/releases/download/v0.11.2/vrcm-0.11.2.apk",
  "notes": "更新内容"
}
``