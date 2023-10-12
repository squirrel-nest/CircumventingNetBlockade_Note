如果哪些 过时 了，就舍弃。。。
# 旧版本在：[huarui0/ProxyKnack_Note](https://github.com/huarui0/ProxyKnack_Note/tree/master)
## Cloudflare WARP - 目前以 这个 作为 主要 工具， Clash Pro 作为 辅助
   * <details open>
         <summary>
             ✨ Cloudflare WARP  的 安装 与 设置
         </summary>
         <ul style="disc">
             <details open>
                 <summary>
                     ✨ 参考
                 </summary>
                 <ul>
                     <li> 【机会不多】大厂VPN终极玩法！获取team帐户zero trust，配制文件到所有平台！利用clouflarer强大工具warp实现网络代理！配合Wareguard使用完美（WARP第三期） <a href="https://www.youtube.com/watch?v=fGTtiG2sIvU&t=589s">YouTube</a></li>
                     <li> 软路由openwrt+openclash配置Cloudflare WARP <a href="https://www.youtube.com/watch?v=viqLCciet-c">YouTube</a></li>
                 </ul>
             </details>
             <details open>
                 <summary>
                     ✨ Cloudflare WARP  的 安装
                 </summary>
                 <ul>
                     <details open>
                         <summary>
                             ✨ 步骤
                         </summary>
                         <ol type="1">
                             <li> - </li>
                             <li> - </li>
                             <li> - </li>
                         </ol>
                     </details>
                 </ul>
             </details>
         </ul>
     </details>

----

## Clash 及 Clash Pro 相关 工具 - Clash Pro 为主
   * <details open>
         <summary>
             ✨  <i><b>Clashx Pro 的 安装 及 设置</b></i>
         </summary>
         <ul style="disc">
             <li>
                 <details open>
                     <summary>
                         ✨ 下载
                     </summary>
                     <ol type="1">
                         <li> <a href="https://github.com/yichengchen/clashX/releases">ClashX 下载地址</a> </li>
                         <li> <a href="https://install.appcenter.ms/users/clashx/apps/clashx-pro/distribution_groups/public">ClashX Pro 下载地址： Appcenter</a> </li>
                     </ol>
                 </details>
             </li>
             <li>
                 <details open>
                     <summary>
                         ✨ 教程
                     </summary>
                     <ol type="1">
                         <li> <a href="https://www.mac52ipod.cn/post/apple-mac-macos-shadowsocks-client-app-clashx.php">Mac技巧之苹果电脑 macOS 系统上开源免费的 shadowsocks 客户端软件：ClashX</a> </li>
                         <li> <a href="https://merlinblog.xyz/wiki/ClashX.html">ClashX教程 | macOS上好看又好用的科学上网工具</a> </li>
                         <li> <a href="https://www.youtube.com/watch?v=ipwsiG03W6g">苹果电脑翻墙软件：ClashX MAC使用教程，一款在MAC电脑上非常好用的翻墙软件，支持SSR/V2ray/Trojan节点，mac os 翻墙vpn下载（cc字幕）</a> </li>
                         <li> <a href="https://github.com/yichengchen/clashX/pull/827">Add support for AppleScript #827</a> </li>
                     </ol>
                 </details>
             </li>
             <li>
                 <details open>
                     <summary>
                         ✨ 1.91.1 Release 说明
                     </summary>
                     <ol type="1">
                         <li>升级 Clash Core 到 1.10, 支持snell v3, PROCESS-PATH规则，查看Clash Release Note 获取详细信息。</li>
                         <li>支持使用 AppleScript 切换代理模式</li>
                         <li>修复开机启动选项在某些状态不生效的问题</li>
                         <li>修复10.13系统支持</li>
                         <li>
                             <details open>
                                 <summary>
                                     ✨ Apple Script 使用方法
                                 </summary>
                                 <ul style="disc">
                                     <li>在左上角的菜单栏中选择"Settings..."（首选项）选项；</li>
                                     <li>tell application "ClashX" to toggleProxy // 切换代理开关</li>
                                     <li>tell application "ClashX" to proxyMode "direct" // 切换代理模式</li>
                                     <li>tell application "ClashX" to proxyMode "global"</li>
                                     <li>tell application "ClashX" to proxyMode "rule"</li>
                                 </ul>
                             </details>
                         </li>
                         <li>ClashX Pro 集成premium core，提供增强模式(tun)，rule set等特性支持，</li>
                     </ol>
                 </details>
             </li>
         </ul>
     </details>
