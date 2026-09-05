# DeepSeek Harness Desktop

> 非官方项目：基于开源 DeepSeek Harness（dsh）的社区 Windows 桌面外壳，与 DeepSeek 官方无隶属关系。

双击即用的 DeepSeek Harness 桌面端：内置官方内核与运行时，免安装 Node、免命令行。

- 开箱即用：双击即开、自动起服务、退出自动关干净（无残留后台进程）
- 出厂预装：任务看板（task-board）+ 插件市场（dshmarket）
- 数据安全：会话/配置存于 ~/.dsh，升级重装不丢
- 中文报错兜底：启动失败给原因 + 「查看日志 / 重试」
- Windows 10 (1809+) / Windows 11

## 下载

到右侧 Releases 下载最新版安装包：

| 文件 | 说明 |
|---|---|
| DeepSeek-Harness-Desktop-Setup-版本.exe | 安装版（推荐） |
| DeepSeek-Harness-Desktop-版本-portable.exe | 便携版（免安装，解压即用） |

> 安装包未签名：首次运行若出现 SmartScreen / 杀软提示「未知发布者」属正常现象——请确认来源为本仓库后选择「更多信息 → 仍要运行」。

## 数据在哪里

- 会话 / 配置 / 插件：~/.dsh（即 C:\Users\<你>\.dsh）
- 想彻底卸载：用安装版自带的卸载入口即可，不会动 ~/.dsh

## 说明

- 本仓库仅作安装包发布通道，不含源码。
- 插件市场第三方插件常滞后于内核（dsh 一个插件加载失败会拖垮整个启动）；本外壳内置「插件哨兵 + 自愈 + 兼容矩阵」三层防线，尽量让你装了不兼容插件也不受影响。
