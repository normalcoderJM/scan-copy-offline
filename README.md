# 扫码复制

在 Mac 上把文字变成二维码，用 iPhone 扫描后自动拷贝。两台设备可以连不同网络，也可以都离线。无需安装 Mac 应用、登录或启动服务器。

## Mac

1. 将 `index.html` 保存到 Mac，双击用浏览器打开。
2. 粘贴文字，点击「生成二维码」。
3. 直接展示二维码，或点击「保存二维码图片」。PNG 文件保存后可以反复扫描。

每张二维码最多容纳 1,800 个 UTF-8 字节，约 600 个汉字。更长的内容可以分段生成。文字保存在二维码中，生成过程在本地浏览器内完成。

## iPhone

首次在苹果自带的「快捷指令」中建立一个名为「扫码复制」的快捷指令。

1. 添加「扫描二维码或条形码」。
2. 添加「拷贝到剪贴板」，输入选择第一个动作的扫描结果。
3. 添加「显示结果」，输入也选择第一个动作的扫描结果。

以后运行这个快捷指令并对准二维码。文字会显示在屏幕上，同时拷贝到剪贴板。可将快捷指令添加到主屏幕。[苹果快捷指令设置指南](https://support.apple.com/guide/shortcuts/create-a-custom-shortcut-apd84c576f8c/ios)

## 第三方组件

`index.html` 内含 [QR Code Generator for JavaScript](https://github.com/kazuhikoarase/qrcode-generator)，版权归 Kazuhiko Arase 所有，依据 MIT 许可使用。原始版权声明保留在文件中，完整许可文本见 [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt)。
