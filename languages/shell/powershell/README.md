# powershell

* Set-ExecutionPolicy

  * Restricted——默认的设置， 不允许任何script运行

  * AllSigned——只能运行经过数字证书签名的script

  * RemoteSigned——运行本地的script不需要数字签名，但是运行从网络上下载的script就必须要有数字签名

  * Unrestricted——允许所有的script运行

* cd

  * `cd /`进入根目录

* ls

  * `ls *\*` 查看二层目录

  * `ls *\*\*` 查看三层目录
  * `ls env:` 查看环境变量

* tree

* md

* start . 打开当前文件夹
* $env: 设置环境变量
  * `$env:name=path`


### powershell默认位置

`C:\Users\Default\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Windows PowerShell\Windows PowerShell.lnk`

`C:\Windows\System32\WindowsPowerShell\v1.0\Windows PowerShell.exe`

### 修改powershell起始路径

在快捷图标里的起始位置修改路径

执行`$Profile`查看powershell脚本存放的路径，如果WindowsPowerShell文件夹不存在，需要新建，然后执行`echo "Set-Location D:\" > $Profile`

### 快速打开程序

1. 查看快捷图标的属性，找到文件目录
2. 复制当前路径，添加到环境变量path
3. 输入程序名，就能快速打开程序


## 修改windows mac地址

1. 查看mac地址，在powershell输入ipconfig /all

2. 找到控制面板\网络和 Internet\网络连接\属性\配置\高级\属性，查看是否有mac地址修改选项，如果没有需要修改注册表

3. 打开注册表\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Class\{4d36e972-e325-11ce-bfc1-08002be10318}，查看0001等类子项的DriverDesc值哪个符合自己的网卡，然后在这个子项里添加一个字符串（命名为NetworkAddress，值是自定义mac地址）

4. 继续在这个子项里新建名为NetworkAddress的子项，然后在新子项里添加一个字符串（命名为default，值是自定义mac地址）和另一个字符串（命名为ParamDesc，值是'MAC Address'）

5. 禁用适配器，然后重启


