# HXBot 测试包

这个仓库只有一个打包流程（`.github/workflows/hxbot-build.yml`），没有产品代码。每次运行用只读令牌从私有仓库取代码，
在 GitHub 的 Mac、Windows、Linux 机器上打测试包，并在 Mac、Windows 机器和安卓模拟器上查系统显示的图标。

- 只能由仓库的管理员手动运行（Actions → HXBot public build → Run workflow）。
- 打出来的是测试包：Mac 包不签名，安卓包用临时签名，都不能发布。安装包在运行页面上只留 1 天。
- 产品的许可证：PolyForm Noncommercial 1.0.0。