----
## 一下不用考虑了。。。
   * Clash 的 安装 与 配置
      + 下载地址
         - Github项目地址： --> [https://github.com/Dreamacro/clash/releases](https://github.com/Dreamacro/clash/releases)<br>
      + 详见
         - 👀 [https://github.com/squirrel-nest/CircumventingNetBlockadeNote/blob/master/MacOS_ProxyNote.md](https://github.com/squirrel-nest/CircumventingNetBlockadeNote/blob/master/MacOS_ProxyNote.md)<br>
      + 安装 --> 详见：[]()<br>
         - ```brew search Clash```
         - ``` brew install clashx-pro --cask```
         - ``` brew install clashx --cask``` ```可选```
         - ``` brew install clash-for-win --cask``` ```可选```
      + 更新
        - `brew upgrade clashx-pro --cask`
      + 设置 步骤
         - Change default system ignore list. --><br> [Change default system ignore list.](https://github.com/yichengchen/clashX#change-default-system-ignore-list)<br> --> [设置例子](https://github.com/yichengchen/clashX/blob/master/proxyIgnoreList.plist)<br>
      + 代理端口
         - 查询入口
           * 弹出窗口 》Help 》Ports
             + Socks5 端口（默认）：```7890```
             + Http端口（默认）：```7890```
         - 备注：Proxyfier的代理设置需要根据以上端口设置。。。
         - Zoom 不知为何，不能设置为 新加坡区 和 香港区，其他都可以。。。



      
   * V2rayU 的 安装 与 配置
      + 参考
         - https://yanue.github.io/V2rayU/
         - <details open>
               <summary>
                 About
               </summary>
               V2rayU 是一款v2ray mac客户端,用于科学上网,使用swift4.2编写,基于v2ray项目,支持vmess,shadowsocks,socks5等服务协议(推荐搭建v2ray服务,可伪装成正常网站,防封锁), 支持二维码,剪贴板导入,手动配置,二维码分享等, 支持订阅, 项目地址: https://github.com/yanue/V2rayU
           </details>
      + 下载： 不用下载 ```brew``` 即可--> [https://github.com/yanue/V2rayU](https://github.com/yanue/V2rayU)<br>
      + 说明：如果 ```Clash Pro``` 无法 ```VPN```，则尝试 V2rayU
      + 安装 ```brew install v2rayu --cask``` ```brew info v2rayu --cask```

   * Proxifier 的 安装 与 设置
      + 参考
         - https://www.cnblogs.com/itachilee/p/14202469.html
         - mac电脑上安装使用Proxifier代理客户端 --><br>
           [https://www.lapulace.com/IProxifier.html](https://www.lapulace.com/IProxifier.html)<br>
         - https://github.com/csujedihy/proximac -- 一个类似的代理app，未验证。
      + 安装，
         - 统一用 brew cask 安装
      + 注册
         - mac v3激活码：```3CWNN-WYTP4-SD83W-ASDFR-84KEA```
         - 打开 App
         - 输入用户名：Jenny，粘贴注册码，即可。
         - 附带：window的 注册码
           ``````
           ``````
           ``````
         - 粘贴注册码，即可。
      + 第一次打开，提示：System Blocked，设置为允许。。即可。 
      + 设置
         - 参考
            * 超详细教程 : 如何在国内实现YouTube直播 (OBS Studio + Proxifier)？ -->
              [https://www.youtube.com/watch?v=jOk-K5CFCqU](https://www.youtube.com/watch?v=jOk-K5CFCqU)<br>
         - 设置说明
            * VPN代理使用Clash Pro，其 Sockets5 端口设置为 7890
         - 设置
            * Proxies 设置
               + 设置入口
               + 设置内容
                  1. 点击 ```Add...``` 按钮， 打开设置界面
                  2. Server Address 设置为 ```127.0.0.1```， 
                     * ClashX Pro，则：Port 设置为 ```7890```
                     * Windows下的 WinXRay，端口：Sockets：1080，Https：1081
                     * 如果是其他，需要查 端口 的 设置信息
                  4. Protocol 选项 选取 SOCKS Version 5
                  5. Authentication 不用设置 🈚
            * Rule 设置
               + 设置入口
               + 设置内容
                  1. 点击 ```Add...``` 按钮， 打开设置界面
                  2. ```Name``` 设置为要使用全局代理的 App 名称，便于设别， ```Enabled``` 选项 ✅
                  3. ```Applications``` 设置，点击 ```+```按钮，然后，选择要代理的 App
                  4. 其他暂不选择。。。
                  5. ```Acction```选择 ```Proxies``` 中设置的 代理
                  6. 最后，点击 ```Save```，保存。

## Clash for MacOS
### Clash for Windows for MacOS - Clash for Windows for Mac 是 Clash for Windows 作者的另一款作品。
   * 参考
      + 文档位置 --> [https://github.com/Fndroid/clash-win-docs-new](https://github.com/Fndroid/clash-win-docs-new)<br>
      + Install and configure clash in Linux to realize proxy Internet access --> [https://cdmana.com/2021/05/20210503053352540i.html](https://cdmana.com/2021/05/20210503053352540i.html)<br>
      + Clash for Mac教程 --> [https://help.loliloli.live/jiao-cheng/untitled-1/clash-for-mac](https://help.loliloli.live/jiao-cheng/untitled-1/clash-for-mac)<br>
   * 下载安装
      - ① Github项目地址： --> [https://github.com/Fndroid/clash_for_windows_pkg/releases](https://github.com/Fndroid/clash_for_windows_pkg/releases)<br>
      - 步骤
         1. 打开下载完成的 dmg 映像文件，将 Clash for Windows 添加到应用程序文件夹中。
         2. 执行以下操作： -- 由于 macOS 默认情况下只允许运行可信任签名的应用，如果 macOS 阻止运行该软件，请打开 macOS 终端，在新建的终端 Shell 中输入：
         ```
             sudo spctl --master-disable   # 由于调用了sudo权限，你可能需要输入密码，会输出如下提示：
         ```
         3. Clash订阅
            + ![订阅转换界面](https://help.loliloli.live/~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-MJ1y1XnJx_66NtD2R1x%2F-MUEA1oOy3HqAa6CRnyR%2F-MUEANqHW_EnKbwZKKCB%2F%E6%88%AA%E5%9B%BE_20213923093929.png?alt=media&token=5f79f6cb-d2e5-48a2-beb6-fd6fe08dd15e)<br>
               - 切记按照上图配置进行选择，否则规则自动测速必定炸设备，导致全部节点被冻结5分钟无法使用！！！
               - 图片说明
                  * 客户端：Clash新参数
                  * 远程配置：ACL4SSR_Online_NoAuto_无自动测速（与Github同步）
                  * 后端地址：默认即可
            + 添加订阅
               1. 打开 Clash for Windows for Mac 后，点击窗口左侧的 Profiles (配置文件)。
                  - [Profiles (配置文件) - 界面](https://gblobscdn.gitbook.com/assets%2F-MJ2Won_67fkuqWwhDZT%2F-MJ2WrvaSeEcP1xOYUAR%2F-MJ2XUAj2gMMv7_l0jkT%2Fimage.png?alt=media&token=5ec69972-2ac3-44c1-87b8-cb46427eb1c2)<br>
               3. 在 Profiles 页面顶部，输入 Clash 配置订阅链接，然后点击 Download 下载配置文件。
               4. 下载成功后，Clash for Windows 将自动切换配置文件。
            + 设置代理模式
               1. 点击窗口左侧的 Proxies (代理)。 -- 默认情况下，Clash 使用 Rule (规则) 模式。不推荐选择 Global (全局) 与 Direct (直连) 模式。
               2. 点rule之后会有一个“节点选择”，在 ”节点选择“ 里勾选一个有效节点即可使用。如下图
                  - ![节点选择](https://help.loliloli.live/~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-MJ1y1XnJx_66NtD2R1x%2F-M_xzi0-ufKKEgIGHNZ1%2F-M_y-2BW3syOOaI9xnnM%2Ft03.webp?alt=media&token=2c2bf44f-98da-4c03-93ea-48ac0b1a832d)<br>
         4. 选择完成后，点击窗口左侧的 General (通用)。 开启 System Proxy (系统代理)，即可科学上网。 
            + ![System Proxy (系统代理) - 界面](https://gblobscdn.gitbook.com/assets%2F-MJ2Won_67fkuqWwhDZT%2F-MJ2WrvaSeEcP1xOYUAR%2F-MJ2XoZvzl87V5dNm8Ga%2Fimage.png?alt=media&token=0d45c096-0672-4131-ae8e-155e696d81f7)<br>
         6. -- Clash 支持通过策略组，对不同的网站使用不同的策略。合理使用分流可以提升使用体验。  
         7. 其他配置 - 部分Mac系统需要自动配置代理方式,具体操作如下.
            + 选取苹果菜单 >“系统偏好设置”，然后点按“网络”。
            + 在列表中，选择您所使用的网络服务，例如“以太网”或 Wi-Fi。
            + 点按“高级”，然后点按“代理”。
            + 代理服务器设置
               - 如果想要自动配置代理服务器设置，请执行以下一项操作：
若要自动发现代理服务器，请选择“自动发现代理”。
                  * ![代理服务器设置](https://help.loliloli.live/~/files/v0/b/gitbook-28427.appspot.com/o/assets%2F-MJ1y1XnJx_66NtD2R1x%2F-MUiKsjgBKoVh2wVIHbo%2F-MUiLAyv6Ofn_Il-nwJF%2Fimage.png?alt=media&token=b6a1ca73-9085-4013-b6f1-ff2aa5a34640)<br>










## v2ray
   * 参考
      + [标签： v2ray节点] --> [https://fanqiang.network/tag/v2ray%E8%8A%82%E7%82%B9/](https://fanqiang.network/tag/v2ray%E8%8A%82%E7%82%B9/)<br>
## ShadowsocksR ｜ ShadowsocksX-NG<br> ShadowsocksR LearningNote --> [https://github.com/huarui0/ProxyKnackNote/blob/master/ShadowsocksR_Note.md](https://github.com/huarui0/ProxyKnackNote/blob/master/ShadowsocksR_Note.md)<br>
   * 官网参考
      + [shadowsocks - Clients](https://shadowsocks.org/en/download/clients.html)<br>
   * 下载
      + 地址：[shadowsocks/ShadowsocksX-NG](https://github.com/shadowsocks/ShadowsocksX-NG/releases)<br>
   * 安装步骤
   * 配置

## VPN App 的使用教程
   * F-Secure FREEDOME VPN - 支持全平台！
      + 实测油管18000Kbps，正规无限试用31天国际大厂F-Secure FREEDOME VPN，支持全平台！ -- [https://www.youtube.com/watch?v=upU5RF3O2bk](https://www.youtube.com/watch?v=upU5RF3O2bk)<br>
   * PrivadoVPN
      + 全平台终身免费VPN，无需配置一键连接，可选12个国家线路 速度快滴不要不要的 --> [https://www.youtube.com/watch?v=tqCBQxf08cg](https://www.youtube.com/watch?v=tqCBQxf08cg)<br>
   * 使用内置的VPN连接 - 172.245.211.129
      + 手机电脑无需下载任何软件空手翻墙，附1900个VPN节点！ --> [https://www.youtube.com/watch?v=zdMoD1jElis](https://www.youtube.com/watch?v=zdMoD1jElis)<br>

# YouTube 教程
## 订阅教程
### 有用的资源
   *  andehui's Blogger --> [https://blog.a169.org/](https://blog.a169.org/)<br> 参阅 每日更新的 订阅 信息 --><br>[https://blog.a169.org/2022/01/ssr2022130-10.html](https://blog.a169.org/2022/01/ssr2022130-10.html)<br>
[https://blog.a169.org/2022/02/ss-ssr-v2ray.html](https://blog.a169.org/2022/02/ss-ssr-v2ray.html)<br>
### SSR 订阅
   * 全平台终身免费VPN，自由切换节点 速度快滴不要不要的 --> [https://www.youtube.com/watch?v=3LhGYuA9xfk](https://www.youtube.com/watch?v=3LhGYuA9xfk)<br>
   * 给电脑和手机 装一个永久免费的VPN 速度与付费版一样 高清4k无压力 --> [https://www.youtube.com/watch?v=aJiEGzwP99s](https://www.youtube.com/watch?v=aJiEGzwP99s)<br>
# 临时邮件地址
   * https://temp-mail.org/zh/ -- 可以接收临时邮件的地方
# Ping - IP是否被屏蔽 的 方法
   * Ping IP 工具 -- [https://tools.ipip.net/ping.php](https://tools.ipip.net/ping.php)<br>
