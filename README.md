<div align="center"></div>
<h1 align="center">BetterQQNT</h1>
<h4 align="center">Electron 客户端插件管理器</h4>

BetterUniverse for QQNT/Electron ( 下文简称 BetterQQNT )。

由于可预期的 QQNT 安全性更新，BetterQQNT 将最早在第一个 QQNT For Windows 正式版（无白名单版本）推出后开源。

目前此仓库仅作文档及版本发布用。

BetterQQNT 仅为优化 QQ 和其他 Electron 应用的使用体验而生，**如有侵权，请联系我们删除**。

此项目感谢所有 bqqnt-dev 成员的协助。

# 注意
BetterQQNT 不保证在所有版本上的通用可用性，也不保证安全性（封号，崩溃等）。

在使用此插件后所遇到的 Bug，崩溃等，请**不要**向官方反馈，而应在此 Repo 下发送 Issue。

请**不要**在官方群聊等内提及，甚至 “炫耀” 此插件。

请**不要**发送视频，帖子等来宣传此插件。

BetterQQNT 可能将于未来的某一天突然跑路。

频道：https://t.me/betterqqnt

讨论组同

# 功能
  - [Koishi 机器人](https://github.com/koishijs/koishi)
  - 主题
  - RedProtocol 机器人协议
  - 自动执行 Pangu.js
  - 加密通话（假）【发送 enc#+文本】
  - 防撤回
  - 直接打开小程序对应网页（部分兼容）
  - 自动分类下载的群文件
  - 置顶聊天窗口
  - 亚克力效果
  - WIP……

  画个饼：
  - 消息一键跳转（到上条未读，在 at 间切换等等）
  - 更多的主题
  - +1 按钮


# 预览

![image](https://github.com/bqqnt-dev/BetterQQNT/assets/135465054/75518115-1bfa-4321-bf63-6e1bdb925def)

![image](https://github.com/bqqnt-dev/BetterQQNT/assets/135465054/c247d216-fc8b-4fd4-af21-04e5154bf3b0)

![image](https://github.com/bqqnt-dev/BetterQQNT/assets/135465054/a1fc3ef3-fdfb-43c2-8866-162059f2893f)

![image](https://github.com/BetterQQNT/BetterQQNT/assets/66859419/0057c818-a4ed-4266-a1eb-e779cdfeee8b)

# 安装
### 手动安装

### 使用 BetterQQNT-Launcher
两种方式：
- 在 Koishi 中安装插件 `qq-launcher` 并启用
- 直接在 [BetterQQNT-Launcher](https://github.com/BetterQQNT/BetterQQNT-Launcher) Release 中下载并打开 bqqenv.exe


#### （仅 x86）
将 `better-qqnt.dll` 重命名为 `version.dll` 并放入 QQNT 安装文件夹。

### 使用 BetterUniversal-Installer
施工中

# 协议安全风险

如你所见，此插件的一个功能为 RedProtocol 机器人协议。
此协议将允许机器人框架程序化操纵 Electron 应用并发送消息。
此协议在第一次使用时将会生成一个 token，并使用此 token 来完成鉴权。
请不要泄露此 token。
导致账号胡乱发送消息甚至封号后果自负。

你可以选择不启用此功能。

# 跨平台？
BetterQQNT 的 Linux 编译版本依然在 segfault 中，由于 Linux 兼容的优先级较低，该 Bug 可能会在第一个正式版前被修复，然后 Linux 编译版本将会被发布。

MacOSX 由于过于麻烦，在可预期的未来内不会被支持。


# 关于开发工具

在安装 BetterQQNT 后，可以按 F12 打开前端 DevTools。

由于 API 仍处于极不稳定的状态，插件文档暂未对外开放。

如想参与开发请与我们联系。

已实现的开发功能：

- 自定义 RPC Call
- 高级 JS 反射
- IPC Processors 处理标准
- 双端调试器
- 任意上下文代码执行
- ……

![image](https://github.com/BetterQQNT/BetterQQNT/assets/66859419/17ee6805-0422-4568-a865-d1dfb23d408f)
