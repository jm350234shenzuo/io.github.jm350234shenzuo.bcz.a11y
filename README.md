# 题神·百词斩

针对 **百词斩**（`com.jiongji.andriod.card`）的 LSPosed 增强模块。

- 模块包名（applicationId）：`io.github.jm350234shenzuo.bcz.a11y`
- 目标应用：`com.jiongji.andriod.card`
- 版本：1.0（versionCode 1）

## 功能
- 答题判定接管（判我对）
- 跳过题目（悬浮球 / 按钮选择器）
- 悬浮控制球与设置页
- 坐标校准（针对 Compose 答题页）

## 环境要求
- Android 7.0+（minSdk 23）
- LSPosed / EdXposed 框架

## 安装
1. 从本仓库 Releases 下载 APK 并安装；
2. 在 LSPosed 中启用「题神·百词斩」，作用域勾选 **com.jiongji.andriod.card**；
3. 强制停止目标 App（或重启手机），重新打开即可。

## 使用
打开模块自身的设置页调整选项；目标 App 内会出现悬浮控制球，可随时开关接管与跳过。

## 源码
源码与构建脚本见 https://github.com/jm350234shenzuo/tishen 的 `baicizhan-a11y/` 目录（本仓库按 LSPosed 模块仓库约定只放说明与发行包，不放源码）。

## 免责声明
本模块仅供学习与研究自动化测试使用，请勿用于违反目标 App 服务条款的用途，使用风险自负。