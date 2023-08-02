# Windows服务包装器使用模板

windows服务包装器可以把可执行程序包装成系统服务，
可以实现程序作为服务启动并且可以记录日志，设置停止命令等。

本项目是一个使用服务包装器的模板。项目包含四个bat脚本可以双击运行，实现服务安装卸载启动停止。包含了一个nginx的服务配置xml可以作为参考配置。

## 使用方法

1. 下载本项目并解压到任意你想要包装的程序安装目录下

2. 下载win sw的[可执行文件](https://github.com/winsw/winsw/releases/latest)重命名成 winsw.exe

3. 修改winsw.xml为你的服务配置
4. 双击`安装Service.bat`可以安装服务其余的见名知意

