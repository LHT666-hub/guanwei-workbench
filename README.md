# 观微 · 人文社科研究工作台

本地优先的文献整理、PDF阅读批注、研究证据和写作工作台。当前提供开发测试版，尚不是正式稳定版。

## 直接下载 beta.63

**[下载 Windows x64 测试版](https://github.com/LHT666-hub/guanwei-workbench/releases/download/v0.38.0-beta.63/Guanwei-0.38.0-beta.63-Windows-x64.zip)**

**[下载 Mac Apple芯片测试版](https://github.com/LHT666-hub/guanwei-workbench/releases/download/v0.38.0-beta.63/Guanwei-0.38.0-beta.63-mac-arm64.zip)**

[发布说明及SHA256校验文件](https://github.com/LHT666-hub/guanwei-workbench/releases/tag/v0.38.0-beta.63)

完整解压所有文件。Windows双击 `Start-Team-Test.cmd`；Mac双击 `Start-Mac-Test.command`。不需要Node或源码，使用独立测试资料库。

## 本轮新功能

- 先选文字高亮和颜色，再拖选文字即可连续标记；再次点击或Esc退出。
- 8种颜色和自定义颜色，扫描PDF可使用区域高亮。
- 自由画笔与线宽、可编辑和拖动的页面文本框、整条擦除的橡皮。
- 工具栏撤销标记，保存重开及分享包保留页面标记。
- 包含近期窗口缩放、工具栏和首页改进。

标记保存在工作台及资料分享包中，不改写原始PDF；普通PDF带标记导出尚未实现。共享新页面标记要求双方都使用beta.63或后续支持分享格式v6的版本。

## 跨网络联机测试

Windows使用手机热点，Mac保持另一条网络。双方保持程序打开，进入「资料分享 → 团队知识库」，私下交换邀请及申请连接码，由管理员明确确认授权。

只用包内 `field-test/Synthetic-Team-Test.pdf` 验证全文、批注、管理员汇总发布、自动接收、离线补收和本地修改保护。

运行后生成的 `field-test/windows-profile`、`field-test/mac-profile` 含设备身份，**不要上传或转发**。发布包不包含这些目录或真实研究材料；不要删除旧测试目录里的profile来升级。

当前Mac成品已完成本轮标注操作检查；Windows真实运行和不同物理网络联机仍需现场验证。旧beta.7只保留在历史发布中，不含本轮阅读器工具。
