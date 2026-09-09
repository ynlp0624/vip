REDSecret PRO · 交付包
===================

本包含三件东西，按使用场景选：

1) REDSecret-PRO.zip  (97 KB)
   —— 完整项目：demos/tool.html + vendor/（两个 QR 库）+ README.md
   —— 解压后打开 demos/tool.html 即用（加密需在 https 或 localhost 下打开，
      直接 file:// 双击在部分手机浏览器会被禁用 crypto.subtle）

2) REDSecret-standalone.html  (389 KB)
   —— 依赖全部内联的单文件版，双击即开，离线可用，无需 vendor/

3) REDSecret-download.html  (144 KB)
   —— 一键下载页（ZIP 已 base64 内嵌），放到任何静态托管后页面内可一键下载；
      单文件直接打开也能下（走内嵌兜底）

五隐写模式：QR / LSB图片 / WAV音频 / 零宽字符 / 自动识别
三项新能力：AES-256-GCM 加密 / 任意文件 / 诱饵密钥（可否认）

全部运算在本机浏览器完成，数据不上传。
