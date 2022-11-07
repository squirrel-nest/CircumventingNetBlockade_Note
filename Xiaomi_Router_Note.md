# R2100
## 参考
  * [小米AX3600路由器开启SSH，装上Clash小猫咪🐱比软路由还好用？](https://www.youtube.com/watch?v=V_3lMAvxLvQ)
  * [小米路由器科学上网，一行代码 30S 搞定，一键自动Breed，安装老毛子Padavan固件！支持V2ray✚Clash 👉《真 ◆全局》科学上网，新手也能 100%成功](https://www.youtube.com/watch?v=jBaMRhda4Dk)
## Clash 安装 与 配置
  * 密码管理 - 不能用 简单的密码
  * 固件升级
    + 根据系统管理- 固件升级 - 提示 操作 即可
  * SSH 的 开启
    + ssh admin@192.168.***.1 --》 输入密码
    + ...
  * 安装 ShellClash
    + ...
  * 上传 yaml 配置文件
    + sftp 的 简单用法 - `是 linux 的 命令 ftp 的 改进版。。。`
      - 登录远程主机 - 【连接到 远程 目标 路由器】
        * sftp username@remote_hostname_or_IP  - sftp admin@192.168.123.1
      - 查询帮助手册
        * help  或 ？
      + 在 远程主机上的操作
        * 与 linux 操作 完全一致
        * 基本命令 - 例子
          + ```
                //远程主机上的操作  
                pwd  
                ls  
                cd
            ```
      + 在 本地主机上的操作  
        * 在 远程主机命令的区别，就是 要在 命令 之前 夹 一个 字母 l - 代表 local 【本地】 的 意思
          + ```
                //本地主机上的操作  
                lpwd  
                lls  
                lcd 
            ```
        * 还有一个通用的法则，在命令前面加一个！表示命令在本地主机上执行，即：用 ！ 代替 l 字母，也是表示 在本地操作的意思
          + ```
                //在远程主机上执行  
                vim test.sh  
                //在本地主机上执行  
                !vim test.sh  
            ```
      + 从远程主机下载文件
        * ```
              //下载到本机主机当前目录，并且文件名与remoteFile相同  
              get remoteFile  
                
              //下载到本机主机当前目录，并且文件名改为localFile  
              get remoteFile localFile  
          ```
      + 从远程主机下载一个目录及其内容
        * ```
              get -r someDirectory  
          ```
      + 上传文件到远程主机的当前目录
        * ```
              //上传本机主机当前目录的文件到远程主机当前目录，并且文件名与 localFile 相同  
              put localFile
              
              //上传本机主机当前目录的文件到远程主机当前目录，并且文件名改为 remoteFile  
              put localFile remoteFile
          ```
      + 上传目录到远程主机的当前目录
        * ```
              //上传本机主机当前目录的文件到远程主机当前目录，并且目录名与 localDirectory 相同
              put -r localDirectory
          ```
          
      + 退出sftp
        * exit
  * 更名 上传的 文件为 config.yaml,需要更改吗？
