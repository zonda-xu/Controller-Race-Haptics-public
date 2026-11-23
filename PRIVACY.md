# Controller Race Haptics

[简体中文](#隐私政策) · [English](#privacy-policy)

## 隐私政策

发布者：Jerry Zonda · 适用版本：Windows 版 1.0.0 · 更新日期：2026 年 11 月 23 日

Controller Race Haptics（CRH）在你的电脑上将赛车模拟器的驾驶数据转换为手柄反馈。使用基础功能无需注册 CRH 账号。CRH 不向开发者上传驾驶记录、Windows 账号标识或游戏车手标识，也不内置广告、行为分析或自动向开发者报告崩溃的服务。

### 本机读取哪些信息

CRH 从所选游戏的本地遥测接口读取可用的车辆、赛道、会话、踏板、车速和车轮状态，用于计算扳机、握把及音圈反馈。在 iRacing 中，应用读取当前车手的用户 ID；在 rFactor 2 中，应用读取游戏报告的当前车手名称。这些字段帮助应用识别换人或会话变化，避免沿用上一位车手的制动学习状态。

启动时，CRH 使用当前 Windows 用户的安全标识符（SID），取不到时使用 Windows 用户名，以防同一用户重复运行应用。为连接手柄，CRH 读取 Windows 提供的设备名称、设备标识、连接接口、振动能力和音频输出端点信息。音频输出用于驱动手柄音圈，不使用麦克风录音。

### 本机保存和删除

实时驾驶数据和用于区分车手的标识在内存中处理。退出 CRH 即停止应用读取游戏和设备。游戏选择、语言、触觉偏好、手动选择的音频输出端点和车型配置可以保存在当前 Windows 用户的应用数据目录；保存车型配置时可能生成备份。配置使用 JSON 或文本文件，并受所在目录的 Windows 文件权限保护。

你可以在应用内查看或修改设置。若要清除本机配置，先退出 CRH，再从当前用户的应用数据中删除 `ControllerRaceHaptics` 配置目录及其中的备份。商店安装版的目录可能位于该应用包的专用数据位置。你主动导出的配置文件保存在选择的位置，可单独查看、分享或删除。CRH 不会自动发布这些文件。

### 商店内购

CRH 通过 Microsoft Store 查询 Pro 商品价格和当前商店账号的购买授权。购买或恢复购买时，应用读取商品标识、交易结果、授权状态和适用的到期信息，以启用对应游戏的功能。Microsoft 处理商店账号和付款，CRH 不接收你的账号密码或银行卡号。删除本机配置不会取消已购权益。商店交易数据的处理方式见 [Microsoft 隐私声明](https://privacy.microsoft.com/zh-cn/privacystatement)。

### 联系开发者

有关 CRH 的一般问题或功能建议，请使用 [CRH 项目反馈区](https://github.com/zonda-xu/Controller-Race-Haptics-public/issues)。如需查阅、更正或删除你曾主动提供给开发者的资料，请使用 Microsoft Store 应用页面列出的支持方式联系 Jerry Zonda，或先在项目反馈区索取私下联系方式。反馈区对所有人公开，请勿张贴订单号、账号标识或含个人资料的截图。

通过 GitHub 阅读本政策或提交反馈时，GitHub 根据自己的隐私声明处理网站访问及账号相关信息。CRH 不会把本机驾驶数据发送到项目反馈区。详情见 [GitHub 隐私声明](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)。

## Privacy Policy

Publisher: Jerry Zonda · Applies to version 1.0.0 for Windows · Last updated November 23, 2026

Controller Race Haptics (CRH) turns racing simulator data into controller feedback on your PC. You can use the free features without a CRH account. CRH does not upload driving records, Windows account identifiers or in-game driver identifiers to the developer. It includes no advertising, behavioral analytics or automatic crash reporting to the developer.

### Information used on your PC

CRH reads available vehicle, track, session, pedal, speed and wheel data from the selected simulator’s local telemetry interface to calculate trigger, grip and voice-coil feedback. In iRacing it reads the current driver’s user ID. In rFactor 2 it reads the current driver name supplied by the game. These fields help CRH detect driver or session changes so that it can reset the previous driver’s learned braking state.

On startup, CRH uses your Windows security identifier (SID), or your Windows username if the SID is unavailable, to prevent two copies from running for the same user. To connect a controller, it reads device names and identifiers, connection interfaces, vibration capabilities and audio output endpoint information provided by Windows. Audio output drives the controller’s voice coils. CRH does not record microphone audio.

### Local storage and deletion

CRH processes live driving data and driver identifiers in memory. Exiting CRH stops it from reading game and device data. It can save your game selection, language, haptic preferences, manually selected audio output endpoint and vehicle profiles in your Windows user account’s application data folder. Saving a profile can create a backup. Settings are stored as JSON or text files and are protected by the Windows file permissions on the folder.

You can review or change settings in the app. To erase local settings, exit CRH and delete its `ControllerRaceHaptics` settings directory, including its backups, from your user account’s application data. The Store edition may use a private data location for the app package. Files you choose to export are saved where you select. You control whether to inspect, share or delete them. CRH does not publish them automatically.

### Microsoft Store purchases

CRH uses Microsoft Store to look up Pro prices and entitlements for the current Store account. When you purchase or restore a purchase, CRH reads product identifiers, the transaction outcome, license status and any applicable expiry to enable features for that game. Microsoft handles Store accounts and payments. CRH does not receive your account password or card number. Clearing local settings does not cancel your purchases. See the [Microsoft Privacy Statement](https://privacy.microsoft.com/en-us/privacystatement) for how Microsoft handles Store transaction data.

### Contact

For general CRH questions or feature requests, use the [CRH project issue tracker](https://github.com/zonda-xu/Controller-Race-Haptics-public/issues). To request access to, correction of or deletion of information you previously provided to the developer, contact Jerry Zonda through the support channel on the Microsoft Store listing, or ask in the project tracker for a private way to get in touch. Posts are public. Keep order numbers, account identifiers and screenshots containing personal details out of public issues.

When you read this policy or submit feedback through GitHub, GitHub processes website access and account information under its own privacy statement. CRH does not send on-device driving data to the issue tracker. See the [GitHub General Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
