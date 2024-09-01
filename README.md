# TShockInstaller
## 如何使用脚本安装TShock?
- 如果你是Window用户可以选择使用以下命令一次性安装(在pwsh中运行此命令即可)
- 此脚本仅Windows可用
```
curl -o install.ps1 https://gitee.com/kksjsj/TShockInstaller/raw/master/InstallTShock.ps1
powershell -ExecutionPolicy ByPass -File ./install.ps1 -verb runas
```
