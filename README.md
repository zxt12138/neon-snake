# 霓虹贪吃蛇 Neon Snake

一款霓虹风格的现代化贪吃蛇游戏。单个 HTML 文件，零依赖，浏览器打开即玩。

## 在线试玩

直接用浏览器打开 `index.html` 即可。也可以在仓库 **Settings → Pages** 中开启 GitHub Pages（Source 选择 main 分支根目录），即可通过网址在线游玩。

## 操作方式

| 平台 | 操作 |
|---|---|
| 电脑 | 方向键 / WASD 移动，空格暂停 / 开始，回车开始 |
| 手机 | 手指滑动屏幕控制方向 |

## 游戏特性

- 经典贪吃蛇玩法，吃到食物得 10 分
- 每 50 分自动提速一档
- 最高纪录自动保存（localStorage）
- 霓虹发光视觉效果、呼吸灯食物、渐变蛇身
- 自适应屏幕尺寸，同时适配电脑和手机

## 打包成可安装程序

同一套代码可以打包成各平台安装包：

- **Windows（exe）**：用 Electron + electron-builder 打包
- **安卓（APK）**：用 Capacitor + Android Studio 打包

详细步骤见 [docs/游戏打包与发布指南.md](docs/游戏打包与发布指南.md)

## 发布

推荐发布到 [itch.io](https://itch.io)（免费，支持直接上传 exe / apk 供玩家下载），具体操作同样见打包指南。
