# 参考
   * **Internet censorship circumvention** --> [https://en.wikipedia.org/wiki/Internet_censorship_circumvention](https://en.wikipedia.org/wiki/Internet_censorship_circumvention)<br>
   * 突破网络审查 --> [https://zh.wikipedia.org/wiki/突破网络审查](https://zh.wikipedia.org/wiki/%E7%AA%81%E7%A0%B4%E7%BD%91%E7%BB%9C%E5%AE%A1%E6%9F%A5)<br>
   * Understanding and Circumventing Network Censorship --> [https://ssd.eff.org/en/module/understanding-and-circumventing-network-censorship](https://ssd.eff.org/en/module/understanding-and-circumventing-network-censorship)<br>
   * How to: Use Tor on macOS --> [https://ssd.eff.org/en/node/80/](https://ssd.eff.org/en/node/80/)  -- Circumventing Network Surveillance
   * How to: Use Tor for Windows --> [https://ssd.eff.org/en/node/57/](https://ssd.eff.org/en/node/57/)  -- Circumventing Network Surveillance
# 名词解释
   1. Network Censorship <---> Network Blockade =-------> Network Surveillance : 如通过Cookie？ =-----> Network Tracing
   2. Circumvention: [https://dictionary.cambridge.org/us/dictionary/english/circumvention](https://dictionary.cambridge.org/us/dictionary/english/circumvention) --><br>           
      * Circumventing |==========|-->|Blockade: [https://dictionary.cambridge.org/us/dictionary/english/blockade](https://dictionary.cambridge.org/us/dictionary/english/blockade) --><br>  
      *                   |--> Network           |
      * Bypassing ----|==========|-->|Censorship [https://dictionary.cambridge.org/us/dictionary/english/censorship](https://dictionary.cambridge.org/us/dictionary/english/censorship) --><br>  

# App
## Clash
   * 下载
      - Github项目地址： --> [https://github.com/Dreamacro/clash/releases](https://github.com/Dreamacro/clash/releases)<br>
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

### ClashX for MacOS --> Clashx Pro
   * 参考
   * 教程
      + [Mac技巧之苹果电脑 macOS 系统上开源免费的 shadowsocks 客户端软件：ClashX](https://www.mac52ipod.cn/post/apple-mac-macos-shadowsocks-client-app-clashx.php)<br>
      + [ClashX教程 | macOS上好看又好用的科学上网工具] --> [https://merlinblog.xyz/wiki/ClashX.html](https://merlinblog.xyz/wiki/ClashX.html)<br>
      + [苹果电脑翻墙软件：ClashX MAC使用教程，一款在MAC电脑上非常好用的翻墙软件，支持SSR/V2ray/Trojan节点，mac os 翻墙vpn下载（cc字幕）]--><br>[https://www.youtube.com/watch?v=ipwsiG03W6g](https://www.youtube.com/watch?v=ipwsiG03W6g)<br>
      + Add support for AppleScript #827 --> [https://github.com/yichengchen/clashX/pull/827](https://github.com/yichengchen/clashX/pull/827)<br>
   * 步骤
      1. 下载
        - ClashX 下载地址 --> [https://github.com/yichengchen/clashX/releases](https://github.com/yichengchen/clashX/releases)<br>
        - ClashX Pro 下载地址： Appcenter --> [https://install.appcenter.ms/users/clashx/apps/clashx-pro/distribution_groups/public](https://install.appcenter.ms/users/clashx/apps/clashx-pro/distribution_groups/public)<br> 
           * <details>
                <summary>1.91.1 Release 说明</summary>
                <br>
                    + 升级 Clash Core 到 1.10, 支持snell v3, PROCESS-PATH规则，查看Clash Release Note 获取详细信息。<br>
                    + 支持使用 AppleScript 切换代理模式<br>
                    + 修复开机启动选项在某些状态不生效的问题<br>
                    + 修复10.13系统支持<br>
                    ```
                    # Apple Script 使用方法
                      tell application "ClashX" to toggleProxy // 切换代理开关
                      tell application "ClashX" to proxyMode "direct" // 切换代理模式
                      tell application "ClashX" to proxyMode "global"
                      tell application "ClashX" to proxyMode "rule"
                    + ClashX Pro 集成premium core，提供增强模式(tun)，rule set等特性支持，<br>
                    
             </details>


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