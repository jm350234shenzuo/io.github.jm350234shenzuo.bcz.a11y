# 题神·百词斩（TiShen Baicizhan）

针对 **百词斩**（`com.jiongji.andriod.card`）的 LSPosed 增强模块，包名 `io.dsh.bcz.a11y`。

## 功能
- 答题判定接管（判我对）
- 跳过题目（悬浮球 / 按钮选择器）
- 悬浮控制球与设置页
- 坐标校准（针对 Compose 答题页）

## 环境要求
- Android 7.0+（minSdk 24）
- LSPosed / EdXposed 框架

## 安装
1. 下载本仓库 Releases 里的 APK 并安装；
2. 在 LSPosed 中启用「题神·百词斩」并勾选作用域 **com.jiongji.andriod.card**；
3. 强制停止目标 App（或重启手机），重新打开即可。

## 使用
安装后打开模块自身的设置页调整；目标 App 内会显示一个悬浮控制球，可随时开关接管与跳过。

## 源码
源码与构建脚本在 https://github.com/jm350234shenzuo/tishen 的 `baicizhan-a11y/` 目录。本仓库按 LSPosed 模块仓库约定只放说明与发行包。

## 免责声明
本模块仅用于学习与研究自动化测试，请勿用于违反目标 App 服务条款的用途，使用风险自负。