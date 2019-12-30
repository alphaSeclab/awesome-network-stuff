# 所有收集类项目:
- [收集的所有开源工具](https://github.com/alphaSeclab/sec-tool-list): 超过18K, 包括Markdown和Json两种格式
- [逆向资源](https://github.com/alphaSeclab/awesome-reverse-engineering): IDA/Ghidra/x64dbg/OllDbg/WinDBG/CuckooSandbox/Radare2/BinaryNinja/DynamoRIO/IntelPin/Frida/QEMU/Android安全/iOS安全/Window安全/Linux安全/macOS安全/游戏Hacking/Bootkit/Rootkit/Angr/Shellcode/进程注入/代码注入/DLL注入/WSL/Sysmon/...
- [网络相关的安全资源](https://github.com/alphaSeclab/awesome-network-stuff): 代理/GFW/反向代理/隧道/VPN/Tor/I2P，以及中间人/PortKnocking/嗅探/网络分析/网络诊断等
- [攻击性网络安全资源](https://github.com/alphaSeclab/awesome-cyber-security): 漏洞/渗透/物联网安全/数据渗透/Metasploit/BurpSuite/KaliLinux/C&C/OWASP/免杀/CobaltStrike/侦查/OSINT/社工/密码/凭证/威胁狩猎/Payload/WifiHacking/无线攻击/后渗透/提权/UAC绕过/...



# network-stuff


- 跟网络相关的安全资源，包括：代理/GFW/反向代理/隧道/VPN/Tor/I2P，以及中间人/PortKnocking/嗅探/网络分析/网络诊断等。超过1700开源安全工具。相关文章待添加。
- [English Version](https://github.com/alphaSeclab/awesome-network-stuff/blob/master/Readme_en.md)


# 目录
- [工具](#1a9934198e37d6d06b881705b863afc8)
    - [(1) 收集](#74ecf59705f3b800caed3664c6d32624)
    - [未分类](#56acb7c49c828d4715dce57410d490d1)
    - [(40) Replay&&重播](#58b6684347a223e01d4d76d9ca185a88)
    - [(1) 通信协议](#e810979fcdfaefc2375a65e9b3f3a11c)
    - [(7) Multiplexer](#dd2b52e59921ad730fceac252d99dd77)
    - [(7) Impacket](#0effa0fb88eb72a133563727d42910d9)
    - [(30) Wireshark](#6fa0e0d1f898fba299b2566a33602841)
    - [(16) Netcat](#b35965810463fb97b1ca26d94a8b62f0)
    - [(21) Scapy](#01f99d208e245eb44f15f720043b50d4)
    - [(8) Tcpdump](#b293f791ec9366957733415323755aa6)
    - [pcap](#f13469c9891173804423be4403b2c4ff)
        - [(58) 未分类](#eb49514924c3f4bf2acf6f3a4436af13)
        - [(3) 转换](#b239f12aca7aa942b45836032cbef99a)
        - [(2) 收集](#d365897ae51adc286d4e6f6787924d69)
    - [(16) libpcap](#8bc2e181f74ba67ec93fd2a13d95cc0c)
    - [(5) WinPcap](#5303e6ae470e6def3b69d614674a1c46)
    - [(8) fiddler](#31d28e8b2cf6c06411cd5d178dbd3e77)
    - [(5) 网络数据包](#64f068672e615343db9235f1973d8fba)
    - [(34) 其他](#eec238a1a2657b70f7bbbe68a4421249)
- [代理&&Proxy](#21cbd08576a3ead42f60963cdbfb8599)
    - [工具](#d03d494700077f6a65092985c06bf8e8)
        - [(65) 未分类](#0ff94312f3ab4898f5996725133ea9d1)
        - [(17) HAProxy](#d3069cac6097830d12f5933c9c8b7a77)
        - [DNS](#6381920f17576b07cc87a8dc619123aa)
            - [(7) 未分类](#b0328a85ce70f4be618511259df159a9)
            - [(19) DNSCrypt](#191c4ddd413ed659f507ef4ad8c17818)
        - [(13) HTTP&&HTTPS](#b6f25145e99ea944cbb528a24afaa0be)
        - [V2Ray](#dbc310300d300ae45b04779281fe6ec8)
            - [(57) 未分类](#9a47326f72e25428c0163118b9eb42e5)
            - [(9) V2Ray-lib/GUI](#441d09c37d758425d97bcdb5e08a4256)
            - [(1) 帐号](#e3e66ebfedb62affa6ef04eced00448f)
            - [(3) 安装&&管理](#733afa2680ce2eab471cddc5654cd95b)
            - [模板](#d34c4520a378177efaaa60911f07d8d0)
            - [其他](#1072cf1157d333483198c30028f65e5a)
        - [(3) proxychains](#160b0cdb52f30bdc3f222aa08c91d10d)
        - [Shadowsocks](#cb16466a31a167bb61f39e2a4a85f449)
            - [(51) 未分类](#60a91763cc1c0e034bee9717b9b87468)
            - [(4) 帐号](#81bb199d6d8690cc6d7ddc92aa81f7f9)
            - [(2) 其他](#81ba7ad53e5c5f4a9615923ba9595928)
            - [(3) 插件](#bfe4545f8f585c6f19d28ae9d5912aff)
            - [(40) ShadowsocksR](#02a80eb3908819d75933198c6b9c6008)
            - [(6) Shadowsocks-ng](#0b7ec49dd41a16ce7ba58d399475e09f)
            - [(1) 收集](#bdf7adbb1e8c52aa89dc771aa5fedc4b)
            - [(42) Shadowsocks-lib/gui](#f90ec3d0727d2ee3840df6c9f9557756)
            - [(7) Docker](#82476f41454f4e55dcdcf45d817e0395)
            - [(18) 安装&&管理](#0a4e6103d8a48ee758983d56018076da)
        - [(94) Socks](#57b8e953d394bbed52df2a6976d98dfa)
        - [(11) 安装&&配置&&管理](#8ff91c8095e77fe88dcac1cff78d79c6)
        - [代理爬取&&代理池](#b2241c68725526c88e69f1d71405c6b2)
            - [(16) 抓取](#6d7e96fefef09f8ac350c8e9d77ec49c)
            - [(2) 使用](#4417ed293dcbe11e3b5057be518e670d)
    - [文章](#07fb7fc7f8ef8da762c2cc86c482a3f6)
- [翻墙&&GFW](#837c9f22a3e1bb2ce29a0fb2bcd90b8f)
    - [工具](#af9d2b4988d35a2a634c042a1c66bb8c)
        - [(1) 未分类](#fe72fb9498defbdbb98448511cd1eaca)
        - [(28) 翻墙](#6e28befd418dc5b22fb3fd234db322d3)
        - [(38) GFW](#e9cc4e00d5851a7430a9b28d74f297db)
    - [文章](#8c94b343a7f1fb63a1ac538d032425a0)
- [匿名网络](#b03a7c05fd5b154ad593b6327578718b)
    - [工具](#6e80463404d46f0493cf6e84597e4b5c)
        - [(5) 未分类](#f0979cd783d1d455cb5e3207d574aa1e)
        - [(139) Tor&&&Onion&&洋葱](#e99ba5f3de02f68412b13ca718a0afb6)
        - [(11) I2P](#ceb532aae106b39ea224c7aef786c831)
    - [文章](#7b28248ff4b6fe73675e3139109ef93d)
- [隧道&&穿透&&反向代理](#e996f5ff54050629de0d9d5e68fcb630)
    - [工具](#01e6651181d405ecdcd92a452989e7e0)
        - [(36) 未分类](#ea4dfcd8f33ec1852180c6283b2c8516)
        - [(56) 反向代理](#e9f97504fbd14c8bb4154bd0680e9e62)
        - [(125) 隧道&&穿透](#9d6789f22a280f5bb6491d1353b02384)
        - [(5) 公网访问局域网](#8ea8f890cf767c3801b5e7951fca3570)
    - [文章](#c8cc22e067df97d3c58ac53b91ebe240)
- [VPN](#891b953fda837ead9eff17ff2626b20a)
    - [(119) 工具](#d62a971d37c69db9f3b9187318c3921a)
    - [(25) OpenVPN](#7cf7e8a30b73997985f20698eaf6b0c9)
- [中间人&&MITM](#42ae221f526f55b5282ea221a376ec6c)
    - [(146) 未分类](#42f9e068b6511bcbb47d6b2b273097da)
    - [(1) 收集](#4958460c709a66ca528f1732117e8dfd)
    - [(12) mitmproxy](#b4959a15647a6dcf79901f76655d0ca8)
- [分析&&取证&&诊断&&探查&&检测&&嗅探](#3c28b67524f117ed555daed9cc99e35e)
    - [工具](#7bf0f5839fb2827fdc1b93ae6ac7f53d)
        - [(23) 未分类](#b346105580b0240d693020ce8719ebca)
        - [(2) 协议分析](#8dd8c4c8d11c149aa803a221480687d2)
        - [(3) 网络诊断](#9dfefb87c4dc3288b2eddf6780e8ffb9)
        - [(4) 取证](#b3811e8d4be5755957b0ec0e336715a2)
        - [(170) 嗅探&&Sniff](#32739127f0c38d61b14448c66a797098)
        - [(14) 捕获&&Capture](#d7485f829bd85cd784ff582cbddc8624)
        - [(1) 流量检测](#471c124b012dbde8ea3288f35667efc8)
        - [(4) Xx分析](#07701b342951b5d7bfa839db7752f9dd)
    - [文章](#384f5e1bef62f815c6745062f2975ba7)
- [网络攻击](#53da0cc607b98c444ec0e50a0b77f754)
    - [工具](#295e14c39bf33cd5136be8ced9383746)
        - [(2) PortKnocking](#07f06751f1de7ddd1f6a95323f0191c8)
        - [(45) 伪造&&Spoof](#f855508acfc870b1f0d90ff316f1dd75)
        - [(1) 检测绕过](#62b461e2ceead9edb75c1b51f6eecdfd)
        - [(21) 投毒&&Poisoning](#3bd67ee9f322e2c85854991c85ed6da0)
- [Android](#c63cbfa77e689e485fc2d8bc5051f229)
    - [(21) 工具](#863839860fab4b8601905205cac9b54f)
- [iOS](#70857140d346b443fe3b7ea3046f702a)
    - [(13) 工具](#692d86299dedab073fbb6144a5b2bd64)


# <a id="1a9934198e37d6d06b881705b863afc8"></a>工具


***


## <a id="74ecf59705f3b800caed3664c6d32624"></a>收集


- [**1787**星][4y] [caesar0301/awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools) 用于处理网络痕迹的工具收集


***


## <a id="56acb7c49c828d4715dce57410d490d1"></a>未分类




***


## <a id="58b6684347a223e01d4d76d9ca185a88"></a>Replay&&重播


- [**12024**星][2m] [Go] [buger/goreplay](https://github.com/buger/goreplay) 实时捕获HTTP流量并输入测试环境，以便持续使用真实数据测试你的系统
- [**8180**星][5d] [JS] [netflix/pollyjs](https://github.com/netflix/pollyjs) Record, Replay, and Stub HTTP Interactions.
- [**4625**星][5d] [Ruby] [vcr/vcr](https://github.com/vcr/vcr) Record your test suite's HTTP interactions and replay them during future test runs for fast, deterministic, accurate tests.
- [**4597**星][4d] [C++] [mozilla/rr](https://github.com/mozilla/rr) 记录与重放App的调试执行过程
- [**3450**星][6m] [C] [session-replay-tools/tcpcopy](https://github.com/session-replay-tools/tcpcopy) tcpcopy：TCP 流量回放工具，可用于性能测试、稳定性测试、压力测试、加载测试、smoke 测试等
- [**1461**星][2y] [C++] [acaudwell/logstalgia](https://github.com/acaudwell/logstalgia)  a visualization tool that replays or streams web server access logs as a retro arcade game simulation.
- [**1417**星][1m] [Java] [chrisk44/hijacker](https://github.com/chrisk44/hijacker) Aircrack, Airodump, Aireplay, MDK3 and Reaver GUI Application for Android
- [**605**星][30d] [Py] [webrecorder/pywb](https://github.com/webrecorder/pywb) 重放和记录Web存档
- [**565**星][10d] [C] [appneta/tcpreplay](https://github.com/appneta/tcpreplay) Pcap 编辑和重放工具（针对*nix和Windows）
- [**262**星][2m] [Py] [felixweyne/imaginaryc2](https://github.com/felixweyne/imaginaryc2) Imaginary C2 is a python tool which aims to help in the behavioral (network) analysis of malware. Imaginary C2 hosts a HTTP server which captures HTTP requests towards selectively chosen domains/IPs. Additionally, the tool aims to make it easy to replay captured Command-and-Control responses/served payloads.
- [**149**星][28d] [Py] [swehner/foos](https://github.com/swehner/foos) Instant replay system for foosball table
- [**126**星][4y] [C] [ctxis/rdp-replay](https://github.com/ctxis/rdp-replay) 重播pcap文件中的RDP流量
- [**87**星][8m] [Go] [seborama/govcr](https://github.com/seborama/govcr) HTTP mock for Golang: record and replay HTTP/HTTPS interactions for offline testing
- [**82**星][2y] [JS] [dmarcos/aframe-motion-capture-components](https://github.com/dmarcos/aframe-motion-capture-components) Capture entity motions and replay them on other entities
- [**78**星][1y] [Py] [ionelmc/python-aspectlib](https://github.com/ionelmc/python-aspectlib) An aspect-oriented programming, monkey-patch and decorators library. It is useful when changing behavior in existing code is desired. It includes tools for debugging and testing: simple mock/record and a complete capture/replay framework.
- [**74**星][4m] [Lua] [dns-oarc/drool](https://github.com/dns-oarc/drool) DNS Replay Tool
- [**73**星][2y] [Java] [spiderlabs/burplay](https://github.com/spiderlabs/burplay) Burplay is a Burp Extension allowing for replaying any number of requests using same modifications definition. Its main purpose is to aid in searching for Privilege Escalation issues.
- [**72**星][28d] [C++] [rigtorp/udpreplay](https://github.com/rigtorp/udpreplay) 重播pcap文件中的UDP数据包
- [**69**星][9d] [Py] [catch-up-tv-and-more/plugin.video.catchuptvandmore](https://github.com/catch-up-tv-and-more/plugin.video.catchuptvandmore) Replay, Live TV and websites videos addon for Kodi
- [**66**星][1m] [Py] [hatching/httpreplay](https://github.com/hatching/httpreplay) 根据TLS主密钥，重播PCAP文件中的HTTP和HTTPS请求
- [**60**星][3y] [Py] [iamckn/mousejack_transmit](https://github.com/iamckn/mousejack_transmit) Wireless mouse/keyboard attack with replay/transmit poc
- [**59**星][23d] [C++] [whid-injector/whid-31337](https://github.com/whid-injector/whid-31337) WHID Elite is a GSM-enabled Open-Source Multi-Purpose Offensive Device that allows a threat actor to remotely inject keystrokes, bypass air-gapped systems, conduct mousejacking attacks, do acoustic surveillance, RF replay attacks and much more. In practice, is THE Wet Dream of any Security Consultant out there!
- [**56**星][2m] [Shell] [125k/pwrdeauther](https://github.com/125K/PwrDeauther) This script allows you to deauth a specific SSID or an entire channel with mdk3 (MDK3 is more powerful than Aireplay)
- [**56**星][2m] [Shell] [125k/pwrdeauther](https://github.com/125k/pwrdeauther) This script allows you to deauth a specific SSID or an entire channel with mdk3 (MDK3 is more powerful than Aireplay)
- [**54**星][26d] [Java] [vy/hrrs](https://github.com/vy/hrrs) Record, transform, and replay HTTP requests in Java EE and Spring applications.
- [**46**星][1y] [HTML] [octosavvi/espkey](https://github.com/octosavvi/espkey) Wiegand data logger, replay device and micro door-controller
- [**43**星][1y] [Py] [nirizr/pytest-idapro](https://github.com/nirizr/pytest-idapro) 辅助对IDAPython脚本进行单元测试
- [**34**星][24d] [C] [dns-oarc/dnsjit](https://github.com/dns-oarc/dnsjit) Engine for capturing, parsing and replaying DNS
- [**33**星][29d] [C] [root670/cheatdeviceps2](https://github.com/root670/cheatdeviceps2) Game enhancer for PlayStation 2 similar to Action Replay, GameShark, and CodeBreaker.
- [**27**星][11d] [C] [microsoft/wafbench](https://github.com/microsoft/wafbench) WAFBench (wb) is a tool to measure the performance of WAF(Web Application Firewall) . It's based on latest code of ab (ApacheBench), and adds support for real trace replaying, framework of testing waf (FTW), and some other features.
- [**26**星][1m] [Go] [linus4/csgoverview](https://github.com/linus4/csgoverview) A 2D demo replay tool for Counter Strike: Global Offensive.
- [**25**星][4d] [TS] [airtasker/proxay](https://github.com/airtasker/proxay) Proxay is a record/replay proxy server that helps you write faster and more reliable tests.
- [**21**星][2y] [Py] [pure-l0g1c/aircrack](https://github.com/pure-l0g1c/aircrack) Automatic Wifi Cracker. Uses Airodump, Aircrack, Aireplay
- [**20**星][3y] [JS] [tunnelshade/pocuito](https://github.com/tunnelshade/pocuito) A tiny chrome extension to record and replay your web application proof-of-concepts.
- [**19**星][3y] [cn0xroot/gr-replay](https://github.com/cn0xroot/gr-replay) 用于Gnuradio的信号捕捉和重放
- [**17**星][2y] [C] [deanjerkovich/rage_fuzzer](https://github.com/deanjerkovich/rage_fuzzer) a dumb protocol-unaware packet fuzzer/replayer
- [**16**星][2y] [Lua] [withlin/kong-plugin-http-anti-replay-attack](https://github.com/withlin/kong-plugin-http-anti-replay-attack) 防重放攻击
- [**15**星][6m] [yuangongnd/remasc](https://github.com/yuangongnd/remasc) ReMASC: Realistic Replay Attack Corpus for Voice Controlled Systems
- [**15**星][2y] [C#] [hackingthings/can-bus-arduino-tool](https://github.com/HackingThings/CAN-Bus-Arduino-Tool) A tool for performing replay and sniffing CAN bus traffic.
- [**3**星][5y] [Haskell] [maurer/tachyon](https://github.com/maurer/tachyon) Record/Replay for syscall streams


***


## <a id="e810979fcdfaefc2375a65e9b3f3a11c"></a>通信协议


- [**1692**星][5m] [C] [networkprotocol/netcode.io](https://github.com/networkprotocol/netcode.io) 基于UDP的安全通信协议


***


## <a id="dd2b52e59921ad730fceac252d99dd77"></a>Multiplexer


- [**2530**星][1m] [C] [yrutschle/sslh](https://github.com/yrutschle/sslh) 应用协议多路复用器（例如，在同一端口上共享SSH和HTTPS）。接受指定端口上的连接，并根据对第一个数据包的测试结果将其转发
- [**1056**星][20d] [C++] [simsong/tcpflow](https://github.com/simsong/tcpflow) TCP/IP 数据包分用器
- [**797**星][2m] [Go] [trivago/gollum](https://github.com/trivago/gollum) An n:m message multiplexer written in Go
- [**728**星][1m] [C++] [stealth/sshttp](https://github.com/stealth/sshttp) SSH/HTTP(S) multiplexer. Run a webserver and a sshd on the same port w/o changes.
- [**31**星][6m] [Py] [innogames/polysh](https://github.com/innogames/polysh) Polysh, the remote shell multiplexer
- [**25**星][2y] [Py] [qiaofei32/tcp-multiplexer](https://github.com/qiaofei32/tcp-multiplexer) A TCP service multiplexer in Python
- [**7**星][2m] [Py] [adafruit/adafruit_circuitpython_tca9548a](https://github.com/adafruit/adafruit_circuitpython_tca9548a) CircuitPython driver for the TCA9548A I2C Multiplexer.


***


## <a id="0effa0fb88eb72a133563727d42910d9"></a>Impacket


- [**3922**星][5d] [Py] [secureauthcorp/impacket](https://github.com/SecureAuthCorp/impacket) Python类收集, 用于与网络协议交互
- [**381**星][1m] [Py] [fox-it/bloodhound.py](https://github.com/fox-it/bloodhound.py) 基于Python的BloodHound Ingestor，基于Impacket
- [**288**星][11m] [maaaaz/impacket-examples-windows](https://github.com/maaaaz/impacket-examples-windows) The great impacket example scripts compiled for Windows
- [**203**星][5d] [Py] [ropnop/impacket_static_binaries](https://github.com/ropnop/impacket_static_binaries) Standalone binaries for Linux/Windows of Impacket's examples
- [**88**星][10m] [Py] [dirkjanm/impacket](https://github.com/dirkjanm/impacket) Impacket is a collection of Python classes for working with network protocols.
- [**71**星][7m] [Py] [zer1t0/ticket_converter](https://github.com/zer1t0/ticket_converter) A little tool to convert ccache tickets into kirbi (KRB-CRED) and vice versa based on impacket.
- [**67**星][3y] [Py] [harmj0y/impdump](https://github.com/harmj0y/impdump) This is a simple parser for/decrypter for Impacket's esentutl.py utility. It assists with decrypting hashes and hash histories from ntds.dit databases.


***


## <a id="6fa0e0d1f898fba299b2566a33602841"></a>Wireshark


- [**4857**星][5d] [Go] [gcla/termshark](https://github.com/gcla/termshark) A terminal UI for tshark, inspired by Wireshark
- [**2409**星][4d] [C] [wireshark/wireshark](https://github.com/wireshark/wireshark) Wireshark
- [**988**星][23d] [Py] [kiminewt/pyshark](https://github.com/kiminewt/pyshark) Python wrapper for tshark, allowing python packet parsing using wireshark dissectors
- [**593**星][1y] [Py] [softscheck/tplink-smartplug](https://github.com/softscheck/tplink-smartplug) TP-Link WiFi SmartPlug Client and Wireshark Dissector
- [**499**星][8m] [Rust] [cloudflare/wirefilter](https://github.com/cloudflare/wirefilter) An execution engine for Wireshark-like filters
- [**354**星][2y] [Shell] [koenbuyens/kalirouter](https://github.com/koenbuyens/kalirouter) 将 KaliLinux 主机转变为路由器，使用 Wireshark 记录所有的网络流量，同时将 HTTP/HTTPS 流量发送到其他主机的拦截代理（例如 BurpSuite）
- [**343**星][6y] [JS] [evilcos/cookiehacker](https://github.com/evilcos/cookiehacker) Cookie利用
- [**295**星][2m] [Lua] [pentesteracademy/patoolkit](https://github.com/pentesteracademy/patoolkit) 一组流量分析插件，用于将Wireshark的功能从微分析工具和协议解析器扩展到宏分析器和威胁猎人。
- [**184**星][1y] [Lua] [ntop/wireshark-ntop](https://github.com/ntop/wireshark-ntop) Extensions for Wireshark
- [**163**星][10m] [C] [davidgfnet/wireshark-whatsapp](https://github.com/davidgfnet/wireshark-whatsapp) Whatsapp dissector plugin for wireshark
- [**151**星][11m] [Py] [wangshub/hmpa-pi](https://github.com/wangshub/hmpa-pi) 在树莓派上，利用 Wireshark 扫描附近网络 WiFi 设备，并对扫描结果通过邮件或者微信进行推送
- [**135**星][5y] [Py] [ashdnazg/pyreshark](https://github.com/ashdnazg/pyreshark) A Wireshark plugin providing a simple interface for writing dissectors in Python.
- [**97**星][8m] [Shell] [shadowhatesyou/pipetap.sh](https://github.com/shadowhatesyou/pipetap.sh) This script invokes tcpdump over ssh piping to STDOUT, allowing remote use of wireshark
- [**85**星][6y] [C] [armenb/sharktools](https://github.com/armenb/sharktools) Tools for programmatic parsing of packet captures using Wireshark functionality
- [**68**星][3y] [CMake] [bastilleresearch/gr-nordic](https://github.com/bastilleresearch/gr-nordic) GNU Radio module and Wireshark dissector for the Nordic Semiconductor nRF24L Enhanced Shockburst protocol.
- [**66**星][10m] [security-cheatsheet/wireshark-cheatsheet](https://github.com/security-cheatsheet/wireshark-cheatsheet) Wireshark Cheat Sheet
- [**55**星][2m] [C] [secureauthcorp/sap-dissection-plug-in-for-wireshark](https://github.com/SecureAuthCorp/SAP-Dissection-plug-in-for-Wireshark) This Wireshark plugin provides dissection of SAP's NI, Diag, Enqueue, Router, Message Server, SNC and IGS protocols.
- [**46**星][3y] [C] [rpcapd-linux/rpcapd-linux](https://github.com/rpcapd-linux/rpcapd-linux) 为Windows版本的Wireshark提供远程流量捕获的守护程序
    - 重复区段: [分析->工具->捕获](#d7485f829bd85cd784ff582cbddc8624) |
- [**40**星][6m] [Lua] [whitequark/zmtp-wireshark](https://github.com/whitequark/zmtp-wireshark) A Wireshark dissector for ZMTP version 3.0 and later (ZeroMQ 4 and later)
- [**39**星][2y] [Lua] [bcsecorg/ethereum_devp2p_wireshark_dissector](https://github.com/bcsecorg/ethereum_devp2p_wireshark_dissector) This is Ethereum devp2p protocol dissector plugin for wireshark.
- [**33**星][1y] [seemoo-lab/wireshark-awdl](https://github.com/seemoo-lab/wireshark-awdl) Wireshark Dissector for Apple Wireless Direct Link (AWDL) and Apple's CoreCapture logging framework. Note: the AWDL dissector is part of Wireshark 3.0!
- [**21**星][12m] [Lua] [cloudshark/wireshark-plugin](https://github.com/cloudshark/wireshark-plugin) Upload captures directly to CloudShark from Wireshark
- [**17**星][6m] [Lua] [markopaul0/wirebait](https://github.com/markopaul0/wirebait) Run and test your Lua Wireshark dissector without Wireshark or capture data.
- [**9**星][2m] [C] [thephez/wireshark-plugin-dash](https://github.com/thephez/wireshark-plugin-dash) Wireshark dissector plugin for the Dash cryptocurrency protocol
- [**6**星][1y] [Py] [kiminewt/pyshark-legacy](https://github.com/kiminewt/pyshark-legacy) Python wrapper for tshark, allowing python packet parsing using wireshark dissectors (Python2 legacy version)
- [**2**星][6y] [C] [frederic/dfb-wireshark-dissector](https://github.com/frederic/dfb-wireshark-dissector) Wireshark dissector for Voodoo protocol, network layer of DirectFB.
- [**2**星][11m] [Java] [nberktumer/comp416-packet-sniffer](https://github.com/nberktumer/comp416-packet-sniffer) A simple data transfer program using TCP written in Java for sniffing the data using WireShark
- [**2**星][2y] [Lua] [sihaiyang0215/wiresharkdissector](https://github.com/sihaiyang0215/wiresharkdissector) Lua dissector for Minecraft 1.8.9 PC Edition
- [**1**星][9m] [wtanaka/ansible-role-wireshark](https://github.com/wtanaka/ansible-role-wireshark) Ansible role to install wireshark
- [**0**星][6y] [C] [mjeanson/wireshark-gmetric](https://github.com/mjeanson/wireshark-gmetric) Ganglia gmetric protocol dissector for Wireshark


***


## <a id="b35965810463fb97b1ca26d94a8b62f0"></a>Netcat


- [**1357**星][4m] [Rust] [vi/websocat](https://github.com/vi/websocat) Command-line client for WebSockets, like netcat (or curl) for ws:// with advanced socat-like functions
- [**831**星][2y] [PS] [besimorhino/powercat](https://github.com/besimorhino/powercat) PowerShell实现的Netcat
- [**490**星][3y] [PS] [secabstraction/powercat](https://github.com/secabstraction/powercat) 可与Netcat和Ncat一起使用的PowerShell TCP / IP瑞士军刀
- [**329**星][6y] [C] [diegocr/netcat](https://github.com/diegocr/netcat) NetCat for Windows
- [**264**星][1y] [JS] [roccomuso/netcat](https://github.com/roccomuso/netcat) Netcat client and server modules written in pure Javascript for Node.j
- [**150**星][3y] [Py] [nullarray/pycat](https://github.com/nullarray/pycat) Python network tool, similar to Netcat with custom features.
- [**41**星][6y] [PHP] [spiderlabs/upnp-request-generator](https://github.com/spiderlabs/upnp-request-generator) A tool to parse UPnP descriptor XML files and generate SOAP control requests for use with Burp Suite or netcat
- [**33**星][1m] [Py] [rhelmot/nclib](https://github.com/rhelmot/nclib) Netcat as a python library
- [**25**星][3y] [Py] [sc0tfree/netbyte](https://github.com/sc0tfree/netbyte) Netbyte is a Netcat-style tool that facilitates probing proprietary TCP and UDP services. It is lightweight, fully interactive and provides formatted output in both hexadecimal and ASCII.
- [**20**星][2y] [C] [pinkp4nther/pinkit](https://github.com/pinkp4nther/pinkit) A quick LKM rootkit that executes a reverse TCP netcat shell with root privileges.
- [**15**星][2y] [Swift] [vgmoose/nc-client](https://github.com/vgmoose/nc-client) [iOS] netcat gui app, for using the 10.1.x mach_portal root exploit on device
- [**10**星][10m] [JS] [roccomuso/nc](https://github.com/roccomuso/nc) Porting Netcat in Node.js. CLI util.
- [**7**星][7y] [C] [mainframed/nc110-omvs](https://github.com/mainframed/nc110-omvs) NetCat 110 with changes to support OMVS on z/OS
- [**6**星][4y] [Py] [paradoxis/reverse-shell-client](https://github.com/paradoxis/reverse-shell-client) The reverse shell client is a Python based alternative for a netcat reverse shell listener
- [**5**星][2y] [Shell] [foospidy/fuzzcat](https://github.com/foospidy/fuzzcat) Rudimentary network protocol fuzzer using bash, netcat, and other tools.
- [**4**星][12y] [C++] [liamkirton/sslcat](https://github.com/liamkirton/sslcat) [2008] Windows netcat for SSL


***


## <a id="01f99d208e245eb44f15f720043b50d4"></a>Scapy


- [**4678**星][4d] [Py] [secdev/scapy](https://github.com/secdev/scapy) 交互式数据包操作, Python, 命令行+库
- [**796**星][8m] [Py] [phaethon/kamene](https://github.com/phaethon/kamene) Network packet and pcap file crafting/sniffing/manipulation/visualization security tool. Originally forked from scapy in 2015 and providing python3 compatibility since then.
    - 重复区段: [分析->工具->嗅探](#32739127f0c38d61b14448c66a797098) |
- [**309**星][1y] [Py] [tintinweb/scapy-ssl_tls](https://github.com/tintinweb/scapy-ssl_tls) 用于Scapy，在SSL/TLS层进行交互式的数据包篡改
- [**274**星][4m] [Py] [invernizzi/scapy-http](https://github.com/invernizzi/scapy-http) Support for HTTP in Scapy
- [**186**星][5y] [Py] [rpp0/scapy-fakeap](https://github.com/rpp0/scapy-fakeap) Fake wireless Access Point (AP) implementation using Python and Scapy, intended for convenient testing of 802.11 protocols and implementations.
- [**64**星][3y] [Py] [milesrichardson/docker-nfqueue-scapy](https://github.com/milesrichardson/docker-nfqueue-scapy) Docker容器，使用python脚本在netfilter队列中监听数据包，并使用scapy操作数据包。
- [**47**星][4y] [Py] [bastilleresearch/scapy-radio](https://github.com/bastilleresearch/scapy-radio) scapy-radio (from original Hg repo)
- [**45**星][4y] [Py] [scy-phy/scapy-cip-enip](https://github.com/scy-phy/scapy-cip-enip) EtherNet/IP+CIP dissector for Scapy
- [**41**星][5y] [Py] [nimai/mptcp-scapy](https://github.com/nimai/mptcp-scapy) MPTCP firewall tester based on scapy
- [**33**星][2y] [Py] [guedou/r2scapy](https://github.com/guedou/r2scapy) a radare2 plugin that decodes packets with Scapy
- [**32**星][3m] [Py] [amossys/fragscapy](https://github.com/amossys/fragscapy) Fragscapy is a command-line tool to fuzz network protocols by automating the modification of outgoing network packets. It can run multiple successive tests to determine which options can be used to evade firewalls and IDS.
- [**25**星][4y] [Py] [averagesecurityguy/scapy](https://github.com/averagesecurityguy/scapy) Scapy Presentation and Code
- [**23**星][7m] [Py] [antisomnus/sniffer](https://github.com/antisomnus/sniffer) Simple sniffer using scapy and PyQt5 on Windows 10
    - 重复区段: [分析->工具->嗅探](#32739127f0c38d61b14448c66a797098) |
- [**19**星][5y] [Py] [feanaur/scapy-pentest](https://github.com/feanaur/scapy-pentest) Scapy Penetration testing scripts
- [**14**星][5y] [Py] [azz2k/scapy-rssi](https://github.com/azz2k/scapy-rssi) Example of how to read RSSI values from wifi packaged using Scapy
- [**13**星][4y] [Py] [rahilsharma/scapy-wireless-scanner](https://github.com/rahilsharma/scapy-wireless-scanner) Final Yr. Project B Tech CSE. Simple wireless scanner built using Scapy Library.
- [**12**星][2y] [Py] [imadhsissou/python-arp-spoofer](https://github.com/imadhsissou/python-arp-spoofer) A friendly command-line spoofing tool written in python using scapy and netifaces.
    - 重复区段: [网络攻击->工具->伪造](#f855508acfc870b1f0d90ff316f1dd75) |
- [**10**星][11m] [Py] [daniel4x/mitm-python](https://github.com/daniel4x/mitm-python) A simple as possible man in the middle written in python using scapy
    - 重复区段: [中间人->未分类](#42f9e068b6511bcbb47d6b2b273097da) |
- [**10**星][5y] [Py] [emileaben/scapy-dns-ninja](https://github.com/emileaben/scapy-dns-ninja) Minimal DNS answering machine, for customized/programmable answers
- [**9**星][5m] [Py] [skyplabs/scapy-mitm](https://github.com/skyplabs/scapy-mitm) ARP cache poisoning implementation using Scapy
    - 重复区段: [中间人->未分类](#42f9e068b6511bcbb47d6b2b273097da) |
- [**3**星][4y] [Py] [mk-fg/scapy-nflog-capture](https://github.com/mk-fg/scapy-nflog-capture) Driver for scapy to allow capturing packets via Linux NFLOG interface


***


## <a id="b293f791ec9366957733415323755aa6"></a>Tcpdump


- [**1186**星][19d] [C] [the-tcpdump-group/tcpdump](https://github.com/the-tcpdump-group/tcpdump) the TCPdump network dissector
- [**231**星][1m] [Go] [cloudflare/xdpcap](https://github.com/cloudflare/xdpcap) tcpdump like XDP packet capture
- [**59**星][2y] [Py] [yandex/tcplanz](https://github.com/yandex/tcplanz) TCPDump latency analyzer
- [**45**星][5y] [sergk/cheatsheat-tcpdump](https://github.com/sergk/cheatsheat-tcpdump) cheatsheat-tcpdump
- [**34**星][8y] [C#] [advtools/advsock2pipe](https://github.com/advtools/advsock2pipe) A small utility to connect a TCP socket to a Windows named pipe. It can be used, for exemple, to capture network data with tcpdump on Linux or iPhone/iPad and to see the capture in (almost) realtime in Wireshark on Windows. Released under GPLv3.
- [**32**星][1m] [C++] [f18m/large-pcap-analyzer](https://github.com/f18m/large-pcap-analyzer) A command-line utility program that performs some simple operations on PCAP files (Wireshark/tcpdump traces) very quickly. Allows you to manipulate very large PCAP files that cannot be easily handled with other software like Wireshark (or tshark). Supports filtering encapsulated GTPu frames. Easily extendible.
- [**3**星][4y] [Py] [wouter-glasswall/rogueap](https://github.com/wouter-glasswall/rogueap) Start a rogue access point with no effort, with support for hostapd, airbase, sslstrip, sslsplit, tcpdump builtin
- [**2**星][2y] [wtanaka/ansible-role-tcpdump](https://github.com/wtanaka/ansible-role-tcpdump) Ansible role to install tcpdump


***


## <a id="f13469c9891173804423be4403b2c4ff"></a>pcap


### <a id="d365897ae51adc286d4e6f6787924d69"></a>收集


- [**188**星][3y] [Lua] [automayt/ics-pcap](https://github.com/automayt/ics-pcap) ICS/SCADA PCAP收集
- [**30**星][4y] [neu5ron/malware-traffic-analysis-pcaps](https://github.com/neu5ron/malware-traffic-analysis-pcaps) 网站malware-traffic-analysis.net的pcap文件托管


### <a id="eb49514924c3f4bf2acf6f3a4436af13"></a>未分类


- [**765**星][5m] [Py] [lgandx/pcredz](https://github.com/lgandx/pcredz) This tool extracts Credit card numbers, NTLM(DCE-RPC, HTTP, SQL, LDAP, etc), Kerberos (AS-REQ Pre-Auth etype 23), HTTP Basic, SNMP, POP, SMTP, FTP, IMAP, etc from a pcap file or from a live interface.
- [**419**星][11m] [C] [jpr5/ngrep](https://github.com/jpr5/ngrep) 应用于网络层的类似与grep的工具。基于PCAP，可指定扩展的正则表达式或十六进制表达式，对数据包的数据payload进行匹配
- [**380**星][2m] [Py] [0x4d31/fatt](https://github.com/0x4d31/fatt) FATT /fingerprintAllTheThings - a pyshark based script for extracting network metadata and fingerprints from pcap files and live network traffic
- [**340**星][11d] [JS] [dns-oarc/packetq](https://github.com/dns-oarc/packetq) A tool that provides a basic SQL-frontend to PCAP-files
- [**225**星][1m] [Py] [secureworks/dalton](https://github.com/secureworks/dalton) 使用预定义/指定的规则, 针对IDS传感器(例如Snort/Suricata)进行网络数据包捕获
- [**216**星][2y] [C++] [spacehuhn/arduinopcap](https://github.com/spacehuhn/arduinopcap) 使用ESP8266 / ESP32和Arduin，创建并发送pcap文件
- [**123**星][2y] [Py] [blazeinfosec/pcrappyfuzzer](https://github.com/blazeinfosec/pcrappyfuzzer) pcrappyfuzzer：Scapy+ radamsa 的简单组合，从 pcap 文件中提取数据，执行快速 Fuzz
- [**123**星][3m] [XSLT] [pcapng/pcapng](https://github.com/pcapng/pcapng) PCAP下一代文件格式规范
- [**112**星][11m] [C] [rup0rt/pcapfix](https://github.com/rup0rt/pcapfix) 修复损坏的pcap文件
- [**95**星][1y] [Py] [hgn/captcp](https://github.com/hgn/captcp) A open source program for TCP analysis of PCAP files
- [**88**星][3y] [Py] [azizaltuntas/network-analysis-tools](https://github.com/azizaltuntas/network-analysis-tools) Pcap (capture file) Analysis Toolkit(v.1)
- [**79**星][1y] [Py] [shendo/websnort](https://github.com/shendo/websnort) Web service for scanning pcaps with snort
- [**64**星][3y] [Ruby] [danielmiessler/caparser](https://github.com/danielmiessler/caparser) A quick and dirty PCAP parser that helps you identify who your applications are sending sensitive data to without encryption.
- [**61**星][6y] [Py] [kevthehermit/yarapcap](https://github.com/kevthehermit/yarapcap) 使用YARA处理HTTP Pcap
- [**52**星][6y] [Py] [kevthehermit/maildb](https://github.com/kevthehermit/maildb) Python Web App to Parse and Track Email and http Pcap Files.
- [**42**星][9m] [Go] [dreadl0ck/gopcap](https://github.com/dreadl0ck/gopcap) Go语言编写的Pcap读取器，提供与同类工具的基准测试比较
- [**39**星][3m] [spiderlabs/iocs-idps](https://github.com/spiderlabs/iocs-idps) This repository will hold PCAP IOC data related with known malware samples (owner: Bryant Smith)
- [**37**星][8m] [Jupyter Notebook] [h21lab/anomaly-detection](https://github.com/h21lab/anomaly-detection) Scripts to help to detect anomalies in pcap file. Anomaly Detection using tensorflow and tshark.
- [**37**星][8y] [JS] [mudynamics/pcapr-local](https://github.com/mudynamics/pcapr-local) 浏览与管理大规模的pcap文件
- [**36**星][4m] [Py] [cisco-talos/re2pcap](https://github.com/cisco-talos/re2pcap) 用原始HTTP请求或响应创建PCAP文件
- [**36**星][11m] [Go] [hdiniz/rtpdump](https://github.com/hdiniz/rtpdump) Extract audio file from RTP streams in pcap format
- [**35**星][2y] [Py] [newbee119/ip-location](https://github.com/NewBee119/IP-location) batch query IP location information，批量查询IP地理位置信息，解析pcap包中IP地址的地理信息
- [**34**星][11m] [Go] [justinazoff/flow-indexer](https://github.com/justinazoff/flow-indexer) Flow-Indexer indexes flows found in chunked log files from bro,nfdump,syslog, or pcap files
- [**32**星][3m] [C#] [globalpolicy/csarp-netcut](https://github.com/globalpolicy/csarp-netcut) An arpspoof program using Sharppcap
- [**28**星][1y] [C] [lpefferkorn/ipdecap](https://github.com/lpefferkorn/ipdecap) Decapsulate traffic encapsulated within GRE, IPIP, 6in4, ESP (ipsec) protocols, can also remove IEEE 802.1Q (virtual lan) header. Works with pcap files.
- [**28**星][2y] [tatsui-geek/malware-traffic-analysis.net](https://github.com/tatsui-geek/malware-traffic-analysis.net) Download pcap files from
- [**27**星][2y] [Lua] [shengnoah/riff](https://github.com/shengnoah/riff) 一个基于lua插件的pcap监控工具。
- [**26**星][2y] [R] [hrbrmstr/crafter](https://github.com/hrbrmstr/crafter) Analyze and Visualize Network Packet Capture (PCAP) Files
- [**24**星][7y] [Ruby] [chrislee35/flowtag](https://github.com/chrislee35/flowtag) FlowTag visualizes pcap files for forensic analysis
- [**23**星][2y] [Py] [fireeye/brocapi](https://github.com/fireeye/brocapi) Bro PCAP Processing and Tagging API
- [**22**星][5y] [Py] [catalyst256/gobbler](https://github.com/catalyst256/gobbler) Gobbling it's way through your pcap files
- [**21**星][6m] [Go] [d4-project/sensor-d4-tls-fingerprinting](https://github.com/d4-project/sensor-d4-tls-fingerprinting) Extract TLS certificates from pcap files or network interfaces, fingerprint TLS client/server interactions with ja3/ja3s
- [**21**星][1y] [C] [the-tcpdump-group/tcpslice](https://github.com/the-tcpdump-group/tcpslice) tcpslice concatenates multiple pcap files together, or extracts time slices from one or more pcap files.
- [**20**星][1y] [Py] [slgobinath/pcap-processor](https://github.com/slgobinath/pcap-processor) 读取和处理pcap文件
- [**18**星][1y] [Go] [dirkduesentrieb/fgsniffer](https://github.com/dirkduesentrieb/fgsniffer) Convert Fortigates "diagnose sniffer" output to pcap files
- [**17**星][2y] [C++] [awgn/captop](https://github.com/awgn/captop) Utility to measure the performance of pcap network interfaces.
- [**17**星][1y] [Py] [dr0op/msfrpcapi](https://github.com/dr0op/msfrpcapi) MSF RPC API调用文档及demo

- [**16**星][1m] [Rust] [courvoif/pcap-file](https://github.com/courvoif/pcap-file) pcap读取与写入
- [**13**星][6y] [C] [ashishraste/arp-dns-attacks](https://github.com/ashishraste/arp-dns-attacks) ARP spoofing, HTTP redirection, DNS spoofing and DNS forging using pcap library
- [**13**星][6y] [Py] [catalyst256/pdfhunter](https://github.com/catalyst256/pdfhunter) Looks for pdf files in pcap files and rebuilds them
- [**12**星][2y] [Py] [johnbergbom/peddlecheap](https://github.com/johnbergbom/peddlecheap) Pcaps for PeddleCheap and implant communication + script for interpreting and decrypting pcaps.
- [**11**星][1y] [JS] [hellvinz/goredis](https://github.com/hellvinz/goredis) live monitoring redis commands via pcap in a browser
- [**11**星][5m] [Py] [teto/mptcpanalyzer](https://github.com/teto/mptcpanalyzer) Tool to help analyze mptcp pcaps
- [**9**星][11m] [C] [cedricol07/p2a](https://github.com/cedricol07/p2a) Parse Pcap for Anomalies
- [**9**星][1y] [Py] [yojiwatanabe/networkalarm](https://github.com/yojiwatanabe/networkalarm) A tool to monitor local network traffic for possible security vulnerabilities. Warns user against possible nmap scans, Nikto scans, credentials sent in-the-clear, and shellshock attacks. Currently supports live monitoring and network capture (pcap) scanning.
- [**6**星][1y] [C] [dns-oarc/pcap-thread](https://github.com/dns-oarc/pcap-thread) pcap辅助库，支持POSIX线程和透明层回调
- [**6**星][2y] [C] [jduncanator/isniff](https://github.com/jduncanator/isniff) Packet capture and network sniffer for Apple iOS devices (iPhone / iPod). An implementation of iOS 5+ Remote Virtual Interface service and pcapd.
- [**3**星][8m] [C] [sizet/packet_capture](https://github.com/sizet/packet_capture) 使用 raw socket 和搭配輔助資料 (ancillary data (PACKET_AUXDATA), 適用於 2.6.21 之後的核心) 監聽和記錄 (pcap 格式) 乙太網路介面上傳送和接收的封包.
- [**2**星][3m] [Py] [lucadivit/pcap_features_extraction](https://github.com/lucadivit/pcap_features_extraction) This program allow you to extract some features from pcap files.
- [**1**星][2y] [C++] [broadsword007/wolfpack](https://github.com/broadsword007/wolfpack) Wolf Pack is a cross-platform network traffic analyzer built using Qt and Library PcapPlusPlus
- [**1**星][2y] [C#] [hidd3ncod3s/pcap2saz](https://github.com/hidd3ncod3s/pcap2saz) Converts HTTP flows in pcap file into SAZ file
- [**1**星][11m] [Py] [techathena/veritas](https://github.com/techathena/veritas) pcap analyser that uses rest api for IP/URL reputation and also for obtaining URL's
- [**1**星][8m] [C++] [z4ziggy/esp8266_pcap_serial](https://github.com/z4ziggy/esp8266_pcap_serial) ESP8266 Sniffer sketch which outputs PCAP data via Serial.
- [**1**星][8m] [C] [z4ziggy/esp8266_pcap_uart](https://github.com/z4ziggy/esp8266_pcap_uart) ESP8266 Sniffer firmware which outputs PCAP data via UART.
- [**1**星][6m] [Py] [tylerp96/pcap-blaster](https://github.com/tylerp96/pcap-blaster) General Purpose PCAP Fuzzer
- [**0**星][1y] [C++] [craiganv/sniffing_stuff](https://github.com/CraigANV/sniffing_stuff) Playing around with pcap, for capturing probe request packets mainly
- [**0**星][1y] [Ruby] [enukane/pcap80211analyzer](https://github.com/enukane/pcap80211analyzer) not-so-smart 802.11 frame pcapng analyzer
- [**0**星][6y] [Py] [hughobrien/wlan-stats](https://github.com/hughobrien/wlan-stats) Tool chain using tshark to pull data from pcaps, further process them in python, and graph the output in R.


### <a id="b239f12aca7aa942b45836032cbef99a"></a>转换


- [**237**星][2y] [Py] [jullrich/pcap2curl](https://github.com/jullrich/pcap2curl) 提取网络数据包中的HTTP 请求，转化为 cURL 指令，用于 replay
- [**191**星][6y] [Py] [andrewf/pcap2har](https://github.com/andrewf/pcap2har) 将pcap文件转为HTTP归档文件
- [**45**星][5y] [securitytube/pcap2xml](https://github.com/securitytube/pcap2xml) 将802.11数据包跟踪转换为XML和SQLITE格式




***


## <a id="8bc2e181f74ba67ec93fd2a13d95cc0c"></a>libpcap


- [**1225**星][4d] [C] [the-tcpdump-group/libpcap](https://github.com/the-tcpdump-group/libpcap) the LIBpcap interface to various kernel packet capture mechanism
- [**783**星][1y] [JS] [node-pcap/node_pcap](https://github.com/node-pcap/node_pcap) libpcap bindings for node
- [**508**星][4d] [C] [pmacct/pmacct](https://github.com/pmacct/pmacct) pmacct is a small set of multi-purpose passive network monitoring tools [NetFlow IPFIX sFlow libpcap BGP BMP RPKI IGP Streaming Telemetry].
- [**323**星][6m] [HTML] [helpsystems/pcapy](https://github.com/helpsystems/pcapy) Pcapy is a Python extension module that interfaces with the libpcap packet capture library.
- [**213**星][5m] [Py] [pynetwork/pypcap](https://github.com/pynetwork/pypcap) python libpcap 模块
- [**96**星][9y] [Py] [dugsong/pypcap](https://github.com/dugsong/pypcap) libpcap的Python包装
- [**67**星][4y] [C] [luigirizzo/netmap-libpcap](https://github.com/luigirizzo/netmap-libpcap) Automatically exported from code.google.com/p/netmap-libpcap
- [**48**星][5y] [Py] [allfro/pcappy](https://github.com/allfro/pcappy) A pure Python libpcap wrapper!
- [**42**星][6y] [Ruby] [sophsec/ffi-pcap](https://github.com/sophsec/ffi-pcap) Ruby FFI bindings for libpcap.
- [**19**星][6d] [Crystal] [maiha/pcap.cr](https://github.com/maiha/pcap.cr) Crystal bindings for libpcap
- [**13**星][10m] [C] [c-bata/xpcap](https://github.com/c-bata/xpcap) Cross-platform Packet Capture which supports Linux and macOS(BSD) in 1000 LOC without depending on libpcap.
- [**8**星][1y] [C] [weaknetlabs/libpcap-80211-c](https://github.com/weaknetlabs/libpcap-80211-c) 802.11 Libpcap and C
- [**4**星][11y] [tadashi/wifi-monitor](https://github.com/tadashi/wifi-monitor) python, py_libpcap, handover
- [**3**星][9d] [Rust] [jmmk/rustcap](https://github.com/jmmk/rustcap) Rust wrapper for libpcap
- [**2**星][3y] [Py] [killswitch-gui/nix-sniffer-examples](https://github.com/killswitch-gui/nix-sniffer-examples) Python ctypes libpcap examples
- [**0**星][3y] [C] [h3pr5tq/get-rssi](https://github.com/h3pr5tq/get-rssi) Linux utility for getting RSSI WiFi of APs to text file. Using Monitor mode, libpcap. Useful for experiments with WiFi (example, localization).


***


## <a id="5303e6ae470e6def3b69d614674a1c46"></a>WinPcap


- [**236**星][4y] [C] [softethervpn/win10pcap](https://github.com/softethervpn/win10pcap) Windows 10  WinPcap (NDIS 6.x 驱动模式)
- [**113**星][4y] [C] [wireshark/winpcap](https://github.com/wireshark/winpcap) WinPcap数据包捕获库
- [**51**星][2y] [Py] [orweis/winpcapy](https://github.com/orweis/winpcapy) A Modern Python wrapper for WinPcap
- [**33**星][2y] [Batchfile] [3gstudent/winpcap_install](https://github.com/3gstudent/winpcap_install) Auto install WinPcap on Windows(command line)
- [**10**星][6m] [C] [sageaxcess/pcap-ndis6](https://github.com/sageaxcess/pcap-ndis6) WinPCAP for NDIS 6.x


***


## <a id="31d28e8b2cf6c06411cd5d178dbd3e77"></a>fiddler


- [**448**星][3d] [C#] [malwareinfosec/ekfiddle](https://github.com/malwareinfosec/ekfiddle) Fiddler Web调试器的框架，用于研究漏洞利用工具包、恶意广告和恶意流量
    - 重复区段: [分析->工具->未分类](#b346105580b0240d693020ce8719ebca) |
- [**297**星][1y] [JS] [xxxily/fiddler-plus](https://github.com/xxxily/fiddler-plus) 自定义的Fiddler规则，多环境切换、解决跨域开发、快速调试线上代码必备|高效调试分析利器
- [**81**星][4y] [C#] [david-risney/csp-fiddler-extension](https://github.com/david-risney/csp-fiddler-extension) Content Security Policy rule collector extension for Fiddler
- [**76**星][2y] [C#] [vahidn/process-proxifier](https://github.com/vahidn/process-proxifier) Using FiddlerCore to add proxy settings to the Windows applications
- [**46**星][8m] [JS] [radenvodka/pentol](https://github.com/radenvodka/pentol) PENTOL - Pentester Toolkit for Fiddler2
- [**24**星][6y] [Py] [emergingthreats/fiddler2pcap](https://github.com/emergingthreats/fiddler2pcap) fiddler插件，输出到pcap
- [**14**星][8m] [C#] [jprknight/exofiddlerextension](https://github.com/jprknight/exofiddlerextension) The Exchange Online Fiddler Extension
- [**2**星][1y] [Go] [progtramder/webproxy](https://github.com/progtramder/webproxy) A fiddler-like webproxy, support sniffing http/https content by implementing 'Sniffer' interface
    - 重复区段: [分析->工具->嗅探](#32739127f0c38d61b14448c66a797098) |


***


## <a id="64f068672e615343db9235f1973d8fba"></a>网络数据包


- [**6630**星][5d] [Py] [networkx/networkx](https://github.com/networkx/networkx) 用于创建、操纵和研究复杂网络的结构，Python包
- [**517**星][2m] [C] [libnet/libnet](https://github.com/libnet/libnet) 创建和注入网络数据包
- [**360**星][3y] [C] [rafael-santiago/pig](https://github.com/rafael-santiago/pig) Linux数据包创建工具
- [**289**星][6d] [C] [troglobit/nemesis](https://github.com/troglobit/nemesis) 网络数据包构造和注入的命令行工具
- [**127**星][1m] [C] [cisco-talos/file2pcap](https://github.com/cisco-talos/file2pcap) 创建各种类型的数据包捕获文件，其中包含指定的任何文件的内容


***


## <a id="eec238a1a2657b70f7bbbe68a4421249"></a>其他


- [**15856**星][] [C] [curl/curl](https://github.com/curl/curl) 命令行工具和库，使用URL语法传输数据，支持HTTP，HTTPS，FTP，FTPS，GOPHER，TFTP，SCP，SFTP，SMB，TELNET，DICT，LDAP，LDAPS，FILE，IMAP，SMTP，POP3，RTSP和RTMP。libcurl提供了许多强大的功能
- [**4152**星][1y] [JS] [kdzwinel/betwixt](https://github.com/kdzwinel/betwixt) 在浏览器外，使用熟悉的Chrome DevTools界面分析网络流量
- [**2363**星][2m] [Lua] [snabbco/snabb](https://github.com/snabbco/snabb) 网络工具包，简单、快速
- [**1211**星][2y] [C] [saminiir/level-ip](https://github.com/saminiir/level-ip) Linux用户模式 TCP/IP 栈，使用 TUN/TAP 设备（操作系统内核中的虚拟网络设备）实现
- [**821**星][11d] [C] [emmericp/ixy](https://github.com/emmericp/ixy) 简单用户空间数据包处理。控制网络适配器，并在用户空间中实现整个驱动程序
- [**686**星][5y] [C] [antirez/hping](https://github.com/antirez/hping) 发送自定义的TCP / IP数据包并显示目标回复，类似ping ICMP回复
- [**675**星][22d] [Py] [kbandla/dpkt](https://github.com/kbandla/dpkt) 快速、简单的数据包创建/解析，带有基本TCP / IP协议的定义
- [**612**星][3y] [Py] [omriher/captipper](https://github.com/omriher/captipper) 分析、探索和恢复HTTP恶意流量，Python工具
- [**511**星][2y] [Py] [sjvasquez/web-traffic-forecasting](https://github.com/sjvasquez/web-traffic-forecasting) 在Kaggle主持的Web流量预测竞赛的解决方案
- [**405**星][13d] [HTML] [thinkst/canarytokens](https://github.com/thinkst/canarytokens) 跟踪网络上的活动和动作
- [**393**星][3m] [Go] [alphasoc/flightsim](https://github.com/alphasoc/flightsim) 生成恶意网络流量并评估控件的实用程序
- [**386**星][3y] [Py] [sensepost/dns-shell](https://github.com/sensepost/dns-shell) 基于DNS的交互式Shell
- [**333**星][1y] [Ruby] [packetfu/packetfu](https://github.com/packetfu/packetfu) 数据包篡改工具。Ruby编写
- [**304**星][2y] [JS] [kristian-lange/net-glimpse](https://github.com/kristian-lange/net-glimpse) 网络流量（以太网和Internet）的实时可视化，以及通过WebSocket从网络接口Steaming header数据
- [**267**星][4m] [Py] [fwkz/riposte](https://github.com/fwkz/riposte) 将应用程序包装在定制的交互式Shell中。Python包
- [**259**星][3m] [Go] [sachaos/tcpterm](https://github.com/sachaos/tcpterm) 数据包可视化
- [**227**星][3y] [Py] [praetorian-code/pyshell](https://github.com/praetorian-code/pyshell) 简化基于Web的命令注入，尽可能地模拟交互式shell的感觉
- [**206**星][3y] [Py] [countercept/doublepulsar-c2-traffic-decryptor](https://github.com/countercept/doublepulsar-c2-traffic-decryptor) 处理PCAP文件，解密发送到DOUBLEPULSAR implant的C2流量
- [**134**星][10m] [C] [yadutaf/tracepkt](https://github.com/yadutaf/tracepkt) 跟踪 Linux 系统 PING 数据包跨网络接口和命名空间的路线，支持 IPv4 及 IPv6
- [**104**星][2y] [Shell] [joarleymoraes/net_guard](https://github.com/joarleymoraes/net_guard) 命令行工具, 利用 ARP 协议检测网络中的未知设备
- [**53**星][3y] [Py] [wraith-wireless/pyric](https://github.com/wraith-wireless/pyric) 无线接口控制器，Python编写
- [**43**星][2d] [Go] [x-way/iptables-tracer](https://github.com/x-way/iptables-tracer) 将跟踪点插入正在运行的配置中，以观察数据包通过iptables链的路径
- [**31**星][5m] [Py] [mechpen/sockdump](https://github.com/mechpen/sockdump) 使用bpf转储unix域套接字流量
- [**21**星][2y] [C] [circl/pcapdj](https://github.com/circl/pcapdj) dispatch pcap files
- [**20**星][5y] [Py] [mk-fg/nflog-zmq-pcap-pipe](https://github.com/mk-fg/nflog-zmq-pcap-pipe) Tool to collect nflog and pipe it to a pcap stream/file over network (0mq) for real-time (or close to) analysis
- [**17**星][5m] [stvemillertime/absolutely-positively-not-hacking-back-with-pcap](https://github.com/stvemillertime/absolutely-positively-not-hacking-back-with-pcap) Streaming Unexpected Network Byte Sequences with High Probability of Blue Screening or Otherwise Crashing Attacker Command-and-Control Nodes
- [**15**星][7m] [C] [magisterquis/pcapknock](https://github.com/magisterquis/pcapknock) Watches for trigger packets, runs commands or spawns a shell
- [**15**星][7y] [Py] [opensecurityresearch/clipcaptcha](https://github.com/opensecurityresearch/clipcaptcha) A Tool for Impersonating CAPTCHA Providers
- [**14**星][2m] [OCaml] [mirage/ocaml-pcap](https://github.com/mirage/ocaml-pcap) OCaml code for generating and analysing pcap (packet capture) files
- [**13**星][19d] [C++] [fkie-cad/pcapfs](https://github.com/fkie-cad/pcapfs) A FUSE module to mount captured network data
- [**11**星][3y] [Perl] [icgc-tcga-pancancer/pcap-core](https://github.com/icgc-tcga-pancancer/pcap-core) Legacy, see cancerit/PCAP-core: NGS reference implementations and helper code for the IGCG/TCGA Pan-Cancer Analysis Project
- [**7**星][6y] [JS] [sparrowprince/webpcap](https://github.com/sparrowprince/webpcap) A web-based packet analyzer (client/server architecture). Useful for analyzing distributed applications or embedded devices.
- [**4**星][6y] [C] [hbock/libairpcap-nl](https://github.com/hbock/libairpcap-nl) Implementation of AirPcap library, targetting the NL80211 protocol.
- [**3**星][4y] [Py] [reyammer/csawctf-quals-2015-pcapin](https://github.com/reyammer/csawctf-quals-2015-pcapin) 


# <a id="837c9f22a3e1bb2ce29a0fb2bcd90b8f"></a>翻墙&&GFW


***


## <a id="af9d2b4988d35a2a634c042a1c66bb8c"></a>工具


### <a id="fe72fb9498defbdbb98448511cd1eaca"></a>未分类


- [**2937**星][12m] [Shell] [91yun/serverspeeder](https://github.com/91yun/serverspeeder) 锐速破解版


### <a id="6e28befd418dc5b22fb3fd234db322d3"></a>翻墙


- [**13874**星][10d] [JS] [bannedbook/fanqiang](https://github.com/bannedbook/fanqiang) 翻墙-科学上网
- [**11682**星][13d] [getlantern/download](https://github.com/getlantern/download) Lantern官方版本下载 蓝灯 翻墙 科学上网 外网 加速器 梯子 路由
- [**3960**星][7d] [hq450/fancyss_history_package](https://github.com/hq450/fancyss_history_package) 科学上网插件的离线安装包储存在这里
- [**3121**星][21d] [Shell] [softwaredownload/openwrt-fanqiang](https://github.com/softwaredownload/openwrt-fanqiang) 最好的路由器翻墙、科学上网教程—OpenWrt—shadowsocks
- [**1261**星][1y] [PHP] [you2php/delete](https://github.com/you2php/delete) （迫于压力，本项目停止维护，请尽快fork代码。1月1日之后删除项目）[免翻墙工具]A free and open-source youtube video proxy script [Written in PHP]
- [**982**星][3y] [Py] [dowsnature/dowsdns](https://github.com/dowsnature/dowsdns) 快速翻跃中国防火墙
- [**847**星][3y] [C] [examplecode/mproxy](https://github.com/examplecode/mproxy) c 语言实现的一个最小的http代理，支持翻墙
- [**504**星][2m] [hugetiny/awesome-vpn](https://github.com/hugetiny/awesome-vpn) A curated list of awesome free VPNs and proxies.免费的代理,科学上网,翻墙，梯子大集合
- [**360**星][2y] [udpsec/awesome-vpn](https://github.com/udpsec/awesome-vpn) 科学上网的有趣项目集锦，欢迎大家pr自己喜欢的项目到这里。
- [**341**星][13d] [Go] [getlantern/lantern](https://github.com/getlantern/lantern) Lantern官方版本下载 蓝灯 翻墙 科学上网 外网 加速器 梯子 路由 lantern censorship-circumvention censorship gfw vpn accelerator
- [**315**星][7m] [waylau/vpngate-mirrors](https://github.com/waylau/vpngate-mirrors) Here are the newset VPN Gate web site’s mirrors .With the VPN Gate, you can get through your government's firewall to browse restricted websites.提供最新的访问 VPN Gate 镜像网站,通过使用 VPN 自由访问互联网(翻墙)！
- [**266**星][3y] [waylau/free-vpn](https://github.com/waylau/free-vpn) We Provide Newset Free VPN Service. PC, mobile phones and network appliances, no software installation. With the VPN Service,you can get through your government's firewall to browse restricted websites.提供最新的免费的 VPN 服务,通过使用 VPN 自由访问互联网(翻墙)！无论是PC端，移动端都无需安装客户端。
- [**250**星][17d] [HTML] [gfw-breaker/open-proxy](https://github.com/gfw-breaker/open-proxy) 一键部署被墙网站反向代理; 免翻墙访问被禁网站
- [**132**星][2y] [sky8964/home](https://github.com/sky8964/home) 【墙外到墙内搬运工】郭文贵 推特党 兲朝浮世绘 小民之心 辛灏年 曹长青 袁红冰 旗袍 袁腾飞 翻墙 科学上网 | 搬运工 自由 民主 法治 宪政 人权 平等 视频 音频 文字版 在线 播放 下载 民运 维权 王岐山 孟建柱 孙力军 傅振华 江棉恒 江泽民 习近平 温家宝 王芳 董卿 杨澜 周小平 吴征 唐柏桥 e租宝 泛亚 共产党 赵家 盜国贼 内幕 黑暗 灾难 专政 上访 游行 暴乱 欺骗 谎言 腐败 通奸 权贵 马航 老兵 活摘 启蒙 墙外 墙内 防火墙 防火长城 功夫网 党文化 民阵 爆料 九评 杨建利 郭宝胜 昭明 反共 法轮功 自媒体 Youtube 油管 推特 Twitter 网盘 传播 关注 五毛 自干五 特务 红二代 红三代 官二代 土共 共匪
- [**85**星][2y] [Py] [wanjunzh/ssct](https://github.com/wanjunzh/ssct) shadowsocks 包装器，用于持续绕过防火墙
- [**59**星][3y] [Go] [jijinggang/golocproxy](https://github.com/jijinggang/golocproxy) 轻量级超强反向代理软件，用go语言开发，通过公共可知的服务器端口代理，把局域网内任何主机的本地服务发布给局域网外的用户，可用来跨越各种防火墙。
- [**58**星][7m] [JS] [yzyjim/shadowsocks-back-china-pac](https://github.com/yzyjim/shadowsocks-back-china-pac) Shadowsocks翻墙回国PAC规则
- [**57**星][8d] [zscdumin/vpn](https://github.com/zscdumin/vpn) ShadowSocks 翻墙（收费服务器合租套餐：150元/年、50元/季度、20元/月，需要的可以联系我）
- [**46**星][1y] [Shell] [witee/note-shadowsocks](https://github.com/witee/note-shadowsocks) 公司网关使用 shadowsocks 搭建翻墙网络
- [**45**星][4y] [Py] [cdhigh/forwarder](https://github.com/cdhigh/forwarder) 简单的HTTP请求转发服务器，配合KIndleEar翻入墙内或绕过部分网站对GAE的IP地址的封锁。灵感来自
- [**41**星][11m] [C++] [guohaodongpu/huangyexingdong-bug](https://github.com/guohaodongpu/huangyexingdong-bug) 荒野行动辅助，透视穿墙。我把源码发出来，
- [**40**星][2y] [Java] [jwnie/proxyservice](https://github.com/jwnie/proxyservice) 抓取网上公开代理，维护可供爬虫使用的IP池，区分墙内墙外、http/https/socks代理。
- [**38**星][4m] [Lua] [wubonetcn/luawaf](https://github.com/wubonetcn/luawaf) A secure and privately deployable web application firewall(WAF).一个安全、可私有部署的Web应用防火墙(WAF)。
- [**32**星][3y] [archimboldimao/surgeconfig](https://github.com/archimboldimao/surgeconfig) 这是我日常使用 Surge 配置 Shadowsocks 代理翻墙的文件。
- [**30**星][4y] [comeforu2012/fq_faq](https://github.com/comeforu2012/fq_faq) 翻墙常见问题
- [**27**星][5m] [HTML] [firewalltutor/firewalltutor.github.io](https://github.com/firewalltutor/firewalltutor.github.io) fire wall tutor 自建梯子教程 Google 翻墙 科学上网 代理工具 一键安装
- [**24**星][1y] [PS] [jiangxianli/googlehosttool](https://github.com/jiangxianli/googlehosttool) 一键添加最新google hosts文件到本地hosts文件中，google 翻墙访问工具，适用windows、linux、mac
- [**21**星][2y] [Py] [sirpsycho/firecall](https://github.com/sirpsycho/firecall) firecall: 直接向Cisco ASA防火墙发送命令, 无需登录防火墙后再做修改


### <a id="e9cc4e00d5851a7430a9b28d74f297db"></a>GFW


- [**14867**星][2m] [gfwlist/gfwlist](https://github.com/gfwlist/gfwlist) gfwlist
- [**5116**星][3d] [ASP] [hq450/fancyss](https://github.com/hq450/fancyss) fancyss is a project providing tools to across the GFW on asuswrt/merlin based router.
- [**4922**星][1y] [Go] [yinghuocho/firefly-proxy](https://github.com/yinghuocho/firefly-proxy) A proxy software to help circumventing the Great Firewall.
- [**3712**星][] [acl4ssr/acl4ssr](https://github.com/acl4ssr/acl4ssr) SSR 去广告ACL规则/SS完整GFWList规则，Telegram频道订阅地址
- [**3632**星][3m] [C++] [trojan-gfw/trojan](https://github.com/trojan-gfw/trojan) An unidentifiable mechanism that helps you bypass GFW.
- [**2781**星][2y] [C] [seclab-ucr/intang](https://github.com/seclab-ucr/intang) research project for circumventing the "TCP reset attack" from the Great Firewall of China (GFW) by disrupting/desynchronizing the TCP Control Block (TCB) on the censorship devices.
- [**1852**星][1y] [Py] [jinnlynn/genpac](https://github.com/jinnlynn/genpac) PAC/Dnsmasq/Wingy file Generator, working with gfwlist, support custom rules.
- [**1407**星][8d] [Java] [chinashiyu/gfw.press](https://github.com/chinashiyu/gfw.press) GFW.Press新一代军用级高强度加密抗干扰网络数据高速传输软件
- [**1195**星][7y] [Py] [mothran/mongol](https://github.com/mothran/mongol) A simple python tool to pinpoint the IP addresses of machines working for the Great Firewall of China.
- [**626**星][4y] [JS] [n0wa11/gfw_whitelist](https://github.com/n0wa11/gfw_whitelist) A Pac File of the Whitelisted Websites for the Great Firewall of China (GFW)
- [**613**星][8m] [Shell] [cokebar/gfwlist2dnsmasq](https://github.com/cokebar/gfwlist2dnsmasq) A shell script which convert gfwlist into dnsmasq rules. Python version:
- [**350**星][22d] [Shell] [fanyueciyuan/eazy-for-ss](https://github.com/fanyueciyuan/eazy-for-ss) A Bypassgfw Collection
- [**290**星][3y] [Py] [cokebar/gfwlist2dnsmasq_python](https://github.com/cokebar/gfwlist2dnsmasq_python) Just another python script to auto-generate dnsmasq ipset rules using gfwlist. Shell script version:
- [**269**星][6m] [Shell] [yangchuansheng/love-gfw](https://github.com/yangchuansheng/love-gfw) 
- [**213**星][1m] [Shell] [zfl9/gfwlist2privoxy](https://github.com/zfl9/gfwlist2privoxy) 将 gfwlist.txt（Adblock Plus 规则）转换为 privoxy.action
- [**167**星][13d] [Py] [paloaltonetworks/ansible-pan](https://github.com/paloaltonetworks/ansible-pan) Ansible modules for Palo Alto Networks NGFWs
- [**148**星][11m] [Shell] [aturl/awesome-anti-gfw](https://github.com/aturl/awesome-anti-gfw) 突破网络审查和封锁的开源工具清单。
- [**123**星][7y] [steamedfish/gfwiplist](https://github.com/steamedfish/gfwiplist) 可用于翻墙路由表的墙外IP列表
- [**116**星][2y] [gfwlist/tinylist](https://github.com/gfwlist/tinylist) Tiny version of gfwlist, focusing on common websites ONLY
- [**102**星][12m] [searking/ggfwzs_in_hack](https://github.com/searking/ggfwzs_in_hack) hack VIP for chrome-extension 谷歌访问助手
- [**86**星][22d] [Go] [asche910/flynet](https://github.com/asche910/flynet) A powerful TCP/UDP tool, which support socks5 proxy by tcp and udp, http proxy and NAT traversal. This tool can help you bypass gfw easily
- [**79**星][3m] [comwrg/fuck-gfw](https://github.com/comwrg/fuck-gfw) 记录各个包管理器使用代理的方法, 因为GFW已经浪费了已经数不清的时间, FUCK GFW
- [**55**星][3m] [Java] [arloor/httpproxy](https://github.com/arloor/httpproxy) a netty-based http proxy that breaks the GFW。
- [**30**星][10m] [smallstrong0/ss](https://github.com/smallstrong0/ss) I spend many ways to break the GFW,and this is my destination.
- [**28**星][3y] [iqiancheng/shadowsocks-awesome](https://github.com/iqiancheng/shadowsocks-awesome) 一个实时更新的实用gfwlist清单。用于ss的PAC自动分流。
- [**26**星][2m] [HTML] [trojan-tutor/trojan-tutor.github.io](https://github.com/trojan-tutor/trojan-tutor.github.io) trojan 教程 自建梯子教程 trojan教程 trojan-gfw 科学上网 代理工具 翻墙 Ubuntu Debian 小白教程 https伪装
- [**24**星][13d] [kylebing/sslist](https://github.com/kylebing/sslist) 优化访问速度的小型 gfw (Great Fire Wall) 规则列表 gfwlist
- [**20**星][t] [Py] [natescarlet/gfwlist.acl](https://github.com/natescarlet/gfwlist.acl) 
- [**18**星][5d] [JS] [wri/gfw-mapbuilder](https://github.com/wri/gfw-mapbuilder) Template for the GFW Map Builder that is available through ArcGIS Online, as a stand-alone web application, & a library to build custom Forest Atlas web applications
- [**17**星][6d] [awesome-doge/breaking-gfw-book](https://github.com/awesome-doge/breaking-gfw-book) 整理所有的翻牆方法，持續更新....歡迎PR
- [**15**星][3m] [Shell] [zfl9/gfwlist2dnsmasq](https://github.com/zfl9/gfwlist2dnsmasq) 将 gfwlist.txt（Adblock Plus 规则）转换为 dnsmasq.conf
- [**11**星][1y] [C#] [limiqs/litrojan](https://github.com/limiqs/litrojan) Litrojan - Lite User Interface for Trojan, an unidentifiable mechanism that helps you bypass GFW.
- [**11**星][1y] [Shell] [sutra/gfwlist2dnsmasq.awk](https://github.com/sutra/gfwlist2dnsmasq.awk) Convert gfwlist into dnsmasq configuration file.
- [**6**星][5m] [Shell] [jm33-m0/w411brk](https://github.com/jm33-m0/w411brk) linux透明翻墙代理搭建 / some tools for gfw evasion
- [**4**星][2y] [Go] [cn4/gfwlist2glider](https://github.com/cn4/gfwlist2glider) gfwlist to glider rule file
- [**3**星][2y] [Py] [fpfeng/gfwlist2potatso](https://github.com/fpfeng/gfwlist2potatso) transfer gfwlist to potatso rulesets
- [**2**星][8m] [JS] [lifenjoiner/ezx-pac](https://github.com/lifenjoiner/ezx-pac) ez (Easylist) + x (gfwlist) pac (Proxy Auto-Config) file template and auto generating for IE/EDGE and firefox
- [**1**星][8m] [C++] [guidovranken/gfwx-fuzzers](https://github.com/guidovranken/gfwx-fuzzers) 




***


## <a id="8c94b343a7f1fb63a1ac538d032425a0"></a>文章




# <a id="b03a7c05fd5b154ad593b6327578718b"></a>匿名网络


***


## <a id="6e80463404d46f0493cf6e84597e4b5c"></a>工具


### <a id="f0979cd783d1d455cb5e3207d574aa1e"></a>未分类


- [**90**星][1y] [Py] [thelinuxchoice/anonymouse](https://github.com/thelinuxchoice/anonymouse) Python script to send anonymous email using anonymouse.org
- [**36**星][11m] [Shell] [keeganjk/kali-anonymous](https://github.com/keeganjk/kali-anonymous) 
- [**7**星][2y] [HTML] [surfer77/becominganonymous.com](https://github.com/surfer77/becominganonymous.com) The Becoming Anonymous website, you are welcome to contribute!
- [**5**星][4y] [HTML] [auth0-samples/auth0-anonymous-tracker](https://github.com/auth0-samples/auth0-anonymous-tracker) A cross-site anonymous user tracker.
- [**4**星][6m] [Go] [fentec-project/fe-anonymous-heatmap](https://github.com/fentec-project/fe-anonymous-heatmap) A demonstration of creating a location heatmap from encrypted data by using functional encryption.


### <a id="e99ba5f3de02f68412b13ca718a0afb6"></a>Tor&&&Onion&&洋葱


- [**3665**星][21d] [Py] [micahflee/onionshare](https://github.com/micahflee/onionshare) Securely and anonymously send and receive files, and publish onion sites
- [**2375**星][18d] [security-onion-solutions/security-onion](https://github.com/security-onion-solutions/security-onion) Linux distro for intrusion detection, enterprise security monitoring, and log management
- [**1731**星][3y] [Go] [s-rah/onionscan](https://github.com/s-rah/onionscan) OnionScan is a free and open source tool for investigating the Dark Web.
- [**1211**星][t] [ObjC] [onionbrowser/onionbrowser](https://github.com/onionbrowser/onionbrowser) An open-source, privacy-enhancing web browser for iOS, utilizing the Tor anonymity network
    - 重复区段: [iOS->工具](#692d86299dedab073fbb6144a5b2bd64) |
- [**930**星][9m] [C#] [lachesis/scallion](https://github.com/lachesis/scallion) 基于GPU的Onion Hash生成器
- [**761**星][7y] [grugq/portal](https://github.com/grugq/portal) Personal Onion Router To Assure Liberty
- [**560**星][7y] [C] [katmagic/shallot](https://github.com/katmagic/shallot) 为您的隐藏服务创建自定义的.onion地址
- [**492**星][1m] [Shell] [trimstray/multitor](https://github.com/trimstray/multitor) Shell脚本, 创建多个Tor实例, 并使用HAProxy实现负载均衡
    - 重复区段: [代理->工具->HAProxy](#d3069cac6097830d12f5933c9c8b7a77) |
- [**436**星][11d] [JS] [ayms/node-tor](https://github.com/ayms/node-tor) Javascript implementation of the Tor (or Tor like) anonymizer project (The Onion Router)
- [**424**星][3m] [Py] [nullhypothesis/exitmap](https://github.com/nullhypothesis/exitmap) A fast and modular scanner for Tor exit relays.
- [**423**星][3d] [Awk] [alecmuffett/eotk](https://github.com/alecmuffett/eotk) Enterprise Onion Toolkit
- [**419**星][1y] [Go] [kragniz/tor-controller](https://github.com/kragniz/tor-controller) Run Tor onion services on Kubernetes
- [**416**星][13d] [C] [deeponion/deeponion-legacy](https://github.com/deeponion/deeponion-legacy) Official Source Repo for DeepOnion - Anonymous Cryptocurrency on TOR Network (legacy)
- [**385**星][20d] [Py] [maqp/tfc](https://github.com/maqp/tfc) Tinfoil Chat - Onion-routed, endpoint secure messaging system
- [**379**星][9m] [Py] [k4m4/onioff](https://github.com/k4m4/onioff) url检测器，深度检测网页链接
- [**370**星][4d] [Py] [realgam3/pymultitor](https://github.com/realgam3/pymultitor) pymultitor：Python 多线程 Tor 脚本
- [**369**星][2m] [Py] [micahflee/torbrowser-launcher](https://github.com/micahflee/torbrowser-launcher) Securely and easily download, verify, install, and launch Tor Browser in Linux
- [**354**星][4d] [Py] [alecmuffett/real-world-onion-sites](https://github.com/alecmuffett/real-world-onion-sites) This is a list of substantial, commercial-or-social-good mainstream websites which provide onion services.
- [**316**星][2m] [Shell] [brainfucksec/kalitorify](https://github.com/brainfucksec/kalitorify) 用于Kali的shell脚本，使用iptables创建通过Tor网络的透明代理。可以执行各种检查：检查Tor出口节点（即在Tor代理下时的公共IP），或者Tor已正确配置，可以检查服务和网络设置。
- [**313**星][2y] [Shell] [milesrichardson/docker-onion-nmap](https://github.com/milesrichardson/docker-onion-nmap) 使用 nmap 扫描 Tor 隐藏网络的Docker 镜像。基于 alpine，使用proxychains 做 nmap 的包装
- [**280**星][6m] [Py] [mthbernardes/rsg](https://github.com/mthbernardes/rsg) 多种方式生成反向Shell
- [**279**星][2y] [Py] [dirtyfilthy/freshonions-torscraper](https://github.com/dirtyfilthy/freshonions-torscraper) Fresh Onions is an open source TOR spider / hidden service onion crawler hosted at zlal32teyptf4tvi.onion
- [**268**星][10m] [C++] [wbenny/mini-tor](https://github.com/wbenny/mini-tor) 使用 MSCNG/CryptoAPI 实现的 Tor 协议
- [**265**星][9d] [Go] [lightningnetwork/lightning-onion](https://github.com/lightningnetwork/lightning-onion) Onion Routed Micropayments for the Lightning Network
- [**262**星][2m] [C] [basil00/torwall](https://github.com/basil00/torwall) Tallow - Transparent Tor for Windows
- [**254**星][3y] [Haskell] [galoisinc/haskell-tor](https://github.com/galoisinc/haskell-tor) A Haskell implementation of the Tor protocol.
- [**251**星][4y] [Py] [whitepacket/zib-trojan](https://github.com/whitepacket/zib-trojan) The Open Tor Botnet (ZIB); Python-based forever-FUD IRC Trojan
- [**245**星][3y] [Py] [donnchac/onionbalance](https://github.com/donnchac/onionbalance) OnionBalance provides load-balancing and redundancy for Tor hidden services
- [**235**星][2d] [C] [ipsn/go-libtor](https://github.com/ipsn/go-libtor) Self-contained Tor from Go
- [**223**星][6m] [Py] [ruped24/toriptables2](https://github.com/ruped24/toriptables2) Tor Iptables script is an anonymizer that sets up iptables and tor to route all services and traffic including DNS through the Tor network.
- [**220**星][2y] [Py] [vlall/darksearch](https://github.com/vlall/darksearch) query cached onion sites, irc chatrooms, various pdfs, game chats, blackhat forums etc
- [**197**星][3m] [Py] [meejah/txtorcon](https://github.com/meejah/txtorcon) Twisted-based asynchronous Tor control protocol implementation. Includes unit-tests, examples, state-tracking code and configuration abstraction.
- [**196**星][1m] [C] [cathugger/mkp224o](https://github.com/cathugger/mkp224o) vanity address generator for tor onion v3 (ed25519) hidden services
- [**161**星][3y] [Shell] [hiroshimanrise/anonym8](https://github.com/hiroshimanrise/anonym8) Sets Transparent proxy tunnel through Tor, I2P, Privoxy, Polipo and modify DNS; Include Anonymizing Relay Monitor (arm), macchanger and wipe (Cleans ram/cache & swap-space) features, ID spoofing has never been so easy.
- [**147**星][2y] [C] [r-a-w/torproxy](https://github.com/r-a-w/torproxy) TorProxy is a tool which uses netfilter hooks in the linux kernel to route all network traffic through the Tor network
- [**141**星][2y] [Py] [gumblex/ptproxy](https://github.com/gumblex/ptproxy) Turn any pluggable transport for Tor into an obfuscating TCP tunnel.
- [**140**星][27d] [Py] [blueudp/deep-explorer](https://github.com/blueudp/deep-explorer) Deep Explorer is a tool developed in python which purpose is the search of hidden services in tor network, using Ahmia Browser and crawling the links obtained
- [**131**星][2y] [Shell] [coldhakca/tor-relay-bootstrap](https://github.com/coldhakca/tor-relay-bootstrap) Script to bootstrap a Debian server to be a set-and-forget Tor relay
- [**130**星][1y] [Py] [blacknbunny/mcreator](https://github.com/blacknbunny/mcreator) 反向Shell生成器, 自带AV绕过技术
- [**122**星][2y] [Ruby] [ehloonion/onionmx](https://github.com/ehloonion/onionmx) Onion delivery, so delicious
- [**119**星][2y] [alecmuffett/the-onion-diaries](https://github.com/alecmuffett/the-onion-diaries) Blog-type notes about building Onion sites
- [**119**星][28d] [C#] [joelverhagen/torsharp](https://github.com/joelverhagen/torsharp) Use Tor for your C# HTTP clients. Tor + Privoxy =
- [**114**星][12m] [C] [opsxcq/docker-tor-hiddenservice-nginx](https://github.com/opsxcq/docker-tor-hiddenservice-nginx) Easily setup a hidden service inside the Tor network
- [**114**星][8y] [C++] [moxie0/tortunnel](https://github.com/moxie0/tortunnel) A partial Onion Proxy implementation that's designed to build single-hop circuits through Tor exit nodes
- [**109**星][1m] [Py] [t0thkr1s/revshellgen](https://github.com/t0thkr1s/revshellgen) Reverse shell generator written in Python 3.
- [**107**星][2m] [ajvb/awesome-tor](https://github.com/ajvb/awesome-tor) A list of awesome Tor related projects, articles, papers, etc
- [**104**星][3m] [Ruby] [dryruby/tor.rb](https://github.com/dryruby/tor.rb) Tor.rb is a Ruby library for interacting with the Tor anonymity network.
- [**102**星][7m] [HTML] [ahmia/search](https://github.com/ahmia/search) Ahmia - Search Engine for onion services.
- [**95**星][11m] [Shell] [antitree/private-tor-network](https://github.com/antitree/private-tor-network) Run an isolated instance of a tor network in Docker containers
- [**95**星][2y] [guardianproject/tor-browser](https://github.com/guardianproject/tor-browser) UPDATE: Orfox is being replaced by Tor Browser for Android. All future work and comments will be handled by Tor Project.
    - 重复区段: [Android->工具](#863839860fab4b8601905205cac9b54f) |
- [**94**星][22d] [Go] [lu4p/torat](https://github.com/lu4p/torat) ToRat is a Remote Administation tool written in Go using Tor as a transport mechanism and RPC for communication
- [**88**星][9m] [Shell] [jseidl/multi-tor](https://github.com/jseidl/multi-tor) Shellscript opens multiple TOR instances
- [**80**星][2m] [JS] [garethflowers/tor-browser-portable](https://github.com/garethflowers/tor-browser-portable) Portable version of the Tor Browser, for Windows
- [**79**星][11m] [Makefile] [onioniot/openwrt-packages](https://github.com/onioniot/openwrt-packages) Onion Packages Feed for OpenWRT
- [**79**星][3y] [C++] [torps/torps](https://github.com/torps/torps) The Tor Path Simulator
- [**78**星][6y] [Shell] [breadtk/onion_pi](https://github.com/breadtk/onion_pi) Make a Raspberry Pi into a Anonymizing Tor Proxy!
- [**78**星][3y] [Go] [cyphar/mkonion](https://github.com/cyphar/mkonion) A simple way to create a Tor onion service for existing Docker containers.
- [**76**星][4y] [PHP] [dunglas/php-torcontrol](https://github.com/dunglas/php-torcontrol) PHP TorControl, a library to control TOR
- [**76**星][3m] [Shell] [edu4rdshl/tor-router](https://github.com/edu4rdshl/tor-router) A tool that allow you to make TOR your default gateway and send all internet connections under TOR (as transparent proxy) for increase privacy/anonymity without extra unnecessary code.
- [**74**星][4y] [Go] [dlion/guesstor](https://github.com/dlion/guesstor) Bruteforces [.onion] domains
- [**74**星][20d] [JS] [ralphwetzel/theonionbox](https://github.com/ralphwetzel/theonionbox) Dashboard to monitor Tor node operations
- [**72**星][4y] [david415/ansible-tor](https://github.com/david415/ansible-tor) An Ansible role for using tor!
- [**68**星][8d] [Shell] [brainfucksec/archtorify](https://github.com/brainfucksec/archtorify) Transparent proxy through Tor for Arch Linux OS
- [**66**星][2m] [Java] [lmax-exchange/disruptor-proxy](https://github.com/LMAX-Exchange/disruptor-proxy) Byte-code generator to create Disruptor-backed proxies
- [**64**星][7m] [ObjC] [javerous/torchat-mac](https://github.com/javerous/torchat-mac) macOS native TorChat client
- [**60**星][5y] [Go] [jgrahamc/torhoney](https://github.com/jgrahamc/torhoney) Gets the list of TOR exit nodes and matches them with Project Honeypot data
- [**60**星][8m] [Py] [viele/onionskinrenderer](https://github.com/viele/onionskinrenderer) This is an Onion Skin Renderer for Autodesk Maya
- [**57**星][9m] [Go] [openbazaar/go-onion-transport](https://github.com/openbazaar/go-onion-transport) Tor onion transport for IPFS
- [**57**星][3m] [Py] [gosecure/freshonions-torscraper](https://github.com/gosecure/freshonions-torscraper) Fresh Onions is an open source TOR spider / hidden service onion crawler
- [**54**星][2y] [Java] [mirsamantajbakhsh/onionharvester](https://github.com/mirsamantajbakhsh/onionharvester) A small TOR Onion Address harvester for checking if the address is available or not.
- [**53**星][2y] [Go] [cmars/ormesh](https://github.com/cmars/ormesh) onion-routed mesh
- [**53**星][2y] [Py] [inurlx/cloudkill3r](https://github.com/inurlx/cloudkill3r) CLOUDKiLL3R bypasses Cloudflare protection service via TOR Browser using crimeflare !
- [**50**星][4y] [C++] [sri-csl/stegotorus](https://github.com/sri-csl/stegotorus) A Camouflage Proxy for the Tor Anonymity System
- [**50**星][1y] [JS] [lukechilds/onionite](https://github.com/lukechilds/onionite) Explore the Tor network
- [**49**星][13d] [C] [rahra/onioncat](https://github.com/rahra/onioncat) Official repository of OnionCat, the VPN adapter for Tor and I2P.
- [**46**星][6d] [Shell] [security-onion-solutions/securityonion-saltstack](https://github.com/security-onion-solutions/securityonion-saltstack) 
- [**44**星][6d] [JS] [loki-project/loki-messenger](https://github.com/loki-project/loki-messenger) Loki Messenger - Onion routing based messenger
- [**43**星][10m] [PHP] [danwin/onion-link-list](https://github.com/danwin/onion-link-list) A set of scripts to list tor hidden services
- [**43**星][6m] [Shell] [infosecn1nja/ycsm](https://github.com/infosecn1nja/ycsm) This is a quick script installation for resilient redirector using nginx reverse proxy and letsencrypt compatible with some popular Post-Ex Tools (Cobalt Strike, Empire, Metasploit, PoshC2).
- [**43**星][2y] [Py] [mthbernardes/ipchecker](https://github.com/mthbernardes/ipchecker) Check if a IP is from tor or is a malicious proxy
- [**38**星][2y] [Java] [adrianbzg/twitter-follow-exploit](https://github.com/adrianbzg/twitter-follow-exploit) Automated Twitter mass account creation and follow using Selenium and Tor VPN
- [**38**星][5y] [Shell] [jivoi/ansible-pentest-with-tor](https://github.com/jivoi/ansible-pentest-with-tor) Use Tor for anonymous scanning with nmap
- [**37**星][1m] [Shell] [security-onion-solutions/securityonion-elastic](https://github.com/security-onion-solutions/securityonion-elastic) Security Onion Elastic Stack
- [**36**星][4y] [Java] [onionmail/onionmail](https://github.com/onionmail/onionmail) TOR Mail encrypted server for Hidden Services
- [**36**星][2m] [Shell] [itshaadi/torbox](https://github.com/itshaadi/torbox) Container-based Tor access point (Anonymizing Middlebox).
- [**35**星][5y] [Py] [miserlou/onionchat](https://github.com/miserlou/onionchat) Anonymous chat. No Javascript.
- [**32**星][5m] [Py] [mikemeliz/torcrawl.py](https://github.com/mikemeliz/torcrawl.py) Crawl and extract (regular or onion) webpages through TOR network
- [**31**星][2y] [KiCad Layout] [5n44p/omega-dock-new](https://github.com/5n44p/omega-dock-new) A dock for Onion omega, omega2 and omega2+. It features: Microusb for power supply, USB host, Ethernet
- [**31**星][5y] [Py] [glamrock/stormy](https://github.com/glamrock/stormy) Easy creation of Tor Hidden Services
- [**31**星][5y] [Shell] [patrickod/docker-tor-hidden-services](https://github.com/patrickod/docker-tor-hidden-services) A simple way of exposing any docker container as a tor hidden service
- [**30**星][1m] [Shell] [security-onion-solutions/securityonion-setup](https://github.com/security-onion-solutions/securityonion-setup) 
- [**29**星][4y] [Makefile] [radicallyopensecurity/netaidkit](https://github.com/radicallyopensecurity/netaidkit) Standalone VPN/Tor WiFi router for journalists and activists
    - 重复区段: [VPN->工具](#d62a971d37c69db9f3b9187318c3921a) |
- [**28**星][3y] [Py] [baltimorechad/pyonionscan](https://github.com/baltimorechad/pyonionscan) Dark Web OSINT With Python and OnionScan
- [**28**星][5y] [C++] [yawning/obfsclient](https://github.com/yawning/obfsclient) A C++11 obfs2/3 Tor managed pluggable transport client
- [**27**星][3y] [Py] [duk3luk3/onion-py](https://github.com/duk3luk3/onion-py) Python wrapper for the OnionOO tor status API
- [**27**星][9m] [Go] [nullhypothesis/sybilhunter](https://github.com/nullhypothesis/sybilhunter) Hunting for Sybils and anomalies in archived Tor network data.
- [**27**星][1m] [Shell] [security-onion-solutions/securityonion-docker](https://github.com/security-onion-solutions/securityonion-docker) Docker files for Security Onion
- [**25**星][2y] [Py] [absingh31/tor_spider](https://github.com/absingh31/tor_spider) Python project to crawl and scrap the lesser known deep web or one can say dark web. Just provide the onion link and get started.
- [**24**星][6m] [Py] [bunseokbot/darklight](https://github.com/bunseokbot/darklight) Engine for collecting onion domains and crawling from webpage based on Tor network
- [**24**星][7m] [ObjC] [mtigas/onionbrowser](https://github.com/mtigas/onionbrowser) personal fork for testing and submitting diffs for review. you DEFINITELY want the OnionBrowser/OnionBrowser repo instead
- [**24**星][2y] [Shell] [oniondecoy/installer](https://github.com/oniondecoy/installer) A platform to run private unannounced Honeypots as Tor Hidden Services (aka Onion Decoys) inside the Tor Network.
- [**23**星][] [C++] [deeponion/deeponion](https://github.com/deeponion/deeponion) Official Source Repo for DeepOnion - Anonymous Cryptocurrency on TOR
- [**22**星][5m] [Java] [guardianproject/jtorctl](https://github.com/guardianproject/jtorctl) deprecated fork of Java Tor Control Library
- [**22**星][4y] [Go] [jgrahamc/torexit](https://github.com/jgrahamc/torexit) Small program to read lists of Tor exit nodes and draw picture showing when they join/leave list
- [**22**星][2y] [Py] [mdegrazia/onionpeeler](https://github.com/mdegrazia/onionpeeler) Python script to batch query the Tor Relays and Bridges
- [**21**星][3y] [Go] [rdkr/oniongen-go](https://github.com/rdkr/oniongen-go) 
- [**21**星][3y] [Go] [shakenetwork/onionscan](https://github.com/shakenetwork/onionscan) OnionScan暗网爬虫是一个免费的开源工具，用于调查黑网。 OnionScan is a free and open source tool for investigating the Dark Web
- [**20**星][11m] [Go] [nogoegst/onionize](https://github.com/nogoegst/onionize) create an onion site from a directory, file, zip or an HTTP(S) site
- [**20**星][5d] [Py] [beardog108/onionr](https://github.com/beardog108/onionr) Private Decentralized Communication Network
- [**19**星][4m] [Go] [mahrud/caddy-altonions](https://github.com/mahrud/caddy-altonions) Opportunistic Onions plugin for Caddy
- [**18**星][11m] [Go] [ciehanski/onionbox](https://github.com/ciehanski/onionbox) Send and receive files securely through Tor.
- [**18**星][3y] [PS] [defensivedepth/pertinax](https://github.com/defensivedepth/pertinax) Integrating Sysinternals Autoruns’ logs into Security Onion
- [**18**星][2y] [Lua] [nickcalyx/xmpp-onion-map](https://github.com/nickcalyx/xmpp-onion-map) A list of XMPP servers available as hidden services for use with the Prosody server and mod_onions
- [**18**星][2y] [Shell] [norpol/opensshd-tor-easy-setup](https://github.com/norpol/opensshd-tor-easy-setup) WIP: Quick and easy way to setup a tor .onion ssh service
- [**17**星][3y] [HTML] [jonathan-reisdorf/node-onion-omega-oled-text](https://github.com/jonathan-reisdorf/node-onion-omega-oled-text) Write text with big 16x16 font on the OLED expansion of the Onion Omega / Omega2
- [**15**星][3y] [Shell] [ahmia/torbalancer](https://github.com/ahmia/torbalancer) TorBalancer is a load balancer that uses multiple Tor clients and reuses circuits to onion sites.
- [**15**星][2m] [CSS] [dragonfruitnetwork/onionfruit](https://github.com/dragonfruitnetwork/onionfruit) OnionFruit Connect Downloads and Landing Pages
- [**14**星][4y] [Shell] [juhanurmi/stealth-ssh](https://github.com/juhanurmi/stealth-ssh) Secure SSH server using onion service.
- [**14**星][2m] [Shell] [security-onion-solutions/securityonion-nsmnow-admin-scripts](https://github.com/security-onion-solutions/securityonion-nsmnow-admin-scripts) 
- [**13**星][2y] [Py] [loomisloud/onion-crawler](https://github.com/loomisloud/onion-crawler) Tor website crawler (specific for Alphabay at the time)
- [**12**星][3y] [Java] [miguelmarco/zcashpannel](https://github.com/miguelmarco/zcashpannel) An android front-end to the zcash wallet through onion services
- [**11**星][1m] [JS] [shesek/onionfile](https://github.com/shesek/onionfile) Simple file sharing over tor hidden services (v3)
- [**11**星][2y] [JS] [lukechilds/onionoo-node-client](https://github.com/lukechilds/onionoo-node-client) Node.js client library for the Tor Onionoo API
- [**9**星][4y] [Go] [onionscan/onionscan](https://github.com/onionscan/onionscan) Scan Onion Services for Security Issues
- [**8**星][5m] [PHP] [security-onion-solutions/securityonion-capme](https://github.com/security-onion-solutions/securityonion-capme) 
- [**8**星][2y] [C++] [gilmansharov/onionmalware](https://github.com/gilmansharov/onionmalware) Multi-layer malware
- [**7**星][2y] [Shell] [security-onion-solutions/securityonion-elsa-extras](https://github.com/security-onion-solutions/securityonion-elsa-extras) 
- [**7**星][16d] [Shell] [security-onion-solutions/securityonion-sostat](https://github.com/security-onion-solutions/securityonion-sostat) 
- [**6**星][6y] [Perl] [wwwiretap/bleeding_onions](https://github.com/wwwiretap/bleeding_onions) Script to find Exit and Guard nodes in the Tor Network, that are still suffering from CVE-2014-0160
- [**5**星][26d] [HTML] [security-onion-solutions/securityonion-web-page](https://github.com/security-onion-solutions/securityonion-web-page) 
- [**4**星][1y] [Shell] [ecrimelabs/securityonion-ecrimelabs](https://github.com/ecrimelabs/securityonion-ecrimelabs) Implementation of information from MISP through the eCrimeLabs API and into SecurityOnion
- [**4**星][7m] [Py] [irl/bushel](https://github.com/irl/bushel) A bushel of onions is 57 lbs
- [**4**星][9m] [Shell] [mutedmouse/helk4so](https://github.com/mutedmouse/helk4so) This repository is for integrating HELK capabilities into Security Onion instances. This will be an evolving extension to both products and as such this not contributed directly to either the HELK or SecurityOnion. Please both use at your own risk and enjoy.
- [**4**星][3y] [Shell] [security-onion-solutions/securityonion-sguil-db-purge](https://github.com/security-onion-solutions/securityonion-sguil-db-purge) 
- [**4**星][2y] [Py] [whonix/control-port-filter-python](https://github.com/whonix/control-port-filter-python) [Deprecated in Whonix 14] - new project name -> https://github.com/Whonix/onion-grater
- [**2**星][3y] [C] [epidemics-scepticism/all-the-onions](https://github.com/epidemics-scepticism/all-the-onions) Cryptographers hate him! Find every Tor hidden service address with this one weird trick!
- [**2**星][2y] [Py] [mirsamantajbakhsh/onionharvester-server](https://github.com/mirsamantajbakhsh/onionharvester-server) The web application for paralleling and distributing search operations among Onion Harvester clients.
- [**1**星][2y] [Py] [meejah/txtorcon-documentation-builder](https://github.com/meejah/txtorcon-documentation-builder) A distributed application that re-builds txtorcon's onion-service hosted documentation
- [**0**星][2y] [TeX] [alexxnica/onion-service-usability](https://github.com/alexxnica/onion-service-usability) Research project about understanding how Tor users interact with onion services


### <a id="ceb532aae106b39ea224c7aef786c831"></a>I2P


- [**1340**星][3d] [C++] [purplei2p/i2pd](https://github.com/purplei2p/i2pd) a full-featured C++ implementation of I2P client
- [**548**星][1y] [C++] [monero-project/kovri](https://github.com/monero-project/kovri) kovri：I2P 匿名网络的 C++ 实现版
- [**80**星][7m] [Java] [i2p/i2p.i2p-bote](https://github.com/i2p/i2p.i2p-bote) I2P-Bote is a serverless, encrypted e-mail application.
- [**71**星][19d] [Java] [i2p/i2p.android.base](https://github.com/i2p/i2p.android.base) I2P for Android
- [**71**星][2m] [JS] [purplei2p/i2pdbrowser](https://github.com/purplei2p/i2pdbrowser) i2pd browser bundle
- [**55**星][6d] [Rust] [str4d/ire](https://github.com/str4d/ire) I2P router implementation in Rust
- [**42**星][2m] [mikalv/awesome-i2p](https://github.com/mikalv/awesome-i2p) A curated list of awesome I2P implementations, libraries, resources, projects, and shiny things. I2P is an anonymous overlay network - a network within a network. It is intended to protect communication from dragnet surveillance and monitoring by third parties such as ISPs.
- [**28**星][2y] [C] [l-n-s/transmission-i2p](https://github.com/l-n-s/transmission-i2p) Anonymous torrent client Transmission-I2P [UNMAINTAINED]
- [**28**星][5m] [JS] [purplei2p/i2pd-tools](https://github.com/purplei2p/i2pd-tools) Some useful tools for I2P
- [**20**星][1m] [C++] [nonlinear-chaos-order-etc/i2pchat](https://github.com/nonlinear-chaos-order-etc/i2pchat) 
- [**12**星][2m] [Py] [str4d/txi2p](https://github.com/str4d/txi2p) I2P bindings for Twisted.




***


## <a id="7b28248ff4b6fe73675e3139109ef93d"></a>文章




# <a id="21cbd08576a3ead42f60963cdbfb8599"></a>代理&&Proxy


***


## <a id="d03d494700077f6a65092985c06bf8e8"></a>工具


### <a id="0ff94312f3ab4898f5996725133ea9d1"></a>未分类


- [**7589**星][20d] [Go] [snail007/goproxy](https://github.com/snail007/goproxy) Proxy是高性能全功能的http代理、https代理、socks5代理、内网穿透、内网穿透p2p、内网穿透代理、内网穿透反向代理、内网穿透服务器、Websocket代理、TCP代理、UDP代理、DNS代理、DNS加密代理，代理API认证，全能跨平台代理服务器。
- [**4145**星][5m] [Py] [spiderclub/haipproxy](https://github.com/spiderclub/haipproxy) 
- [**2457**星][2d] [C#] [netchx/netch](https://github.com/netchx/netch) 游戏加速器。支持:Socks5, Shadowsocks, ShadowsocksR, V2Ray 协议
- [**2262**星][3m] [Py] [novnc/websockify](https://github.com/novnc/websockify) Websockify is a WebSocket to TCP proxy/bridge. This allows a browser to connect to any application/server/service. Implementations in Python, C, Node.js and Ruby.
- [**2153**星][6y] [Ruby] [plamoni/siriproxy](https://github.com/plamoni/siriproxy) A (tampering) proxy server for Apple's Siri
- [**1613**星][7m] [Go] [sipt/shuttle](https://github.com/sipt/shuttle) A web proxy in Golang with amazing features.
- [**1423**星][18d] [C] [z3apa3a/3proxy](https://github.com/z3apa3a/3proxy) 微型免费代理服务器
- [**1243**星][2m] [Go] [google/martian](https://github.com/google/martian) 用于构建自定义HTTP / S代理的库
- [**1073**星][6m] [C] [tcurdt/iproxy](https://github.com/tcurdt/iproxy) Let's you connect your laptop to the iPhone to surf the web.
- [**910**星][7d] [JS] [mellow-io/mellow](https://github.com/mellow-io/mellow) Mellow is a rule-based global transparent proxy client for Windows, macOS and Linux.
- [**777**星][3y] [TS] [uwnetworkslab/uproxy-p2p](https://github.com/uwnetworkslab/uproxy-p2p) Internet without borders
- [**739**星][4d] [Py] [abhinavsingh/proxy.py](https://github.com/abhinavsingh/proxy.py) ⚡⚡⚡Fast, Lightweight, Pluggable, TLS interception capable proxy server focused on Network monitoring, controls & Application development, testing, debugging
- [**700**星][2m] [Go] [dliv3/venom](https://github.com/dliv3/venom) Venom - A Multi-hop Proxy for Penetration Testers
- [**660**星][3y] [Ruby] [igrigorik/em-proxy](https://github.com/igrigorik/em-proxy) EventMachine Proxy DSL for writing high-performance transparent / intercepting proxies in Ruby
- [**590**星][5d] [clarketm/proxy-list](https://github.com/clarketm/proxy-list) A list of free, public, forward proxy servers. UPDATED DAILY!
- [**556**星][9y] [Ruby] [mojombo/proxymachine](https://github.com/mojombo/proxymachine) A simple TCP routing proxy built on EventMachine that lets you configure the routing logic in Ruby.
- [**477**星][1y] [Go] [yinqiwen/gsnova](https://github.com/yinqiwen/gsnova) Private proxy solution & network troubleshooting tool.
- [**429**星][3d] [Py] [stamparm/fetch-some-proxies](https://github.com/stamparm/fetch-some-proxies) Simple Python script for fetching "some" (usable) proxies
- [**370**星][2m] [Py] [lyft/metadataproxy](https://github.com/lyft/metadataproxy) A proxy for AWS's metadata service that gives out scoped IAM credentials from STS
- [**363**星][2y] [Py] [roglew/pappy-proxy](https://github.com/roglew/pappy-proxy) An intercepting proxy for web application testing
- [**341**星][2y] [C++] [usb-tools/usbproxy-legacy](https://github.com/usb-tools/USBProxy-legacy) A proxy for USB devices, libUSB and gadgetFS - this project is unmaintained, try here:
- [**305**星][3m] [JS] [bettercap/caplets](https://github.com/bettercap/caplets) 使用.cap脚本, 自动化bettercap的交互式会话
- [**287**星][5m] [Go] [suyashkumar/ssl-proxy](https://github.com/suyashkumar/ssl-proxy) 
- [**285**星][2y] [evilsocket/bettercap-proxy-modules](https://github.com/evilsocket/bettercap-proxy-modules) This repository contains some bettercap transparent proxy example modules.
- [**281**星][t] [a2u/free-proxy-list](https://github.com/a2u/free-proxy-list) 
- [**266**星][5y] [C] [mysql/mysql-proxy](https://github.com/mysql/mysql-proxy) MySQL Proxy is a simple program that sits between your client and MySQL server(s) and that can monitor, analyze or transform their communication. Its flexibility allows for a wide variety of uses, including load balancing, failover, query analysis, query filtering and modification, and many more.
- [**229**星][4y] [Py] [danmcinerney/elite-proxy-finder](https://github.com/danmcinerney/elite-proxy-finder) Finds public elite anonymity proxies and concurrently tests them
- [**218**星][9m] [Go] [joncooperworks/judas](https://github.com/joncooperworks/judas) a phishing proxy
- [**218**星][1y] [PHP] [softius/php-cross-domain-proxy](https://github.com/softius/php-cross-domain-proxy) PHP Proxy for Cross Domain Requests
- [**213**星][3y] [C#] [dxflatline/flatpipes](https://github.com/dxflatline/flatpipes) A TCP proxy over named pipes. Originally created for maintaining a meterpreter session over 445 for less network alarms.
- [**207**星][2y] [Go] [netxfly/xsec-proxy-scanner](https://github.com/netxfly/xsec-proxy-scanner) 速度超快、小巧的代理服务器扫描器
- [**205**星][3y] [Go] [praetorian-code/trudy](https://github.com/praetorian-code/trudy) A transparent proxy that can modify and drop traffic for arbitrary TCP connections.
- [**199**星][3m] [Py] [cisco-talos/decept](https://github.com/cisco-talos/decept) Decept Network Protocol Proxy
- [**194**星][3y] [JS] [mhils/honeyproxy](https://github.com/mhils/honeyproxy) This project is now part of
- [**186**星][13d] [Go] [asciimoo/morty](https://github.com/asciimoo/morty) 去除恶意HTML标签和属性，去除外部资源引用以防止第三方信息泄露
- [**185**星][2m] [Java] [sensepost/mallet](https://github.com/sensepost/mallet) Mallet is an intercepting proxy for arbitrary protocols
- [**182**星][3m] [C] [cloudflare/mmproxy](https://github.com/cloudflare/mmproxy) mmproxy, the magical PROXY protocol gateway
- [**172**星][2y] [Py] [mdsecactivebreach/chameleon](https://github.com/mdsecactivebreach/chameleon) A tool for evading Proxy categorisation
- [**167**星][3y] [C] [hugsy/proxenet](https://github.com/hugsy/proxenet) The ONLY hacker friendly proxy for webapp pentests.
- [**158**星][2y] [Py] [tintinweb/striptls](https://github.com/tintinweb/striptls) proxy poc implementation of STARTTLS stripping attacks
- [**157**星][2m] [Py] [nucypher/pyumbral](https://github.com/nucypher/pyumbral) NuCypher's reference implementation of Umbral (threshold proxy re-encryption) using OpenSSL and Cryptography.io
- [**154**星][4y] [C++] [hiwincn/htran](https://github.com/hiwincn/htran) HTran is a connection bouncer, a kind of proxy server. A “listener” program is hacked stealthily onto an unsuspecting host anywhere on the Internet. When it receives signals from the actual target system, it redirects it to the hacker’s server.
- [**143**星][2y] [Ruby] [nccgroup/binproxy](https://github.com/nccgroup/binproxy) BinProxy is a proxy for arbitrary TCP connections. You can define custom message formats using the BinData gem.
- [**143**星][3y] [Py] [safebreach-labs/pacdoor](https://github.com/safebreach-labs/pacdoor) Proof-of-concept JavaScript malware implemented as a Proxy Auto-Configuration (PAC) File
- [**135**星][9d] [C++] [pichi-router/pichi](https://github.com/pichi-router/pichi) Flexible Rule-Based Proxy
- [**131**星][3y] [Py] [safebreach-labs/pyekaboo](https://github.com/safebreach-labs/pyekaboo) Proof-of-concept program that is able to to hijack/hook/proxy Python module(s) thanks to $PYTHONPATH variable
- [**114**星][7m] [C#] [tyranid/canape.core](https://github.com/tyranid/canape.core) A network proxy library written in C# for .NET Core based on CANAPE
- [**111**星][2m] [Py] [ickerwx/tcpproxy](https://github.com/ickerwx/tcpproxy) Intercepting TCP proxy to modify raw TCP streams using modules on incoming or outgoing traffic
- [**110**星][6m] [Swift] [tuluobo/leiter](https://github.com/tuluobo/leiter) 一个基于 NEKit 的网络 Proxy App。
- [**105**星][6m] [Py] [roglew/guppy-proxy](https://github.com/roglew/guppy-proxy) 用于WebApp安全测试的拦截代理(intercepting proxy)
- [**91**星][4y] [Py] [pdjstone/wsuspect-proxy](https://github.com/pdjstone/wsuspect-proxy) Python tool to inject fake updates into unencrypted WSUS traffic
- [**90**星][3m] [C++] [leoloobeek/comproxy](https://github.com/leoloobeek/comproxy) PoC for proxying COM objects when hijacking
- [**77**星][5m] [Go] [netxfly/x-proxy](https://github.com/netxfly/x-proxy) honeypot proxy
- [**72**星][6y] [C] [jtripper/sslnuke](https://github.com/jtripper/sslnuke) Transparent proxy that decrypts SSL traffic and prints out IRC messages.
- [**71**星][2y] [JS] [kureev/react-native-network-proxy](https://github.com/kureev/react-native-network-proxy) Network debugger (logger) for React Native apps
- [**62**星][4m] [C] [sonertari/sslproxy](https://github.com/sonertari/sslproxy) Transparent SSL/TLS proxy for decrypting and diverting network traffic to other programs, such as UTM services, for deep SSL inspection
- [**62**星][1m] [Lua] [yelp/casper](https://github.com/yelp/casper) Yelp's internal caching proxy, powered by Nginx and OpenResty at its core
- [**60**星][8m] [JS] [try-to/electron-proxy](https://github.com/try-to/electron-proxy) 基于electron开发的内网穿透工具，支持多系统，支持任意本地端口.
- [**58**星][3y] [nidom/buff](https://github.com/nidom/buff) A proxy tool for macOS.
- [**58**星][7m] [JS] [pownjs/pown-proxy](https://github.com/pownjs/pown-proxy) Pown Proxy is a versatile web application security testing proxy with cool TUI features.
- [**54**星][1y] [Go] [netflix-skunkworks/aws-metadata-proxy](https://github.com/netflix-skunkworks/aws-metadata-proxy) AWS Metadata Proxy for protection against SSRF
- [**40**星][5m] [Java] [coveros/zap-sonar-plugin](https://github.com/coveros/zap-sonar-plugin) Integrates OWASP Zed Attack Proxy reports into SonarQube
- [**27**星][17d] [C] [johndoe31415/ratched](https://github.com/johndoe31415/ratched) Ratched is a transparent Man-in-the-Middle TLS proxy intended for penetration testing
- [**21**星][6y] [Go] [mikkolehtisalo/gssapi-proxy](https://github.com/mikkolehtisalo/gssapi-proxy) GSSAPI/Kerberos proxy
- [**10**星][4m] [JS] [zaproxy/zap-api-nodejs](https://github.com/zaproxy/zap-api-nodejs) 


### <a id="d3069cac6097830d12f5933c9c8b7a77"></a>HAProxy


- [**1526**星][4d] [C] [jiangwenyuan/nuster](https://github.com/jiangwenyuan/nuster) A high performance HTTP proxy cache server and RESTful NoSQL cache server based on HAProxy
- [**547**星][t] [Go] [jcmoraisjr/haproxy-ingress](https://github.com/jcmoraisjr/haproxy-ingress) HAProxy Ingress
- [**492**星][1m] [Shell] [trimstray/multitor](https://github.com/trimstray/multitor) Shell脚本, 创建多个Tor实例, 并使用HAProxy实现负载均衡
    - 重复区段: [匿名网络->工具->Tor](#e99ba5f3de02f68412b13ca718a0afb6) |
- [**473**星][5d] [Py] [aidaho12/haproxy-wi](https://github.com/aidaho12/haproxy-wi) Web interface for managing Haproxy servers
- [**279**星][5y] [Go] [hashicorp/consul-haproxy](https://github.com/hashicorp/consul-haproxy) Consul HAProxy connector for real-time configuration
- [**221**星][3y] [Smarty] [analytically/haproxy-ddos](https://github.com/analytically/haproxy-ddos) DDOS and attack resilient HAProxy configuration. To be used behind CloudFlare.
- [**179**星][3y] [Go] [adohe/kube2haproxy](https://github.com/adohe/kube2haproxy) High Availability HAProxy auto configuration and auto service discovery for Kubernetes.
- [**161**星][10m] [Go] [armon/go-proxyproto](https://github.com/armon/go-proxyproto) Golang package to handle HAProxy Proxy Protocol
- [**158**星][2y] [Shell] [anapsix/zabbix-haproxy](https://github.com/anapsix/zabbix-haproxy) HAProxy Zabbix Discovery and Template
- [**121**星][2y] [Py] [teamhg-memex/aquarium](https://github.com/teamhg-memex/aquarium) Splash + HAProxy + Docker Compose
- [**81**星][11d] [geerlingguy/ansible-role-haproxy](https://github.com/geerlingguy/ansible-role-haproxy) Ansible Role - HAProxy
- [**67**星][14d] [Shell] [dbezemer/rpm-haproxy](https://github.com/dbezemer/rpm-haproxy) HAproxy RPM spec and builds for CentOS 6/7
- [**58**星][16d] [Java] [daggerok/streaming-file-server](https://github.com/daggerok/streaming-file-server) full-stack java file server with no limitation for files uploads and downloads: spring-boot + Gradle Kotlin DSL, Gradle buildSrc, postgres / h2, apache fileUpload, lombok, mustache, docker, jgiven, powermock, gradle, CI, bootstrap 4, bootstrap-filelinput, webjars, maven github-release-plugin, nginx, haproxy, reverse-proxy
- [**36**星][3y] [C] [arodland/haproxy](https://github.com/arodland/haproxy) Experiment with haproxy
- [**24**星][1m] [Py] [yelp/hacheck](https://github.com/yelp/hacheck) HAproxy healthcheck proxying service
- [**20**星][27d] [HTML] [cloudfoundry-incubator/haproxy-boshrelease](https://github.com/cloudfoundry-incubator/haproxy-boshrelease) A BOSH release for haproxy (based on cf-release's haproxy job)
- [**19**星][19d] [Py] [yelp/synapse-tools](https://github.com/yelp/synapse-tools) Tools for configuring synapse and reloading haproxy hitlessly


### <a id="6381920f17576b07cc87a8dc619123aa"></a>DNS


#### <a id="b0328a85ce70f4be618511259df159a9"></a>未分类


- [**2503**星][8m] [C++] [chengr28/pcap_dnsproxy](https://github.com/chengr28/pcap_dnsproxy) Pcap_DNSProxy, a local DNS server based on packet capturing
- [**342**星][9m] [Py] [iphelix/dnschef](https://github.com/iphelix/dnschef) DNS 代理，用于渗透测试和恶意代码分析
- [**237**星][12m] [Go] [fardog/secureoperator](https://github.com/fardog/secureoperator) A DNS-protocol proxy for DNS-over-HTTPS providers, such as Google and Cloudflare
- [**203**星][1m] [Rust] [jedisct1/rust-doh](https://github.com/jedisct1/rust-doh) A fast and secure DoH (DNS-over-HTTP) server proxy written in Rust.
- [**171**星][2y] [Go] [arwmq9b6/dnsproxy](https://github.com/arwmq9b6/dnsproxy) 防 DNS 缓存污染，兼顾查询质量与速度
- [**79**星][2y] [Go] [netxfly/xsec-dns-proxy](https://github.com/netxfly/xsec-dns-proxy) xsec-dns-proxy：DNS代理服务器，可以将DNS请求代理到后端的DNS服务器中，在代理的过程中会将dns log写入到数据库中
- [**26**星][9m] [Py] [byt3bl33d3r/dnschef](https://github.com/byt3bl33d3r/dnschef) DNSChef - DNS proxy for Penetration Testers and Malware Analysts


#### <a id="191c4ddd413ed659f507ef4ad8c17818"></a>DNSCrypt


- [**5164**星][t] [Go] [dnscrypt/dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy) 灵活的DNS代理，支持现代的加密DNS协议，例如：DNS protocols such as DNSCrypt v2, DNS-over-HTTPS and Anonymized DNSCrypt.
- [**1433**星][1m] [C#] [bitbeans/simplednscrypt](https://github.com/bitbeans/simplednscrypt) A simple management tool for dnscrypt-proxy
- [**951**星][7y] [C#] [opendns/dnscrypt-win-client](https://github.com/opendns/dnscrypt-win-client) Windows front end for DNSCrypt Proxy
- [**461**星][9m] [C] [cofyc/dnscrypt-wrapper](https://github.com/cofyc/dnscrypt-wrapper) This is dnscrypt wrapper (server-side dnscrypt proxy), which helps to add dnscrypt support to any name resolver.
- [**356**星][] [Shell] [dnscrypt/dnscrypt-server-docker](https://github.com/dnscrypt/dnscrypt-server-docker) A Docker image for a non-censoring, non-logging, DNSSEC-capable, DNSCrypt-enabled DNS resolver
- [**327**星][4y] [JS] [pwnsdx/randomdns](https://github.com/pwnsdx/randomdns) improve the security, privacy and anonymity of DNSCrypt
- [**315**星][t] [Py] [dnscrypt/dnscrypt-resolvers](https://github.com/dnscrypt/dnscrypt-resolvers) Lists of public DNSCrypt-enabled DNS resolvers
- [**273**星][9d] [Go] [adguardteam/dnsproxy](https://github.com/adguardteam/dnsproxy) Simple DNS proxy with DoH, DoT, and DNSCrypt support
- [**231**星][2y] [Shell] [simonclausen/dnscrypt-autoinstall](https://github.com/simonclausen/dnscrypt-autoinstall) Automatic installation and configuration of DNSCrypt (on Debian + Redhat like systems). This script will install DNSCrypt and configure it to start on boot and use an optional dnscrypt service.
- [**162**星][4m] [C] [dyne/dnscrypt-proxy](https://github.com/dyne/dnscrypt-proxy) DNSCrypt-Proxy repository, frankly maintained for what it does (no new features planned)
- [**94**星][1y] [Shell] [jedisct1/bitbar-dnscrypt-proxy-switcher](https://github.com/jedisct1/bitbar-dnscrypt-proxy-switcher) BitBar plugin to control dnscrypt-proxy usage
- [**60**星][16d] [dnscrypt/dnscrypt-protocol](https://github.com/dnscrypt/dnscrypt-protocol) DNSCrypt protocol specification
- [**57**星][2y] [oznu/docker-dns-ad-blocker](https://github.com/oznu/docker-dns-ad-blocker) A lightweight dnsmasq DNS server to block traffic to known ad servers with optional DNSCrypt support. Supports x86_64 and Raspberry Pi (armhf).
- [**50**星][2y] [Shell] [jaybrown/dnscrypt-menu](https://github.com/jaybrown/dnscrypt-menu) Manage DNSCrypt from the macOS menu bar (BitBar plugin)
- [**26**星][5d] [Vue] [dnscrypt/dnscrypt-website](https://github.com/dnscrypt/dnscrypt-website) DNSCrypt website
- [**25**星][2y] [C] [dnscrypt/dnscrypt-plugin-geoip-block](https://github.com/dnscrypt/dnscrypt-plugin-geoip-block) Block DNS queries according to the country they resolve to
- [**12**星][1y] [Py] [jmcgrath207/dnscryptproxypitool](https://github.com/jmcgrath207/dnscryptproxypitool) DnsCrypt Proxy 2 for PiHole Raspberry Pi 3
- [**10**星][12m] [alterstep/dnscrypt-osxclient](https://github.com/alterstep/dnscrypt-osxclient) Mac OSX application to control the DNSCrypt Proxy
- [**1**星][2y] [Shell] [veerendra2/searx-with-dnscrypt](https://github.com/veerendra2/searx-with-dnscrypt) Searx metadata search engine meets dnscrypt in Docker




### <a id="b6f25145e99ea944cbb528a24afaa0be"></a>HTTP&&HTTPS


- [**7969**星][4y] [Go] [cyfdecyf/cow](https://github.com/cyfdecyf/cow) HTTP proxy written in Go. COW can automatically identify blocked sites and use parent proxies to access.
- [**6202**星][11d] [JS] [avwo/whistle](https://github.com/avwo/whistle) 基于Node实现的跨平台抓包调试代理工具（HTTP, HTTP2, HTTPS, Websocket）
- [**1873**星][1m] [C] [tinyproxy/tinyproxy](https://github.com/tinyproxy/tinyproxy) a light-weight HTTP/HTTPS proxy daemon for POSIX operating systems
- [**787**星][12d] [C#] [justcoding121/titanium-web-proxy](https://github.com/justcoding121/titanium-web-proxy) A cross-platform asynchronous HTTP(S) proxy server in C#.
- [**514**星][11m] [Erlang] [heroku/vegur](https://github.com/heroku/vegur) HTTP Proxy Library
- [**355**星][27d] [Go] [quay/jwtproxy](https://github.com/quay/jwtproxy) An HTTP-Proxy that adds AuthN through JWTs
- [**231**星][2m] [Ruby] [zt2/sqli-hunter](https://github.com/zt2/sqli-hunter) SQLi-Hunter is a simple HTTP proxy server and a SQLMAP API wrapper that makes digging SQLi easy.
- [**218**星][10m] [Go] [justmao945/mallory](https://github.com/justmao945/mallory) HTTP/HTTPS proxy over SSH
- [**133**星][2y] [Py] [qiyeboy/baseproxy](https://github.com/qiyeboy/baseproxy) 异步http/https代理,可拦截修改报文
- [**120**星][1y] [Go] [cllunsford/aws-signing-proxy](https://github.com/cllunsford/aws-signing-proxy) Golang http proxy to transparently sign requests to AWS endpoints
- [**110**星][2y] [PHP] [walkor/php-http-proxy](https://github.com/walkor/php-http-proxy) HTTP proxy written in PHP based on workerman.
- [**102**星][2y] [Go] [sakeven/httpproxy](https://github.com/sakeven/httpproxy) 基于 Go 开发，支持 http/1.1 以上版本的 HTTP(S) 代理。（Why not try out Mika?）
- [**32**星][3y] [Go] [mikegleasonjr/devproxy](https://github.com/mikegleasonjr/devproxy) A local development http proxy with hosts spoofing written in Go


### <a id="57b8e953d394bbed52df2a6976d98dfa"></a>Socks


- [**3057**星][2m] [Go] [gwuhaolin/lightsocks](https://github.com/gwuhaolin/lightsocks) 轻量级网络混淆代理，基于 SOCKS5 协议，可用来代替 Shadowsocks
- [**1943**星][5m] [C] [darkk/redsocks](https://github.com/darkk/redsocks) transparent TCP-to-proxy redirector
- [**1740**星][10m] [Py] [constverum/proxybroker](https://github.com/constverum/proxybroker) Proxy [Finder | Checker | Server]. HTTP(S) & SOCKS
- [**1532**星][3y] [Py] [sensepost/regeorg](https://github.com/sensepost/regeorg) The successor to reDuh, pwn a bastion webserver and create SOCKS proxies through the DMZ. Pivot and pwn.
- [**939**星][2y] [C++] [securesocketfunneling/ssf](https://github.com/securesocketfunneling/ssf) 网络工具包：TCP 和 UDP 端口转发、SOCKS 代理、远程 shell，跨平台
- [**852**星][3m] [Py] [anorov/pysocks](https://github.com/anorov/pysocks) A SOCKS proxy client and wrapper for Python.
- [**794**星][3y] [Go] [armon/go-socks5](https://github.com/armon/go-socks5) SOCKS5 server in Golang
- [**558**星][9m] [JS] [blinksocks/blinksocks](https://github.com/blinksocks/blinksocks) A framework for building composable proxy protocol stack.
- [**469**星][6m] [Go] [dan-v/awslambdaproxy](https://github.com/dan-v/awslambdaproxy) An AWS Lambda powered HTTP/SOCKS web proxy
- [**461**星][2y] [missdeer/avege](https://github.com/missdeer/avege) Yet Another Redsocks Golang Fork
- [**441**星][3y] [Py] [ring04h/wyproxy](https://github.com/ring04h/wyproxy) proxying and recording HTTP/HTTPs/Socks5 proxy flow, save to MYSQL database.
- [**425**星][3m] [PS] [p3nt4/invoke-socksproxy](https://github.com/p3nt4/invoke-socksproxy) Socks proxy server using powershell. Supports local and reverse connections for pivoting.
- [**338**星][7m] [Py] [fbkcs/thunderdns](https://github.com/fbkcs/thunderdns) 使用DNS协议转发TCP流量. Python编写, 无需编译客户端, 支持socks5
- [**293**星][3y] [Py] [n1nj4sec/pr0cks](https://github.com/n1nj4sec/pr0cks) python script setting up a transparent proxy to forward all TCP and DNS traffic through a SOCKS / SOCKS5 or HTTP(CONNECT) proxy using iptables -j REDIRECT target
- [**289**星][1y] [C] [dgoulet/torsocks](https://github.com/dgoulet/torsocks) Library to torify application - NOTE: upstream has been moved to
- [**274**星][9m] [C] [rofl0r/microsocks](https://github.com/rofl0r/microsocks) tiny, portable SOCKS5 server with very moderate resource usage
- [**265**星][4y] [JS] [mscdex/socksv5](https://github.com/mscdex/socksv5) SOCKS protocol version 5 server and client implementations for node.js
- [**239**星][3m] [JS] [mattcg/socks5-http-client](https://github.com/mattcg/socks5-http-client) SOCKS v5 HTTP client implementation in JavaScript for Node.js.
- [**239**星][9m] [C] [zhuhaow/tun2socks](https://github.com/zhuhaow/tun2socks) A tun2socks framework with Swift wrapper
- [**233**星][3y] [C#] [thrdev/socks5](https://github.com/thrdev/socks5) A full-fledged high-performance socks5 proxy server written in C#. Plugin support included.
- [**221**星][2y] [Go] [gamexg/proxyclient](https://github.com/gamexg/proxyclient) golang 代理库，和net一致的API。支持 socks4、socks4a、socks5、http、https 等代理协议。
- [**209**星][3y] [Go] [yinghuocho/gotun2socks](https://github.com/yinghuocho/gotun2socks) A Golang implementation of tun2socks
- [**206**星][2y] [Py] [linw1995/lightsocks-python](https://github.com/linw1995/lightsocks-python) 
- [**185**星][3y] [Go] [eahydra/socks](https://github.com/eahydra/socks) socks -- a proxy server.
- [**185**星][3m] [JS] [oyyd/http-proxy-to-socks](https://github.com/oyyd/http-proxy-to-socks) hpts(http-proxy-to-socks) is a nodejs client to convert socks proxy into http proxy
- [**184**星][2y] [5loyd/xsocks](https://github.com/5loyd/xsocks) This project closed.
- [**174**星][2y] [Java] [fengyouchao/sockslib](https://github.com/fengyouchao/sockslib) A Java library of SOCKS5 protocol including client and server
- [**154**星][6y] [C] [defuse/sockstress](https://github.com/defuse/sockstress) Sockstress (TCP DoS) implementation.
- [**154**星][2m] [Rust] [net-reflow/reflow](https://github.com/net-reflow/reflow) Content-routable socks5 proxy switcher for your entire LAN.
- [**137**星][9m] [Go] [snail007/shadowtunnel](https://github.com/snail007/shadowtunnel) secure tunnel which help you protecting your tcp traffic between your machine and your service on remote.
- [**134**星][1m] [Go] [fanpei91/gap-proxy](https://github.com/fanpei91/gap-proxy) gap-proxy 是一个加速网络的 SOCKS5 安全代理工具。
- [**134**星][1m] [Py] [leeon123/cc-attack](https://github.com/leeon123/cc-attack) Using Socks4/5 proxy to make a multithread Http-flood/Https-flood (cc) attack.
- [**131**星][2y] [JS] [oyyd/encryptsocks](https://github.com/oyyd/encryptsocks) Encrypt your socks transmission.
- [**120**星][2y] [PHP] [walkor/php-socks5](https://github.com/walkor/php-socks5) socks5 proxy written in PHP based on workerman.
- [**105**星][15d] [Dockerfile] [peterdavehello/tor-socks-proxy](https://github.com/peterdavehello/tor-socks-proxy) 
- [**98**星][1y] [Py] [tonyseek/rsocks](https://github.com/tonyseek/rsocks) A SOCKS 4/5 reverse proxy server
- [**95**星][4m] [Go] [grepplabs/kafka-proxy](https://github.com/grepplabs/kafka-proxy) Proxy connections to Kafka cluster. Connect through SOCKS Proxy, HTTP Proxy or to cluster running in Kubernetes.
- [**93**星][2m] [C#] [mihazupan/httptosocks5proxy](https://github.com/mihazupan/httptosocks5proxy) C# Http to Socks5 proxy implementation
- [**91**星][2y] [C++] [liulilittle/paperairplane](https://github.com/liulilittle/paperairplane) 一个类似于Proxifier的SOCKS5代理工具
- [**80**星][1y] [Go] [lzjluzijie/websocks](https://github.com/lzjluzijie/websocks) A secure proxy based on WebSocket. 一个基于 WebSocket 的代理工具
- [**79**星][3y] [Go] [ring04h/s5.go](https://github.com/ring04h/s5.go) Socks5 proxy server by golang
- [**72**星][2y] [JS] [chrisyer/lightsocks-nodejs](https://github.com/chrisyer/lightsocks-nodejs) It's a simple socks5 proxy tool which based on lightsocks
- [**72**星][2y] [Go] [qax-a-team/ntlmsocks](https://github.com/QAX-A-Team/NtlmSocks) a pass-the-hash tool
- [**66**星][1y] [Py] [lukebaggett/google_socks](https://github.com/lukebaggett/google_socks) A proof of concept demonstrating the use of Google Drive for command and control.
- [**60**星][4y] [shadowsocks/tun2socks-ios](https://github.com/shadowsocks/tun2socks-ios) tun2socks as a library for iOS apps
- [**56**星][3m] [Shell] [snail007/goproxy-heroku](https://github.com/snail007/goproxy-heroku) goproxy heroku 一键部署套装，把heroku变为免费的http(s)\socks5代理，搜索学习资料。
- [**56**星][3m] [C] [heiher/hev-socks5-tproxy](https://github.com/heiher/hev-socks5-tproxy) A simple, lightweight socks5 transparent proxy for Linux
- [**52**星][6d] [Rust] [sorz/moproxy](https://github.com/sorz/moproxy) A transparent TCP to SOCKSv5/HTTP proxy on Linux written in Rust.
- [**52**星][5y] [Py] [x0day/multiproxies](https://github.com/x0day/multiproxies) penetration testing framework that can use socks4/socks5 proxy.
- [**50**星][5m] [JS] [mattcg/socks5-client](https://github.com/mattcg/socks5-client) SOCKS v5 client socket implementation in JavaScript for Node.JS.
- [**49**星][2y] [Py] [mrschyte/socksmon](https://github.com/mrschyte/socksmon) 使用 BURP 或 ZAP 的 TCP 拦截代理
- [**48**星][29d] [JS] [znetstar/tor-router](https://github.com/znetstar/tor-router) A SOCKS, HTTP and DNS proxy for distributing traffic across multiple instances of Tor
- [**44**星][4m] [Py] [jaredlgillespie/proxyscrape](https://github.com/jaredlgillespie/proxyscrape) Python library for retrieving free proxies (HTTP, HTTPS, SOCKS4, SOCKS5).
- [**44**星][4m] [C] [wongsyrone/transocks-wong](https://github.com/wongsyrone/transocks-wong) A redsocks-like transparent IPv4/IPv6 TCP-to-SOCKS5 redirector (for Linux only)
- [**42**星][2y] [Rust] [alexcrichton/socks5-rs](https://github.com/alexcrichton/socks5-rs) Implementation of a socks5 proxy server in Rust
- [**42**星][5m] [C++] [lianglixin/sksocks](https://github.com/lianglixin/sksocks) SKSocks, for proxy, firewall penetration, data encryption and speeding up internet accessing.
- [**42**星][27d] [Py] [pagekite/pysocksipychain](https://github.com/pagekite/pysocksipychain) Modified socks.py which supports chained proxies
- [**41**星][2y] [6r6/ssr-ml-docker](https://github.com/6r6/ssr-ml-docker) ShadowsockR-Server docker container.
- [**40**星][9m] [Go] [txthinking/socks5](https://github.com/txthinking/socks5) SOCKS Protocol Version 5 Library in Go
- [**40**星][2y] [Py] [zjx20/socks-cli](https://github.com/zjx20/socks-cli) A solution to make CLI commands use socks5 proxy.
- [**39**星][1y] [Dockerfile] [elejke/docker-socks5](https://github.com/elejke/docker-socks5) Docker для поднятия socks5 proxy сервера
- [**39**星][11m] [Py] [keli/furion](https://github.com/keli/furion) Socks5 + SSL Proxy
- [**38**星][4y] [Py] [nonenotnull/regeorg](https://github.com/nonenotnull/regeorg) The successor to reDuh, pwn a bastion webserver and create SOCKS proxies through the DMZ. Pivot and pwn.
- [**38**星][7y] [Java] [ravn/jsocks](https://github.com/ravn/jsocks) Updates for
- [**36**星][9m] [Py] [cyubuchen/free_proxy_website](https://github.com/cyubuchen/free_proxy_website) 获取免费socks/https/http代理的网站集合
- [**34**星][2m] [Shell] [garywill/linux-router](https://github.com/garywill/linux-router) Set Linux as router in one command. Support Internet sharing, redsocks, Wifi hotspot, IPv6. Can also be used for routing VM/containers
- [**33**星][4y] [Py] [pan0pt1c0n/python-sockstress](https://github.com/pan0pt1c0n/python-sockstress) SockStress DoS (Denial of Service) exploit written in Python |
- [**33**星][1y] [Py] [skelsec/socksohttp](https://github.com/skelsec/socksohttp) Socks5 server over Websockets
- [**32**星][4m] [Shell] [riftbit/docker-3proxy](https://github.com/riftbit/docker-3proxy) Smallest and Fastest Docker container for fast proxy setup based on 3proxy SOCKS5 proxy
- [**32**星][1y] [Rust] [sfackler/rust-socks](https://github.com/sfackler/rust-socks) 
- [**32**星][1y] [JS] [blinksocks/blinksocks-gui](https://github.com/blinksocks/blinksocks-gui) A web based GUI wrapper for blinksocks.
- [**31**星][2y] [Go] [brimstone/rsocks](https://github.com/brimstone/rsocks) Tiny little reverse socks5 client & server
- [**31**星][11m] [Shell] [s-o-t/telegram-3proxy-install](https://github.com/s-o-t/telegram-3proxy-install) Bash script to install socks5 proxy (3proxy) configured for telegram.
- [**29**星][4y] [Py] [yinghuocho/ghttproxy](https://github.com/yinghuocho/ghttproxy) a gevent based HTTP/HTTPS proxy with SOCKS5 forwarding.
- [**29**星][1m] [Java] [snail007/goproxy-android](https://github.com/snail007/goproxy-android) snail007/goproxy全能代理服务器安卓版。高性能的http代理、https代理、socks5代理、ss代理、内网穿透、内网穿透p2p、内网穿透代理、内网穿透反向代理、内网穿透服务器、游戏盾、游戏高防、游戏代理，支持API代理认证。websocke代理、tcp代理、udp代理、socket代理、高仿服务器。支持正向代理、反向代理、透明代理、TCP内网穿透、UDP内网穿透、HTTP内网穿透、HTTPS内网穿透、https代理负载均衡、http代理负载均衡、socks5代理负载均衡、socket代理负载均衡、ss代理负载均衡、TCP/UDP端口映射、SSH中转、TLS加密传输、协议转换、防污染DNS代理，限速，限连接数。
- [**28**星][1y] [Ruby] [igrigorik/em-socksify](https://github.com/igrigorik/em-socksify) Transparent proxy support for any EventMachine protocol
- [**28**星][20d] [snail007/goproxy-cn](https://github.com/snail007/goproxy-cn) 高性能的http代理、https代理、socks5代理、ss代理、内网穿透、内网穿透p2p、内网穿透代理、内网穿透反向代理、内网穿透服务器、游戏盾、游戏高防、游戏代理，支持API代理认证。websocke代理、tcp代理、udp代理、socket代理、高仿服务器。支持正向代理、反向代理、透明代理、TCP内网穿透、UDP内网穿透、HTTP内网穿透、HTTPS内网穿透、https代理负载均衡、http代理负载均衡、socks5代理负载均衡、socket代理负载均衡、ss代理负载均衡、TCP/UDP端口映射、SSH中转、TLS加密传输、协议转换、防污染DNS代理，限速，限连接数。官方QQ交流群: 42805407。
- [**24**星][9m] [PHP] [jsondeveloper/dante-gui](https://github.com/jsondeveloper/dante-gui) Dante Server (SOCKS5 Proxy) Web Interface (Telegram ready)
- [**24**星][5y] [C] [z3apa3a/3scan](https://github.com/z3apa3a/3scan) 3Scan is fast detector for open HTTP/CONNECT/SOCKS4/SOCKS5/FTP/TELNET proxy
- [**22**星][10m] [Go] [extremecoders-re/go-dispatch-proxy](https://github.com/extremecoders-re/go-dispatch-proxy) SOCKS5 load balancing proxy developed in Go, combines multiple internet connections
- [**22**星][1y] [Go] [ginuerzh/gosocks5](https://github.com/ginuerzh/gosocks5) golang and SOCKS5
- [**21**星][2y] [JS] [shangxinbo/cardinal](https://github.com/shangxinbo/cardinal) A socks and http proxy by nodejs for you to over GWF
- [**18**星][6y] [Py] [ln5/twisted-socks](https://github.com/ln5/twisted-socks) Adding client SOCKS support to Twisted.
- [**15**星][2y] [Java] [kecon/jsocksproxy](https://github.com/kecon/jsocksproxy) SOCKS proxy written in Java
- [**13**星][4y] [jgamblin/tor](https://github.com/jgamblin/tor) Simple TOR Socks Proxy Container
- [**10**星][8m] [Go] [hanxi/nps](https://github.com/hanxi/nps) 一款轻量级、功能强大的内网穿透代理服务器。支持tcp、udp流量转发，支持内网http代理、内网socks5代理，同时支持snappy压缩、站点保护、加密传输、多路复用、header修改等。支持web图形化管理，集成多用户模式。
- [**10**星][3y] [Go] [marcelki/sockstress](https://github.com/marcelki/sockstress) Sockstress (CVE-2008-4609) DDoS implementation written in Go
- [**8**星][4y] [Py] [jun7th/tsocks](https://github.com/jun7th/tsocks) A reverse socks5 proxy server with ssl(一个Socks5代理服务器程序)
- [**7**星][2y] [C] [qusic/skia](https://github.com/qusic/skia) Transparent SOCKS Redirector for iOS
- [**6**星][1y] [stefanoj3/tordock](https://github.com/stefanoj3/tordock) Dockerized TOR socks5
- [**5**星][5y] [Py] [rpicard/socksonsocks](https://github.com/rpicard/socksonsocks) A tool to set a socket up for using a SOCKS proxy
- [**5**星][2y] [Shell] [flavioaiello/redsocks](https://github.com/flavioaiello/redsocks) Production ready transparent proxy for docker on corporate networks
- [**3**星][2y] [Py] [pannzh/fsocks](https://github.com/pannzh/fsocks) Yet another socks5 proxy to bypass firewall
- [**2**星][8y] [JS] [markfisher/twitter-rabbit-socks-sample](https://github.com/markfisher/twitter-rabbit-socks-sample) 


### <a id="cb16466a31a167bb61f39e2a4a85f449"></a>Shadowsocks


#### <a id="60a91763cc1c0e034bee9717b9b87468"></a>未分类


- [**1891**星][4m] [C] [shadowsocks/simple-obfs](https://github.com/shadowsocks/simple-obfs) A simple obfuscating tool (Deprecated)
- [**632**星][4y] [CoffeeScript] [shadowsocks/shadowsocks-chromeapp](https://github.com/shadowsocks/shadowsocks-chromeapp) Chrome client for shadowsocks
- [**574**星][2y] [JS] [shadowsocks-plus/shadowsocks-plus](https://github.com/shadowsocks-plus/shadowsocks-plus) 
- [**530**星][3y] [ObjC] [herzmut/shadowsocks-ios](https://github.com/herzmut/shadowsocks-ios) Fork of shadowsocks/shadowsocks-iOS
- [**523**星][10m] [JS] [mrluanma/shadowsocks-heroku](https://github.com/mrluanma/shadowsocks-heroku) shadowsocks over WebSocket, support Heroku.
- [**502**星][18d] [JS] [shadowsocks/shadowsocks-org](https://github.com/shadowsocks/shadowsocks-org) The official website of Project Shadowsocks.
- [**371**星][2y] [Java] [zc-zh-001/shadowsocks-share](https://github.com/zc-zh-001/shadowsocks-share) 示例站点
- [**311**星][6y] [Py] [shadowsocks/shadowdns](https://github.com/shadowsocks/shadowdns) A DNS forwarder using Shadowsocks as the server
- [**229**星][2y] [CoffeeScript] [521xueweihan/shadowsocks-heroku](https://github.com/521xueweihan/shadowsocks-heroku) 本项目已删除
- [**202**星][2y] [weilaihui/ss-net](https://github.com/weilaihui/ss-net) 共享shadowsocks主机
- [**192**星][4m] [Shell] [unbinilium/twist](https://github.com/unbinilium/twist) A light script for you to setup shadowsocks-libev server with high-speed connections and newest powerful features
- [**181**星][8m] [shadowsocks/papers](https://github.com/shadowsocks/papers) List of papers related to shadowsocks
- [**174**星][4y] [Py] [shadowsocks-backup/shadowsocks](https://github.com/shadowsocks-backup/shadowsocks) 
- [**127**星][2d] [Py] [v3aqb/fwlite](https://github.com/v3aqb/fwlite) A anti-censorship HTTP proxy with builtin shadowsocks support.
- [**118**星][1y] [JS] [shadowsocks/shadowsocks-hub](https://github.com/shadowsocks/shadowsocks-hub) A web app managing shadowsocks users, servers, nodes, products, accounts, and traffic. Suitable for internal use by companies, organizations, and friends.
- [**109**星][4m] [Shell] [immmx/ubnt-mips-shadowsocks-libev](https://github.com/immmx/ubnt-mips-shadowsocks-libev) Cross complie shadowsocks for UBNT devices based on mipsel or mips64
- [**106**星][4y] [liuchenx/surgeconfig](https://github.com/liuchenx/surgeconfig) surge app shadowsocks config
- [**97**星][4m] [Py] [guyingbo/shadowproxy](https://github.com/guyingbo/shadowproxy) A proxy server that implements Socks5/Shadowsocks/Redirect/HTTP (tcp) and Shadowsocks/TProxy/Tunnel (udp) protocols.
- [**93**星][2m] [Py] [gxfxyz/unblockchn](https://github.com/gxfxyz/unblockchn) Unblock CHN - Shadowsocks 回国解锁代理分流配置工具 (路由器 & Surge) - Unblock Youku 衍生工具
- [**92**星][2y] [Shell] [henryho2006/rpiproxy](https://github.com/henryho2006/rpiproxy) Make a Raspberry PI as a proxy route, work with shadowsocks server, provide clean dns/proxy service
- [**91**星][5y] [JS] [nihgwu/nevermore](https://github.com/nihgwu/nevermore) a shadowsocks client powered by node-webkit
- [**88**星][3y] [JS] [lovetingyuan/fq](https://github.com/lovetingyuan/fq) fq应用，基于nodejs和shadowsocks
- [**80**星][7m] [PHP] [shadowsocks/shadow-shop](https://github.com/shadowsocks/shadow-shop) Building highly customizable e-commerce websites selling shadowsocks services, using Wordpress and WooCommerce
- [**78**星][9d] [Shell] [acris/shadowsocks-asuswrt-merlin](https://github.com/acris/shadowsocks-asuswrt-merlin) Shadowsock for Asuswrt-Merlin New Gen
- [**75**星][8m] [Py] [huaisha1224/shadowsocks-client](https://github.com/huaisha1224/shadowsocks-client) The ShadowSocks client is a support multiple server port and password
- [**72**星][22d] [Py] [ehco1996/aioshadowsocks](https://github.com/ehco1996/aioshadowsocks) 用 asyncio 重写 shadowsocks ~
- [**69**星][6m] [JS] [jiang-xuan/deepinss](https://github.com/jiang-xuan/deepinss) Deep in shadowsocks.
- [**68**星][2y] [Go] [ihciah/inner-shadowsocks](https://github.com/ihciah/inner-shadowsocks) Shadowsocks -> socks5 on server. (Created for providing socks5 proxy for Telegram)
- [**63**星][5m] [Go] [yryz/httpproxy](https://github.com/yryz/httpproxy) 一个轻量级HTTP代理，支持shadowsocks服务，方便命令行、开发环境使用。
- [**60**星][9m] [JS] [shadowsocks/shadowsocks-restful-api](https://github.com/shadowsocks/shadowsocks-restful-api) Secure, reliable, standard restful api for managing shadowsocks-libev
- [**59**星][1y] [Py] [vonsdite/auto_shadowsocks](https://github.com/vonsdite/auto_shadowsocks) Shadowsocks. 科学上网, 仅供学习。是免费的服务器，可能存在科学上网不稳定。
- [**56**星][1m] [Swift] [chengluffy/shadowsocksfree](https://github.com/chengluffy/shadowsocksfree) Try Yourself.
- [**52**星][2y] [C] [shadowsocks/libsscrypto](https://github.com/shadowsocks/libsscrypto) Build libsscrypto.dll for shadowsocks-windows.
- [**48**星][17d] [TS] [srar/socks2shadowsocks](https://github.com/srar/socks2shadowsocks) 单Socks5 转换 多Shadowsocks端口 流量统计 抓包分析 TypeScript
- [**44**星][4m] [HTML] [mrluanma/shadowsocks-websocket-python](https://github.com/mrluanma/shadowsocks-websocket-python) shadowsocks over WebSocket, support Heroku.
- [**40**星][1y] [TS] [icodesign/proxy-uri](https://github.com/icodesign/proxy-uri) Helper to generate/parse Shadowsocks(R)/HTTP(S) URI
- [**38**星][4y] [C] [taichisocks/shadowsocks](https://github.com/taichisocks/shadowsocks) Lightweight shadowsocks client for iOS and Mac OSX base on shadowsocks-libev
- [**38**星][3m] [Py] [kamingchan/shadowsocks-munager](https://github.com/kamingchan/shadowsocks-munager) Middleware of shadowsocks-libev and sspanel
- [**36**星][3y] [Go] [davidqhr/socccks](https://github.com/davidqhr/socccks) Socccks is a shadowsocks like separated socks5 proxy
- [**35**星][5y] [plutochiou/shadowsocks-rss](https://github.com/plutochiou/shadowsocks-rss) shadowsocks update rss
- [**32**星][5y] [Shell] [duoduo369/oh-my-shadowsocks](https://github.com/duoduo369/oh-my-shadowsocks) shadowsocks config on server, supervisor support
- [**28**星][2y] [Swift] [jeanshuang/potatso](https://github.com/jeanshuang/potatso) 适配Xcode9.3 iOS11.3 Swift3.3编译通过。 (unmaintained) Potatso is an iOS client that implements Shadowsocks proxy with the leverage of NetworkExtension framework in iOS 9.
- [**23**星][5d] [Shell] [samuelhbne/vpn-launchpad](https://github.com/samuelhbne/vpn-launchpad) Builds Shadowsocks VPN server on AWS EC2 with QR code support. Works on Ubuntu, OSX and Debian variants including Raspbian.
- [**21**星][1y] [JS] [shadowsocks/shadowsocks-hub-api](https://github.com/shadowsocks/shadowsocks-hub-api) A set of open and standard restful APIs for managing shadowsocks users, servers, nodes, products, accounts, and traffic.
- [**21**星][2y] [Py] [sorz/ssmanager](https://github.com/sorz/ssmanager) A python module managing large amount of running Shadowsocks server instances.
- [**20**星][2y] [JS] [lersh/potatostream](https://github.com/lersh/potatostream) Shadowsocks like Proxy,Written by nodejs
- [**19**星][15d] [windelight/superacl](https://github.com/windelight/superacl) 适用于Shadowsocks各客户端软件和其RSS等衍生版本的访问控制规则
- [**19**星][2y] [Shell] [cool2645/ssmu_install](https://github.com/cool2645/ssmu_install) Shadowsocks-go manyuser auto installer
- [**19**星][1y] [Shell] [necan/shadowsocks-libev-static-build](https://github.com/necan/shadowsocks-libev-static-build) 静态编译 shadowsocks-libev
- [**18**星][3m] [Py] [elder-wu/ssserverdevicelimit](https://github.com/elder-wu/ssserverdevicelimit) 可以让Shadowsocks服务器限制某个端口的设备连接数，防止有人恶意分享ss账号
- [**3**星][2y] [Shell] [altiplanogao/raspbian-ss](https://github.com/altiplanogao/raspbian-ss) Transparent proxy server (use shadowsocks & chinadns) on raspberry pi


#### <a id="bdf7adbb1e8c52aa89dc771aa5fedc4b"></a>收集


- [**304**星][2y] [Shell] [sirzdy/shadowsocks](https://github.com/sirzdy/shadowsocks) 与 ShadowSocks 有关的教程、文件等


#### <a id="f90ec3d0727d2ee3840df6c9f9557756"></a>Shadowsocks-lib/gui


- [**45779**星][5d] [C#] [shadowsocks/shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows) Shadowsocks的Windows客户端
- [**32060**星][4y] [Py] [shadowsocks/shadowsocks](https://github.com/shadowsocks/shadowsocks) shadowsocks原版
- [**12738**星][19d] [C] [shadowsocks/shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev) libev port of shadowsocks
- [**7431**星][2m] [C++] [shadowsocks/shadowsocks-qt5](https://github.com/shadowsocks/shadowsocks-qt5) A cross-platform shadowsocks GUI client
- [**6568**星][6m] [Go] [shadowsocks/shadowsocks-go](https://github.com/shadowsocks/shadowsocks-go) go port of shadowsocks (Deprecated)
- [**2793**星][1m] [Makefile] [shadowsocks/openwrt-shadowsocks](https://github.com/shadowsocks/openwrt-shadowsocks) Shadowsocks-libev for OpenWrt/LEDE
- [**2025**星][5y] [CoffeeScript] [shadowsocks/shadowsocks-gui](https://github.com/shadowsocks/shadowsocks-gui) Shadowsocks GUI client
- [**1928**星][4y] [Py] [ziggear/shadowsocks](https://github.com/ziggear/shadowsocks) backup of https://github.com/shadowsocks/shadowsocks
- [**1431**星][7d] [Rust] [shadowsocks/shadowsocks-rust](https://github.com/shadowsocks/shadowsocks-rust) A Rust port of shadowsocks
- [**1334**星][4y] [mengskysama/shadowsocks](https://github.com/mengskysama/shadowsocks) A fast tunnel proxy that helps you bypass firewalls
- [**1324**星][2m] [C++] [shadowsocks/libqtshadowsocks](https://github.com/shadowsocks/libqtshadowsocks) A lightweight and ultra-fast shadowsocks library written in C++14 with Qt framework
- [**1225**星][3y] [CoffeeScript] [shadowsocks/shadowsocks-nodejs](https://github.com/shadowsocks/shadowsocks-nodejs)  a node.js port of shadowsocks.
- [**907**星][1y] [Go] [huacnlee/flora-kit](https://github.com/huacnlee/flora-kit) 基于 shadowsocks-go 做的完善实现，完全兼容 Surge 的配置文件
- [**866**星][10m] [Shell] [shadowsocks/luci-app-shadowsocks](https://github.com/shadowsocks/luci-app-shadowsocks) OpenWrt/LEDE LuCI for Shadowsocks-libev
- [**846**星][12m] [PHP] [walkor/shadowsocks-php](https://github.com/walkor/shadowsocks-php) A php port of shadowsocks based on workerman. A socks5 proxy written in PHP.
- [**454**星][4y] [clowwindy/shadowsocks-libev](https://github.com/clowwindy/shadowsocks-libev) 
- [**425**星][4m] [JS] [lolimay/shadowsocks-deepin](https://github.com/lolimay/shadowsocks-deepin) a powerful shadowsocks client for linux deepin.
- [**421**星][3y] [Py] [mengskysama/shadowsocks-rm](https://github.com/mengskysama/shadowsocks-rm) A fast tunnel proxy that helps you bypass firewalls
- [**398**星][1y] [Go] [riobard/go-shadowsocks2](https://github.com/riobard/go-shadowsocks2) Experimental Shadowsocks in Go. Stable fork at
- [**249**星][5m] [Py] [fsgmhoward/shadowsocks-py-mu](https://github.com/fsgmhoward/shadowsocks-py-mu) A fast tunnel proxy server for multiple users
- [**243**星][4y] [Py] [rockerflower/shadowsocks](https://github.com/rockerflower/shadowsocks) 
- [**210**星][7y] [haohaolee/shadowsocks-openwrt](https://github.com/haohaolee/shadowsocks-openwrt) A package of shadowsocks for OpenWrt
- [**195**星][3y] [Py] [falseen/shadowsocks-pyqt](https://github.com/falseen/shadowsocks-pyqt) 一个用PyQt5实现的shadowsocks 客户端, 可以在 windows、linux、OSX 等平台上运行
- [**192**星][2m] [Java] [tongxiji/shadowsocks-java](https://github.com/tongxiji/shadowsocks-java) shadowsocks server base on netty4 , tcp & udp full support,
- [**185**星][7y] [CoffeeScript] [shadowsocks/shadowsocks-dotcloud](https://github.com/shadowsocks/shadowsocks-dotcloud) a port of shadowsocks via websockets protocol, able to tunnel through HTTP proxy
- [**167**星][2y] [Rust] [loggerhead/shadowsocks-rust](https://github.com/loggerhead/shadowsocks-rust) Oh my implementation of Shadowsocks in Rust
- [**155**星][2m] [Go] [ihciah/go-shadowsocks-magic](https://github.com/ihciah/go-shadowsocks-magic) A shadowsocks implementation in golang with Multi-connection Acceleration
- [**150**星][1y] [Java] [zhangjiupeng/agentx](https://github.com/zhangjiupeng/agentx) Shadowsocks升级版，支持协议伪装和流量压缩，易于扩展，可统计流量
- [**123**星][3y] [JS] [openmarshall/shortcutss](https://github.com/openmarshall/shortcutss) This is a Mac Shadowsocks client equipped with global shortcuts to switch proxy mode !
- [**88**星][2y] [Go] [dawei101/tongsheclient.shadowsocks-go-ui](https://github.com/dawei101/tongsheclient.shadowsocks-go-ui) shadowsocks client for all desktop platform(mac osx/windows/linux) with golang
- [**71**星][2y] [HTML] [onplus/shadowsocks-websocket-python](https://github.com/onplus/shadowsocks-websocket-python) shadowsocks over WebSocket, support Heroku.
- [**58**星][6y] [CoffeeScript] [lupino/shadowsocks-gui](https://github.com/lupino/shadowsocks-gui) Shadowsocks GUI client
- [**45**星][1y] [Shell] [qiang-yu/shadowsocksvpn-openwrt](https://github.com/qiang-yu/shadowsocksvpn-openwrt) Shadowsocks-libev-full for OpenWrt
- [**44**星][2y] [C#] [tkyu/shadowsocks-csharp-mod](https://github.com/tkyu/shadowsocks-csharp-mod) Shadowsocks for Windows
- [**38**星][1y] [Elixir] [paulzql/shadowsocks-ex](https://github.com/paulzql/shadowsocks-ex) elixir port of shadowsocks
- [**33**星][2y] [Perl] [zhou0/shadowsocks-perl](https://github.com/zhou0/shadowsocks-perl) An asynchronous, non-blocking shadowsocks client and server written in Perl.
- [**31**星][3y] [Py] [loggerhead/shadowsocks](https://github.com/loggerhead/shadowsocks) 
- [**31**星][2y] [Makefile] [xc2/shadowsocks-libev-tomato](https://github.com/xc2/shadowsocks-libev-tomato) Pre-compiled shadowsocks-libev for TomatoUSB, Tomato Shibby, Toastman and Asuswrt Merlin.
- [**29**星][12m] [Java] [bestoa/shadowsocks-vertx](https://github.com/bestoa/shadowsocks-vertx) Java port of shadowsocks with vertx.
- [**28**星][2y] [C] [zhou0/mysocks](https://github.com/zhou0/mysocks) The cross-platform shadowsocks client and server with minimum dependencies.
- [**24**星][7m] [Swift] [universonic/shadowsocks-macos](https://github.com/universonic/shadowsocks-macos) Shadowsocks Client for Apple macOS
- [**23**星][4y] [Py] [shadowsocksfork/shadowsocksfork](https://github.com/shadowsocksfork/shadowsocksfork) A fork of shadowsocks 2.8.2


#### <a id="0b7ec49dd41a16ce7ba58d399475e09f"></a>Shadowsocks-ng


- [**25815**星][1m] [Swift] [shadowsocks/shadowsocksx-ng](https://github.com/shadowsocks/shadowsocksx-ng) Next Generation of ShadowsocksX
- [**5822**星][2y] [qinyuhang/shadowsocksx-ng-r](https://github.com/qinyuhang/shadowsocksx-ng-r) Next Generation of ShadowsocksX
- [**700**星][2y] [yichengchen/shadowsocksx-r](https://github.com/yichengchen/shadowsocksx-r) Next Generation of ShadowsocksX
- [**141**星][7m] [JS] [wzdnzd/shadowsocksx-ng-r](https://github.com/wzdnzd/shadowsocksx-ng-r) Shadowsocks Client for MacOS
- [**108**星][13d] [JS] [paradiseduo/shadowsocksx-ng-r8](https://github.com/paradiseduo/shadowsocksx-ng-r8) ShadowsocksX-NG-R for MacOS
- [**68**星][3y] [Py] [yourtion/alfred_shadowsockscontroller](https://github.com/yourtion/alfred_shadowsockscontroller) ShadowsocksX controller for Alfred


#### <a id="02a80eb3908819d75933198c6b9c6008"></a>ShadowsocksR


- [**5808**星][2y] [shadowsocksrr/shadowsocksr-android](https://github.com/shadowsocksrr/shadowsocksr-android) A ShadowsocksR client for Android
- [**5076**星][4y] [Py] [shadowsocksr-backup/shadowsocksr](https://github.com/shadowsocksr-backup/shadowsocksr) Python port of ShadowsocksR
- [**3940**星][2y] [C#] [shadowsocksr-backup/shadowsocksr-csharp](https://github.com/shadowsocksr-backup/shadowsocksr-csharp) shadowsocksr C#
- [**3826**星][5y] [shadowsocksr-backup/shadowsocks-rss](https://github.com/shadowsocksr-backup/shadowsocks-rss) ShadowsocksR update rss, SSR organization
- [**3420**星][2y] [shadowsocksrr/shadowsocks-rss](https://github.com/shadowsocksrr/shadowsocks-rss) ShadowsocksR update rss, SSR organization
- [**2650**星][2y] [Py] [shadowsocksrr/shadowsocksr](https://github.com/shadowsocksrr/shadowsocksr) Python port of ShadowsocksR
- [**1926**星][16d] [C#] [hmbsbige/shadowsocksr-windows](https://github.com/hmbsbige/shadowsocksr-windows) ShadowsocksR for Windows
- [**1176**星][7m] [ssrarchive/shadowsocks-rss](https://github.com/ssrarchive/shadowsocks-rss) Shadowsocksr project backup
- [**1171**星][6d] [C] [shadowsocksr-live/shadowsocksr-native](https://github.com/shadowsocksr-live/shadowsocksr-native) ShadowsocksR (SSR) native implementation for all platforms,
- [**922**星][1y] [Shell] [ywb94/openwrt-ssr](https://github.com/ywb94/openwrt-ssr) ShadowsocksR-libev for OpenWrt
- [**701**星][6m] [Py] [mobier/shadowsocksr-speed](https://github.com/mobier/shadowsocksr-speed) SSR 批量测试节点有效带宽
- [**665**星][2y] [shadowsocksr-backup/shadowsocksx-ng](https://github.com/shadowsocksr-backup/shadowsocksx-ng) Next Generation of ShadowsocksX
- [**628**星][2y] [C] [shadowsocksr-backup/shadowsocksr-libev](https://github.com/shadowsocksr-backup/shadowsocksr-libev) libev port of ShadowsocksR
- [**478**星][2y] [Py] [ssrarchive/shadowsocksr](https://github.com/ssrarchive/shadowsocksr) Python port of ShadowsocksR
- [**412**星][2y] [zyfworks/ssr-backup](https://github.com/zyfworks/ssr-backup) ShadowsocksR backups
- [**405**星][2y] [Makefile] [bettermanbao/openwrt-shadowsocksr-libev-full](https://github.com/bettermanbao/openwrt-shadowsocksr-libev-full) ShadowsocksR-libev-full for OpenWrt
- [**368**星][2y] [Py] [shadowsocksr-rm/shadowsocksr](https://github.com/shadowsocksr-rm/shadowsocksr) Python port of ShadowsocksR
- [**346**星][13d] [Py] [qwj/python-proxy](https://github.com/qwj/python-proxy) HTTP/Socks4/Socks5/Shadowsocks/ShadowsocksR/SSH/Redirect/Pf TCP/UDP asynchronous tunnel proxy implemented in Python 3 asyncio.
- [**344**星][1m] [Py] [leitbogioro/ssr.go](https://github.com/leitbogioro/ssr.go) A new shadowsocksR config manager
- [**319**星][5y] [shadowsocksr-rm/shadowsocks-rss](https://github.com/shadowsocksr-rm/shadowsocks-rss) ShadowsocksR update rss, SSR organization
- [**238**星][4m] [Swift] [shadowsocksr-live/ishadowsocksr](https://github.com/shadowsocksr-live/ishadowsocksr) ShadowsocksR for iOS, come from
- [**213**星][2y] [C#] [azure99/shadowsocksrcsm](https://github.com/azure99/shadowsocksrcsm) SSRC#魔改版，修复原版链接并进行人性化修改
- [**212**星][2y] [Py] [woosoftware/shadowsocksr-origin](https://github.com/woosoftware/shadowsocksr-origin) Python port of ShadowsocksR
- [**209**星][2y] [Go] [sun8911879/shadowsocksr](https://github.com/sun8911879/shadowsocksr) ShadowsocksR(SSR) for Go library
- [**190**星][10m] [JS] [noahziheng/ssr-helper](https://github.com/noahziheng/ssr-helper) A CLI helper of ShadowsocksR Python
- [**187**星][2m] [ObjC] [shadowsocksr-live/ssrmac](https://github.com/shadowsocksr-live/ssrmac) ShadowsocksR (SSR) client for macOS
- [**179**星][2y] [Shell] [malaohu/ssr-with-net-speeder](https://github.com/malaohu/ssr-with-net-speeder) Shadowsocksr with net speeder
- [**105**星][10m] [Py] [ehco1996/shadowsocksr-deprecated](https://github.com/ehco1996/shadowsocksr-deprecated) ssr mod version for django-sspanel
- [**100**星][20d] [Makefile] [honwen/openwrt-shadowsocksr](https://github.com/honwen/openwrt-shadowsocksr) ShadowsocksR-libev for OpenWrt/LEDE
- [**90**星][7m] [Shell] [honwen/luci-app-shadowsocksr](https://github.com/honwen/luci-app-shadowsocksr) OpenWrt/LEDE LuCI for ShadowsocksR-libev
- [**82**星][1y] [JS] [toyodadoubi/ssrstatus](https://github.com/toyodadoubi/ssrstatus) Shadowsocks/ShadowsocksR 账号在线监控
- [**61**星][2y] [C#] [kuoruan/shadowsocksr-csharp](https://github.com/kuoruan/shadowsocksr-csharp) ShadowsocksR for Windows
- [**55**星][7m] [Py] [shadowsocksr-live/shadowsocksr](https://github.com/shadowsocksr-live/shadowsocksr) 
- [**50**星][2m] [Dockerfile] [winterssy/ssr-docker](https://github.com/winterssy/ssr-docker) 使用Docker部署ShadowsocksR服务端
- [**31**星][2y] [shadowsocksrr/shadowsocksx-ng](https://github.com/shadowsocksrr/shadowsocksx-ng) Next Generation of ShadowsocksX
- [**30**星][5m] [starriv/docker-ss](https://github.com/starriv/docker-ss) use the docker to run shadowsocksr
- [**27**星][2y] [Makefile] [shadowsocksr-rm/openwrt-shadowsocksr](https://github.com/shadowsocksr-rm/openwrt-shadowsocksr) ShadowsocksR-libev for OpenWrt/LEDE
- [**25**星][2y] [shadowsocksr-rm/shadowsocksx-ng](https://github.com/shadowsocksr-rm/shadowsocksx-ng) Next Generation of ShadowsocksX
- [**14**星][5d] [C] [shadowsocksr-live/ssrwin](https://github.com/shadowsocksr-live/ssrwin) ShadowsocksR (SSR) client for Windows
- [**13**星][2y] [TS] [kokororin/nssr](https://github.com/kokororin/nssr) Node.js client for ShadowsocksR


#### <a id="81bb199d6d8690cc6d7ddc92aa81f7f9"></a>帐号


- [**5654**星][1m] [Roff] [max2max/freess](https://github.com/max2max/freess) 免费ss账号 免费shadowsocks账号 免费v2ray账号 (长期更新)
- [**2437**星][2m] [Py] [the0demiurge/shadowsocksshare](https://github.com/the0demiurge/shadowsocksshare) 从ss(r)共享网站爬虫获取共享ss(r)账号，通过解析并校验账号连通性，重新分发账号并生成订阅链接
- [**475**星][1y] [itrump/ssfree](https://github.com/itrump/ssfree) provide shadowsocks free tutorial and free account
- [**133**星][2y] [Py] [chenjiandongx/soksaccounts](https://github.com/chenjiandongx/soksaccounts) Shadowsocks 账号爬虫


#### <a id="bfe4545f8f585c6f19d28ae9d5912aff"></a>插件


- [**749**星][7m] [Go] [cbeuw/goquiet](https://github.com/cbeuw/goquiet) A Shadowsocks obfuscation plugin utilising domain fronting to evade deep packet inspection
- [**53**星][2y] [HTML] [jm33-m0/gfw_scripts](https://github.com/jm33-m0/gfw_scripts) added shadowsocks plugin for gee 4
- [**36**星][1m] [Java] [xausky/shadowsocksgostplugin](https://github.com/xausky/shadowsocksgostplugin) Gost 的 Shadowsocks 安卓插件，可以直接在 Shadowsocks 安卓客户端上连接 Gost 服务器


#### <a id="82476f41454f4e55dcdcf45d817e0395"></a>Docker


- [**81**星][2y] [JS] [chxj1992/shadowsocks-manager-docker](https://github.com/chxj1992/shadowsocks-manager-docker) 这是一个基于 shadowsocks-manager webui 插件开发的shadowsocks账号售卖网站的Docker镜像
- [**65**星][9m] [Dockerfile] [hangim/kcp-shadowsocks-docker](https://github.com/hangim/kcp-shadowsocks-docker) A docker image for shadowsocks server with KCPTUN support
- [**28**星][21d] [Shell] [yaleh/kcp-shadowsocks-server](https://github.com/yaleh/kcp-shadowsocks-server) Docker image of a server with KCP tunnel and Shadowsocks.
- [**24**星][4y] [xgfan/ss-relay](https://github.com/xgfan/ss-relay) shadowsocks relay docker
- [**22**星][12m] [Shell] [cogset/shadowsocks](https://github.com/cogset/shadowsocks) Shadowsocks in Docker
- [**21**星][1m] [Dockerfile] [secbone/docker-ss-libev](https://github.com/secbone/docker-ss-libev) A mini docker image of Shadowsocks-libev only 15M in size
- [**21**星][1y] [Dockerfile] [alibo/goquiet-shadowsocks-docker](https://github.com/alibo/goquiet-shadowsocks-docker) A Docker image for Shadowsocks over GoQuiet


#### <a id="0a4e6103d8a48ee758983d56018076da"></a>安装&&管理


- [**7207**星][7m] [Shell] [teddysun/shadowsocks_install](https://github.com/teddysun/shadowsocks_install) Auto Install Shadowsocks Server for CentOS/Debian/Ubuntu
- [**4246**星][2y] [imeiji/shadowsocks_install](https://github.com/imeiji/shadowsocks_install) Auto install shadowsocks server，thanks 秋水逸冰
- [**3860**星][5d] [JS] [shadowsocks/shadowsocks-manager](https://github.com/shadowsocks/shadowsocks-manager) A shadowsocks manager tool for multi user and traffic control.
- [**1660**星][4d] [Py] [ehco1996/django-sspanel](https://github.com/ehco1996/django-sspanel) 用diango开发的全新的shadowsocks网络面板
- [**858**星][2y] [CoffeeScript] [onplus/shadowsocks-heroku](https://github.com/onplus/shadowsocks-heroku) 一键部署 Free Shadowsocks-Heroku
- [**843**星][3y] [Shell] [hellofwy/ss-bash](https://github.com/hellofwy/ss-bash) Shadowsocks流量管理脚本
- [**481**星][3y] [JS] [vincentchanx/shadowsocks-over-websocket](https://github.com/vincentchanx/shadowsocks-over-websocket) 免费使用 Heroku 部署 shadowsocks
- [**207**星][2m] [Py] [edboffical/bsp](https://github.com/edboffical/bsp) shadowsocks多用户、流量、限时管理接口
- [**179**星][4y] [JS] [gamexg/shadowsocks_admin](https://github.com/gamexg/shadowsocks_admin) 一个 shadowsocks 服务器多账号管理系统，后端使用 shadowsocks-go 。支持多节点、流量限制等功能。
- [**136**星][2y] [Shell] [junbaor/shell_script](https://github.com/junbaor/shell_script) 一键安装 shadowsocks，支持 chacha20-ietf-poly1305 加密方式
- [**107**星][1y] [Py] [lizhongnian/btpanel-ss](https://github.com/lizhongnian/btpanel-ss) 基于宝塔Linux面板的shadowsocks可视化管理插件,本人博客,欢迎大家指导
- [**54**星][1y] [PHP] [ahref-group/superpanel](https://github.com/ahref-group/superpanel) A new shadowsocks panel based on ThinkPHP
- [**42**星][2y] [Py] [liang2580/btpanel-ss](https://github.com/liang2580/btpanel-ss) 基于宝塔Linux面板的shadowsocks可视化管理插件
- [**40**星][8d] [HTML] [zkeeer/shadowsocks-manager](https://github.com/zkeeer/shadowsocks-manager) shadowsocks多用户管理，可视化管理，轻量级，一键安装shadowsocks和ssadmin，控制端口流量/速度，查看端口状态，修改ss配置
- [**28**星][3m] [Shell] [hybtoy/ssrrmu](https://github.com/hybtoy/ssrrmu) ShadowsocksRR (shadowsocksr/ssr) multi-user and single-user install script
- [**28**星][3y] [Shell] [rccoder/awesome-shadowsocks-qt5-installation-on-debian](https://github.com/rccoder/awesome-shadowsocks-qt5-installation-on-debian) Installation Script For shadowsocks-Qt5 on Debian
- [**28**星][2m] [Shell] [idkiro/ssmgr-install](https://github.com/idkiro/ssmgr-install) shadowsocks-manager 前端+后端+魔改BBR一键部署脚本
- [**21**星][3y] [C#] [shadowsocks-plus/shadowsocks-plus-win](https://github.com/shadowsocks-plus/shadowsocks-plus-win) An installer for SSPlus local proxy on Windows


#### <a id="81ba7ad53e5c5f4a9615923ba9595928"></a>其他


- [**1198**星][2m] [jadagates/shadowsocksbio](https://github.com/jadagates/shadowsocksbio) 记录一下SS的前世今生，以及一个简单的教程总结
- [**949**星][3m] [zhaoweih/shadowsocks-tutorial](https://github.com/zhaoweih/shadowsocks-tutorial) SS教程




### <a id="dbc310300d300ae45b04779281fe6ec8"></a>V2Ray


#### <a id="9a47326f72e25428c0163118b9eb42e5"></a>未分类


- [**19408**星][1y] [alvin9999/new-pac](https://github.com/alvin9999/new-pac) 科学/自由上网，免费ss/ssr/v2ray/goflyway账号，搭建教程
- [**5067**星][13d] [Swift] [yanue/v2rayu](https://github.com/yanue/v2rayu) V2rayU,基于v2ray核心的mac版客户端,用于科学上网,使用swift编写,支持vmess,shadowsocks,socks5等服务协议,支持订阅, 支持二维码,剪贴板导入,手动配置,二维码分享等
- [**1789**星][25d] [selierlin/share-ssr-v2ray](https://github.com/selierlin/share-ssr-v2ray) 解决科学上网问题
- [**1450**星][12d] [Go] [xiaoming2028/free-pac](https://github.com/xiaoming2028/Free-PAC) 科学上网/梯子/自由上网/翻墙 SS/SSR/V2Ray/Brook 搭建教程
- [**1350**星][1y] [kirikira/vtemplate](https://github.com/kirikira/vtemplate) v2ray的模板们
- [**1188**星][4d] [Go] [shadowsocks/v2ray-plugin](https://github.com/shadowsocks/v2ray-plugin) A SIP003 plugin based on v2ray
- [**983**星][22d] [HTML] [sprov065/v2-ui](https://github.com/sprov065/v2-ui) 支持多协议多用户的 v2ray 面板，Support multi-protocol multi-user v2ray panel
- [**911**星][4m] [Kotlin] [eycorsican/kitsunebi-android](https://github.com/eycorsican/kitsunebi-android) A fully-featured V2Ray client for Android.
- [**835**星][1m] [Shell] [zfl9/ss-tproxy](https://github.com/zfl9/ss-tproxy) SS/SSR/V2Ray/Socks5 透明代理 for Linux
- [**662**星][2m] [Shell] [toutyrater/v2ray-guide](https://github.com/toutyrater/v2ray-guide) 
- [**619**星][6d] [ntkernel/lantern](https://github.com/ntkernel/lantern) V2Ray配置文件，蓝灯(Lantern)破解，手机版+win版
- [**616**星][23d] [C++] [lhy0403/qv2ray](https://github.com/lhy0403/qv2ray) v2ray linux Windows macOS GUI, 使用 Qt & c++， 支持 vmess ss socks，支持 vmess:// 扫描二维码，路由编辑
- [**460**星][2y] [Kotlin] [v2ray-android/actinium](https://github.com/v2ray-android/actinium) A 3rd party V2Ray client for Android
- [**454**星][28d] [Py] [jiangxufeng/v2rayl](https://github.com/jiangxufeng/v2rayl) v2ray linux GUI客户端，支持订阅、vemss、ss等协议，自动更新订阅、检查版本更新
- [**421**星][1y] [Py] [veekxt/v2ray-template](https://github.com/veekxt/v2ray-template) v2ray 模板，v2ray 配置生成工具
- [**369**星][3m] [Dockerfile] [onplus/v2hero](https://github.com/onplus/v2hero) All Free . Deploy V2Ray to Heroku . v2ray学习参考
- [**346**星][1y] [Shell] [dylanbai8/onekey_caddy_php7_sqlite3](https://github.com/dylanbai8/onekey_caddy_php7_sqlite3) 小内存 VPS 一键搭建 Caddy+PHP7+Sqlite3 环境 （支持VPS最小内存64M），一键翻墙 caddy+web(php+sqlite3)+v2ray+bbr。
- [**314**星][3m] [Shell] [zw963/asuswrt-merlin-transparent-proxy](https://github.com/zw963/asuswrt-merlin-transparent-proxy) transparent proxy base on ss, v2ray, ipset, iptables, chinadns on asuswrt merlin.
- [**283**星][29d] [Dockerfile] [pengchujin/v2raydocker](https://github.com/pengchujin/v2raydocker) 一键v2ray ws + tls 方便就完事了
- [**254**星][3m] [Shell] [sprov065/sprov-ui](https://github.com/sprov065/sprov-ui) 一个支持多协议多用户的v2ray Web面板
- [**246**星][1y] [Shell] [dylanbai8/v2ray_h2-tls_website_onekey](https://github.com/dylanbai8/v2ray_h2-tls_website_onekey) V2RAY 基于 CADDY 的 VMESS+H2+TLS+Website(Use Host)+Rinetd BBR 一键安装脚本
- [**203**星][21d] [Lua] [kuoruan/luci-app-v2ray](https://github.com/kuoruan/luci-app-v2ray) LuCI support for V2Ray
- [**165**星][2y] [Shell] [moexin/easy-v2ray](https://github.com/moexin/easy-v2ray) 简单的V2ray一键配置包，小白也能简单上手。
- [**165**星][4d] [JS] [paperseller/chn-iplist](https://github.com/paperseller/chn-iplist) Chnroutes rules for routers、Shadowrocket、Quantumult、Kitsunebi、acl、BifrostV、v2rayNG、clash、pac、v2ray config file.
- [**154**星][10m] [Shell] [v2ray/dist](https://github.com/v2ray/dist) Mirror of V2Ray core releases
- [**132**星][9m] [JS] [htfy96/v2ray-config-gen](https://github.com/htfy96/v2ray-config-gen) V2Ray Configuration generator
- [**129**星][2y] [C#] [v2ray/v2ray-panel-master](https://github.com/v2ray/v2ray-panel-master) Deprecated
- [**112**星][6m] [v2rayv3/v2ray-sspanel-v3-mod_uim-plugin](https://github.com/v2rayv3/v2ray-sspanel-v3-mod_uim-plugin) 
- [**98**星][1m] [Go] [ne1llee/v2ray2clash](https://github.com/ne1llee/v2ray2clash) V2ray、SSR subscribe convert to Clash、QuantumultX
- [**96**星][5d] [Go] [colettecontreras/v2ray-poseidon](https://github.com/ColetteContreras/v2ray-poseidon) A buildin V2ray plugin for SSRPanel to sync users from database to v2ray, to log traffics/system info
- [**86**星][9m] [Py] [npist/v2rayms](https://github.com/npist/v2rayms) v2ray whmcs 多用户后端
- [**79**星][2y] [nanqinlang-mogic/v2ray](https://github.com/nanqinlang-mogic/v2ray) template with websocket+tls+nginx of v2ray
- [**77**星][2m] [Py] [boypt/vmess2json](https://github.com/boypt/vmess2json) Scripts parse vmess:// links into v2ray config json and vice versa.
- [**58**星][3y] [v2ray/planning](https://github.com/v2ray/planning) Deprecated. Please use v2ray-core for feature requests
- [**57**星][10m] [Vue] [pengchujin/subscribevue](https://github.com/pengchujin/subscribevue) ss ssr v2ray 订阅管理 vue前端界面
- [**57**星][10m] [TS] [pengchujin/onesubscribe](https://github.com/pengchujin/onesubscribe) ss ssr v2ray 订阅管理 node 后端
- [**56**星][2y] [Kotlin] [v2ray/v2rayng](https://github.com/v2ray/v2rayng) This project is currently discontinued. Please use this code with care and considering adopt it.
- [**52**星][2m] [Shell] [mwz1tn/free-v2ray](https://github.com/mwz1tn/free-v2ray) 免费v2ray分享，V2ray安装使用教程，墙裂的购买使用教程
- [**48**星][2y] [Shell] [danielfree/asus-v2ray-transparent-proxy](https://github.com/danielfree/asus-v2ray-transparent-proxy) transparent proxy with v2ray, iptables, ipset 无线路由器 v2ray 透明代理
- [**46**星][2y] [Go] [onplus/v2ray-sitedat](https://github.com/onplus/v2ray-sitedat) 
- [**42**星][9d] [Go] [mzz2017/v2raya](https://github.com/mzz2017/v2raya) V2RayA是一个支持全局透明代理的V2Ray Linux GUI客户端。
- [**41**星][1y] [Py] [v2ray/v2ray-shell_alpha](https://github.com/v2ray/v2ray-shell_alpha) A GUI for V2Ray-core, written in PyQt5
- [**38**星][3m] [C++] [aliyuchang33/hv2ray](https://github.com/aliyuchang33/hv2ray) A linux GUI tool for v2ray base on QT.
- [**33**星][2y] [C#] [mili-tan/mv2rayconfig](https://github.com/mili-tan/mv2rayconfig) 
- [**32**星][3m] [Shell] [lbp0200/v2ray-vultr](https://github.com/lbp0200/v2ray-vultr) 在vultr上，在线自动部署v2ray
- [**31**星][2m] [Shell] [masssmith/smgate](https://github.com/masssmith/smgate) 用树莓派做v2ray透明翻墙网关
- [**31**星][1y] [Shell] [wongsyrone/openwrt-v2ray](https://github.com/wongsyrone/openwrt-v2ray) v2ray package example for OpenWrt/LEDE
- [**31**星][2m] [xuxiaodong/v2ray-for-ansible](https://github.com/xuxiaodong/v2ray-for-ansible) V2Ray for Ansible
- [**27**星][2y] [JS] [kafuuchinoq/v2raygeokit](https://github.com/kafuuchinoq/v2raygeokit) 
- [**26**星][6m] [Batchfile] [dylanbai8/c2ray](https://github.com/dylanbai8/c2ray) C2ray 一款windows下的极简 V2ray 客户端
- [**25**星][2y] [C#] [zjyl1994/v2switcher](https://github.com/zjyl1994/v2switcher) 极简V2Ray配置切换器，拯救多线用户
- [**24**星][24d] [JS] [josephpei/uv2ray](https://github.com/josephpei/uv2ray) Electron V2ray Client (mostly for Linux)
- [**22**星][1y] [Shell] [sparkness/v2ray-tls-docker](https://github.com/sparkness/v2ray-tls-docker) easy to use v2ray tls server
- [**20**星][1y] [Shell] [kyonli/asuswrt-v2ray](https://github.com/kyonli/asuswrt-v2ray) Transparent proxy based on V2Ray
- [**19**星][2m] [Go] [ehco1996/v2scar](https://github.com/ehco1996/v2scar) sidecar for V2ray
- [**19**星][5d] [Shell] [mack-a/v2ray-agent](https://github.com/mack-a/v2ray-agent) 本项目旨在更好的学习新知识，采用CDN+TLS+Nginx+v2ray进行伪装并突破防火墙。
- [**16**星][2y] [Ruby] [kofj/homebrew-v2ray](https://github.com/kofj/homebrew-v2ray) Homebrew tap for v2ray core.


#### <a id="441d09c37d758425d97bcdb5e08a4256"></a>V2Ray-lib/GUI


- [**25531**星][14d] [Go] [v2ray/v2ray-core](https://github.com/v2ray/v2ray-core) A platform for building proxies to bypass network restrictions.
- [**1636**星][5m] [CSS] [functionclub/v2ray.fun](https://github.com/functionclub/v2ray.fun) 正在开发的全新 V2ray.Fun
- [**1344**星][10m] [C#] [cenmrev/v2rayw](https://github.com/cenmrev/v2rayw) GUI for v2ray-core on Windows
- [**418**星][21d] [Makefile] [kuoruan/openwrt-v2ray](https://github.com/kuoruan/openwrt-v2ray) V2Ray for OpenWrt
- [**259**星][2y] [C#] [v2ray/v2rayn](https://github.com/v2ray/v2rayn) A Windows GUI client for V2Ray.
- [**214**星][2m] [Ruby] [v2ray/homebrew-v2ray](https://github.com/v2ray/homebrew-v2ray) The homebrew tap for v2ray-core.
- [**207**星][2y] [C#] [shinlor/v2rays](https://github.com/shinlor/v2rays) 一个V2Ray的Windows客户端
- [**160**星][14d] [HTML] [v2ray/v2ray.github.io](https://github.com/v2ray/v2ray.github.io) V2Ray Portal
- [**84**星][2m] [ObjC] [gssdromen/v2rayc](https://github.com/gssdromen/v2rayc) a GUI for v2ray on Mac


#### <a id="e3e66ebfedb62affa6ef04eced00448f"></a>帐号


- [**2993**星][3m] [Dockerfile] [thinkdevelop/free-ss-ssr](https://github.com/thinkdevelop/free-ss-ssr) SS账号、SSR账号、V2Ray账号


#### <a id="d34c4520a378177efaaa60911f07d8d0"></a>模板




#### <a id="733afa2680ce2eab471cddc5654cd95b"></a>安装&&管理


- [**8564**星][7m] [Shell] [233boy/v2ray](https://github.com/233boy/v2ray) 最好用的 V2Ray 一键安装脚本 & 管理脚本
- [**2844**星][16d] [Py] [jrohy/multi-v2ray](https://github.com/jrohy/multi-v2ray) v2ray easy delpoy & manage tool， support multiple user & protocol manage
- [**2160**星][26d] [Shell] [wulabing/v2ray_ws-tls_bash_onekey](https://github.com/wulabing/v2ray_ws-tls_bash_onekey) V2Ray Nginx+vmess+ws+tls/ http2 over tls 一键安装脚本


#### <a id="1072cf1157d333483198c30028f65e5a"></a>其他






### <a id="160b0cdb52f30bdc3f222aa08c91d10d"></a>proxychains


- [**5659**星][2m] [C] [rofl0r/proxychains-ng](https://github.com/rofl0r/proxychains-ng) proxychains ng (new generation) - a preloader which hooks calls to sockets in dynamically linked programs and redirects it through one or more socks/http proxies. continuation of the unmaintained proxychains project. the sf.net page is currently not updated, use releases from github release page instead.
- [**2402**星][11m] [C] [haad/proxychains](https://github.com/haad/proxychains) a tool that forces any TCP connection made by any given application to follow through proxy like TOR or any other SOCKS4, SOCKS5 or HTTP(S) proxy. Supported auth-types: "user/pass" for SOCKS4/5, "basic" for HTTP.
- [**15**星][1m] [Ruby] [thesecondsun/proxadd](https://github.com/thesecondsun/proxadd) A tool that adds proxy entries to Proxychains config


### <a id="8ff91c8095e77fe88dcac1cff78d79c6"></a>安装&&配置&&管理


- [**20221**星][5d] [Shell] [streisandeffect/streisand](https://github.com/StreisandEffect/streisand) Streisand sets up a new server running your choice of WireGuard, OpenConnect, OpenSSH, OpenVPN, Shadowsocks, sslh, Stunnel, or a Tor bridge. It also generates custom instructions for all of these services. At the end of the run you are given an HTML file with instructions that can be shared with friends, family members, and fellow activists.
- [**3413**星][] [Smarty] [anankke/sspanel-uim](https://github.com/anankke/sspanel-uim) 专为 Shadowsocks / ShadowsocksR / V2Ray 设计的多用户管理面板
- [**3248**星][11d] [TS] [jigsaw-code/outline-server](https://github.com/jigsaw-code/outline-server) 在DigitalOcean上创建和管理Outline服务器
- [**824**星][2y] [PHP] [zhufaner/shadowsocks-manage-system](https://github.com/zhufaner/shadowsocks-manage-system) 科学上网管理系统
- [**344**星][7d] [Shell] [loyess/shell](https://github.com/loyess/shell) Shadowsocks-libev with plugins one-click installation. For example: v2ray-plugin, kcptun, simple-obfs, goquiet, cloak...
- [**85**星][1y] [Py] [justsoos/ss-ssr-v2ray-gadget](https://github.com/justsoos/ss-ssr-v2ray-gadget) merge, deduplicate, backup, convert and online benchmark tools set for shadowsocks/shadowsocksR, v2ray. by python3
- [**57**星][3m] [Shell] [hirbodbehnam/shadowsocks-cloak-installer](https://github.com/hirbodbehnam/shadowsocks-cloak-installer) A one-key script to setup Cloak plugin with Shadowsocks on your server
- [**51**星][1m] [C] [ixzzving/ssr-vpn](https://github.com/ixzzving/ssr-vpn) Shadowsocks & ShadowsocksR & V2Ray & V2RayNG & VNET/酸酸乳节点及客户端
- [**41**星][1y] [Py] [ccapton/brook-ok](https://github.com/ccapton/brook-ok) brook程序服务端配置程序，一键搭建brook / Shadowsocks / Socks5服务用于科学上网
- [**36**星][] [fqshare/free-ssr-v2ray-vpn](https://github.com/fqshare/free-ssr-v2ray-vpn) ssr/酸酸乳/v2ray/shadowsocks节点/vpn/机场搬运分享
- [**32**星][11m] [TS] [xfoxfu/clover](https://github.com/xfoxfu/clover) Shadowsocks and v2ray User Interface


### <a id="b2241c68725526c88e69f1d71405c6b2"></a>代理爬取&&代理池


#### <a id="6d7e96fefef09f8ac350c8e9d77ec49c"></a>抓取


- [**8335**星][1m] [Py] [jhao104/proxy_pool](https://github.com/jhao104/proxy_pool) Python爬虫代理IP池
- [**3656**星][2y] [Py] [qiyeboy/ipproxypool](https://github.com/qiyeboy/ipproxypool) IPProxyPool代理池项目，提供代理ip
- [**1545**星][2y] [Py] [awolfly9/ipproxytool](https://github.com/awolfly9/ipproxytool) 使用 scrapy 爬虫抓取代理网站，获取大量的免费代理 ip。过滤出所有可用的 ip，存入数据库以备使用
- [**853**星][4d] [Go] [henson/proxypool](https://github.com/henson/proxypool) Golang实现的IP代理池
- [**562**星][1y] [Py] [fate0/getproxy](https://github.com/fate0/getproxy) 是一个抓取发放代理网站，获取 http/https 代理的程序
- [**305**星][2y] [Py] [wisedoge/proxypool](https://github.com/wisedoge/proxypool) 跨语言IP代理池，Python实现。
- [**284**星][9m] [Py] [chenjiandongx/async-proxy-pool](https://github.com/chenjiandongx/async-proxy-pool)  异步爬虫代理池，以 Python asyncio 为基础，旨在充分利用 Python 的异步性能。
- [**160**星][7m] [JS] [tidesec/proxy_pool](https://github.com/tidesec/proxy_pool) 一个小巧的代理ip抓取+评估+存储+展示的一体化的工具，包括了web展示和接口。
- [**137**星][4m] [Py] [derekhe/proxypool](https://github.com/derekhe/proxypool) 高质量免费代理池——每日1w+代理资源滚动更新
- [**123**星][2y] [Py] [lujqme/proxy_pool](https://github.com/lujqme/proxy_pool) IP代理池
- [**116**星][5y] [Py] [h01/proxyscanner](https://github.com/h01/proxyscanner) python HTTP代理扫描
- [**106**星][4y] [Py] [mapleray/proxy_pool](https://github.com/mapleray/proxy_pool) python 代理池
- [**95**星][3m] [Py] [cwjokaka/ok_ip_proxy_pool](https://github.com/cwjokaka/ok_ip_proxy_pool) 一个还ok的IP代理池
- [**63**星][10m] [Py] [xnffdd/proxypool](https://github.com/xnffdd/proxypool) 自建免费IP代理池。
- [**38**星][1y] [Py] [leeyis/ip_proxy_pool](https://github.com/leeyis/ip_proxy_pool) 动态生成爬虫，使用scrapy从互联网抓取并检查免费IP
- [**38**星][2m] [Py] [yaleimeng/free_proxy_pool](https://github.com/yaleimeng/free_proxy_pool) 对免费代理IP网站进行爬取，收集汇总为自己的代理池。关键是验证代理的有效性、匿名性、去重复


#### <a id="4417ed293dcbe11e3b5057be518e670d"></a>使用


- [**963**星][1y] [JS] [fabienvauchelles/scrapoxy](https://github.com/fabienvauchelles/scrapoxy) Scrapoxy将您的爬虫隐藏在云后面。启动代理池来发送网络请求
- [**302**星][5m] [Py] [rootviii/proxy_requests](https://github.com/rootviii/proxy_requests) Python类，使用爬取的代理发送http GET / POST请求






***


## <a id="07fb7fc7f8ef8da762c2cc86c482a3f6"></a>文章




# <a id="e996f5ff54050629de0d9d5e68fcb630"></a>隧道&&穿透&&反向代理


***


## <a id="01e6651181d405ecdcd92a452989e7e0"></a>工具


### <a id="ea4dfcd8f33ec1852180c6283b2c8516"></a>未分类


- [**11294**星][3d] [Go] [xtaci/kcptun](https://github.com/xtaci/kcptun) A Stable & Secure Tunnel based on KCP with N:M multiplexing and FEC. Available for ARM, MIPS, 386 and AMD64
- [**2391**星][12d] [Java] [mock-server/mockserver](https://github.com/mock-server/mockserver) MockServer enables easy mocking of any system you integrate with via HTTP or HTTPS with clients written in Java, JavaScript and Ruby. MockServer also includes a proxy that introspects all proxied traffic including encrypted SSL traffic and supports Port Forwarding, Web Proxying (i.e. HTTP proxy), HTTPS Tunneling Proxying (using HTTP CONNECT) and…
- [**1624**星][9m] [JS] [localtunnel/server](https://github.com/localtunnel/server) server for localtunnel.me
- [**968**星][19d] [HTML] [darksecdevelopers/hiddeneye](https://github.com/darksecdevelopers/hiddeneye) Modern Phishing Tool With Advanced Functionality And Multiple Tunnelling Services [ Android-Support-Available ]
- [**321**星][3y] [JS] [mamboleoo/infinitetubes](https://github.com/mamboleoo/infinitetubes) A tunnel experiment in WebGL inspired by the effect seen on
- [**308**星][2y] [JS] [arno0x/dnsexfiltrator](https://github.com/arno0x/dnsexfiltrator) Data exfiltration over DNS request covert channel
- [**296**星][4y] [samyk/proxygambit](https://github.com/samyk/proxygambit) Anonymize and fracture network traffic/Internet access over a point-to-point wireless link or through TCP->GSM->wifi tunnel (advanced resurrection of ProxyHam)
- [**257**星][2y] [Ruby] [bcoles/ssrf_proxy](https://github.com/bcoles/ssrf_proxy) SSRF Proxy facilitates tunneling HTTP communications through servers vulnerable to Server-Side Request Forgery.
- [**211**星][9m] [Go] [cloudflare/cloudflare-ingress-controller](https://github.com/cloudflare/cloudflare-ingress-controller) A Kubernetes ingress controller for Cloudflare's Argo Tunnels
- [**174**星][3y] [C#] [gangzhuo/kcptun-gui-windows](https://github.com/gangzhuo/kcptun-gui-windows) 隧道工具kcptun的GUI
- [**121**星][3y] [PS] [arno0x/dnsdelivery](https://github.com/arno0x/dnsdelivery) DNSDelivery provides delivery and in memory execution of shellcode or .Net assembly using DNS requests delivery channel.
- [**98**星][1m] [Go] [ls0f/cracker](https://github.com/ls0f/cracker) tunnel over http[s]
- [**90**星][2m] [JS] [beameio/beame-sdk](https://github.com/beameio/beame-sdk) HTTPS Server without a public/static IP. TLS Tunnels with decentralized credentials.
- [**57**星][4m] [Go] [flynaj/kcptun](https://github.com/flynaj/kcptun) A Secure Tunnel Based On KCP with N:M Multiplexing
- [**41**星][2y] [JS] [arno0x/reflectivednsexfiltrator](https://github.com/arno0x/reflectivednsexfiltrator) Data exfiltration using reflective DNS resolution covert channel
- [**38**星][2y] [Visual Basic .NET] [arno0x/webdavdelivery](https://github.com/arno0x/webdavdelivery) A WebDAV PROPFIND covert channel to deliver payloads
- [**25**星][8y] [C] [50m30n3/dsptunnel](https://github.com/50m30n3/dsptunnel) IP over audio tunnel
- [**25**星][2y] [Py] [dsnezhkov/octohook](https://github.com/dsnezhkov/octohook) Git Web Hook Tunnel for C2
- [**19**星][13d] [Java] [cronn-de/ssh-proxy](https://github.com/cronn-de/ssh-proxy) Pure Java implementation for SSH port tunneling that understands ProxyJump and ProxyCommand
- [**17**星][10m] [Go] [bitnami-labs/udig](https://github.com/bitnami-labs/udig) public-key addressed TCP tunnel broker
- [**17**星][1m] [Go] [rocket049/powerchat](https://github.com/rocket049/powerchat) linux / windows 加密聊天，分享文件，分享内容（markdown或html），TCP加密隧道
- [**15**星][2y] [Go] [liljebergxyz/tnnlink](https://github.com/liljebergxyz/tnnlink) Simple HTTP tunnel using SSH remote port forwarding
- [**14**星][1y] [Go] [bleenco/vex](https://github.com/bleenco/vex) reverse HTTP proxy tunnel via secure SSH connections.
- [**14**星][5d] [Assembly] [sopium/titun](https://github.com/sopium/titun) Simple, fast, and cross-platform IP tunnel written in Rust. WireGuard compatible.
- [**13**星][3y] [Ruby] [lnussbaum/tuns](https://github.com/lnussbaum/tuns) IP over DNS tunnel
- [**13**星][1y] [Go] [llkat/rsockstun](https://github.com/llkat/rsockstun) reverse socks tunneler with ntlm and proxy support
- [**12**星][2y] [C] [massar/sixxsd](https://github.com/massar/sixxsd) sixxsd - The SixXS Daemon - IPv6 Tunnel & Routing Engine
- [**12**星][3m] [Go] [movsb/taosocks](https://github.com/movsb/taosocks) A smart tunnel proxy that helps you bypass firewalls.
- [**11**星][30d] [Go] [potato-industries/gohide](https://github.com/potato-industries/gohide) tunnel port to port traffic over an obfuscated channel with AES-GCM encryption.
- [**8**星][1y] [Shell] [raffaelespazzoli/openshift-sdn-encrypted-tunnel](https://github.com/raffaelespazzoli/openshift-sdn-encrypted-tunnel) 
- [**6**星][3y] [Py] [lockout/tun64](https://github.com/lockout/tun64) IPv6 transition tunnel-based mechanism information exfiltration tool
- [**6**星][4y] [Py] [shadejinx/tunviz](https://github.com/shadejinx/tunviz) DNS Tunnel Detection
- [**6**星][4y] [Lua] [takeshixx/ip-https-tools](https://github.com/takeshixx/ip-https-tools) Tools for the IP over HTTPS (IP-HTTPS) Tunneling Protocol
- [**2**星][1y] [Py] [ciscose/ngrok-spark-startup-helper](https://github.com/ciscose/ngrok-spark-startup-helper) Helps with ngrok tunnel management when developing Cisco WebEx Teams Bots
- [**1**星][2y] [Py] [0x00-0x00/proxypwn](https://github.com/0x00-0x00/proxypwn) ProxyPwn is a scanner and tunneler for open proxies.
- [**1**星][4m] [Ruby] [simp/pupmod-simp-stunnel](https://github.com/simp/pupmod-simp-stunnel) The SIMP stunnel Puppet Module


### <a id="e9f97504fbd14c8bb4154bd0680e9e62"></a>反向代理


- [**17711**星][4y] [Go] [inconshreveable/ngrok](https://github.com/inconshreveable/ngrok) 反向代理，在公网终端和本地服务之间创建安全的隧道
- [**9561**星][5d] [Go] [cnlh/nps](https://github.com/cnlh/nps) 一款轻量级、功能强大的内网穿透代理服务器。支持tcp、udp流量转发，支持内网http代理、内网socks5代理，同时支持snappy压缩、站点保护、加密传输、多路复用、header修改等。支持web图形化管理，集成多用户模式。
- [**4896**星][11m] [Go] [bitly/oauth2_proxy](https://github.com/bitly/oauth2_proxy) 反向代理，静态文件服务器，提供Providers(Google/Github)认证
- [**3647**星][2m] [Java] [ffay/lanproxy](https://github.com/ffay/lanproxy) 将局域网个人电脑、服务器代理到公网的内网穿透工具，支持tcp流量转发，可支持任何tcp上层协议（访问内网网站、本地支付接口调试、ssh访问、远程桌面...）
- [**2599**星][11d] [C++] [fanout/pushpin](https://github.com/fanout/pushpin) 使用C ++编写的反向代理服务器，可以轻松实现WebSocket，HTTP流和HTTP长轮询服务
- [**2562**星][1m] [Go] [drk1wi/modlishka](https://github.com/drk1wi/modlishka) 一个强大而灵活的HTTP反向代理
- [**1894**星][1y] [Py] [aploium/zmirror](https://github.com/aploium/zmirror) 一个Python反向HTTP代理程序, 用于快速、简单地创建别的网站的镜像, 自带本地文件缓存、CDN支持
- [**1190**星][5d] [Go] [pusher/oauth2_proxy](https://github.com/pusher/oauth2_proxy) 提供与Google，Github或其他提供商进行身份验证的反向代理。
- [**986**星][1m] [JS] [lukechilds/reverse-shell](https://github.com/lukechilds/reverse-shell) 容易记忆的反向shell，可在大多数类Unix系统上使用
- [**821**星][7y] [C] [inquisb/icmpsh](https://github.com/inquisb/icmpsh) 一个简单的反向ICMP Shell，兼容Win32 slave和POSIX，C、Perl、Python
- [**783**星][t] [C#] [damianh/proxykit](https://github.com/damianh/proxykit) 创建以代码优先的HTTP反向代理，作为中间件托管在ASP.NET Core中
- [**665**星][5m] [Py] [aploium/shootback](https://github.com/aploium/shootback) 反向TCP隧道，访问NAT或防火墙后面的目标
- [**471**星][1m] [JS] [siujoeng-lau/workers-proxy](https://github.com/siujoeng-lau/workers-proxy) 一个轻量级的Javascript应用程序，从其他服务器检索资源
- [**388**星][2y] [Py] [mricon/rev-proxy-grapher](https://github.com/mricon/rev-proxy-grapher) 生成反向代理流程graphviz图
- [**388**星][1y] [Go] [mwitkow/grpc-proxy](https://github.com/mwitkow/grpc-proxy) 一个Go反向代理，以最小的开销对gRPC调用，支持丰富路由
- [**365**星][4y] [Py] [ahhh/reverse_dns_shell](https://github.com/ahhh/reverse_dns_shell) 使用DNS作为c2通道的python反向shell
- [**346**星][3y] [Py] [nccgroup/abptts](https://github.com/nccgroup/abptts) 使用Python客户端脚本和Web应用程序服务器页面/程序包，通过HTTP / HTTPS连接，将TCP通信通过隧道，传输到Web应用程序服务器
- [**331**星][5m] [Go] [sysdream/hershell](https://github.com/sysdream/hershell) Go 语言编写的反向 Shell
- [**287**星][1y] [Py] [klsecservices/rpivot](https://github.com/klsecservices/rpivot) 通过Socks4将网络流量隧道到内部网络
- [**285**星][3y] [Go] [longxboy/lunnel](https://github.com/longxboy/lunnel) 简单易用的内网NAT穿越、反向代理软件
- [**255**星][5m] [Go] [lesnuages/hershell](https://github.com/lesnuages/hershell) 用Go编写的简单TCP反向Shell
- [**251**星][5m] [Shell] [thesecondsun/revssl](https://github.com/thesecondsun/revssl) 自动生成OpenSSL反向shell的简单脚本
- [**224**星][1y] [Go] [koding/websocketproxy](https://github.com/koding/websocketproxy) WebSocket reverse proxy handler for Go
- [**189**星][3y] [Nginx] [awslabs/ecs-nginx-reverse-proxy](https://github.com/awslabs/ecs-nginx-reverse-proxy) Reference architecture for deploying Nginx on ECS, both as a basic static resource server, and as a reverse proxy in front of a dynamic application server.
- [**175**星][2m] [Shell] [duy13/vddos-protection](https://github.com/duy13/vddos-protection) Welcome to vDDoS, a HTTP(S) DDoS Protection Reverse Proxy. Thank you for using!
- [**157**星][3y] [Ruby] [waterlink/rack-reverse-proxy](https://github.com/waterlink/rack-reverse-proxy) A Reverse Proxy for Rack
- [**146**星][2m] [Py] [chrispetrou/hrshell](https://github.com/chrispetrou/hrshell) HRShell is an HTTPS/HTTP reverse shell built with flask. It is an advanced C2 server with many features & capabilities.
- [**143**星][1y] [Shell] [adi90x/rancher-active-proxy](https://github.com/adi90x/rancher-active-proxy) All in one active reverse proxy for Rancher !
- [**136**星][24d] [PS] [antoniococo/conptyshell](https://github.com/antoniococo/conptyshell) ConPtyShell - Fully Interactive Reverse Shell for Windows
- [**128**星][3m] [grrrdog/weird_proxies](https://github.com/grrrdog/weird_proxies) Reverse proxies cheatsheet
- [**124**星][4m] [Go] [stalkr/dns-reverse-proxy](https://github.com/stalkr/dns-reverse-proxy) DNS Reverse Proxy
- [**118**星][3y] [PHP] [dhayalanb/windows-php-reverse-shell](https://github.com/dhayalanb/windows-php-reverse-shell) Simple php reverse shell implemented using binary .
- [**113**星][17d] [Java] [mkopylec/charon-spring-boot-starter](https://github.com/mkopylec/charon-spring-boot-starter) Reverse proxy implementation in form of a Spring Boot starter.
- [**107**星][3d] [Go] [jetstack/kube-oidc-proxy](https://github.com/jetstack/kube-oidc-proxy) Reverse proxy to authenticate to managed Kubernetes API servers via OIDC.
- [**105**星][4y] [Shell] [cornerpirate/socat-shell](https://github.com/cornerpirate/socat-shell) Socat can be used to establish a reverse shell with bash tab completion and full shell functionality
- [**104**星][2y] [Ruby] [axsuul/rails-reverse-proxy](https://github.com/axsuul/rails-reverse-proxy) A reverse proxy for Ruby on Rails
- [**100**星][1y] [Go] [bechurch/reverse-proxy-demo](https://github.com/bechurch/reverse-proxy-demo) 
- [**83**星][2y] [Go] [asciimoo/filtron](https://github.com/asciimoo/filtron) 反向HTTP代码
- [**73**星][7m] [Go] [audibleblink/letsproxy](https://github.com/audibleblink/letsproxy) Quickly fetch Let's Encrypt certs and serve a reverse proxy
- [**60**星][4y] [Py] [dotcppfile/serbot](https://github.com/dotcppfile/serbot) Advanced Controller/Server/Client Reverse Shell/Bot – Windows/Linux – Python
- [**53**星][3y] [Shell] [mempodippy/snodew](https://github.com/mempodippy/snodew) PHP root (suid) reverse shell
- [**49**星][14d] [Elixir] [tallarium/reverse_proxy_plug](https://github.com/tallarium/reverse_proxy_plug) 
- [**45**星][8m] [Dockerfile] [jmg87/redteam-k8spwn](https://github.com/jmg87/redteam-k8spwn) Reverse shell container for k8s deployments
- [**44**星][12m] [C#] [andychiare/netcore2-reverse-proxy](https://github.com/andychiare/netcore2-reverse-proxy) An example of how to implement a reverse proxy in .NET Core 2
- [**42**星][4m] [Py] [4n4nk3/tinkerershell](https://github.com/4n4nk3/tinkerershell) A simple python reverse shell written just for fun.
- [**42**星][2y] [Shell] [taherio/redi](https://github.com/taherio/redi) Automated script for setting up CobaltStrike redirectors (nginx reverse proxy, letsencrypt)
- [**40**星][9m] [C#] [azure/reverse-proxy-dotnet](https://github.com/azure/reverse-proxy-dotnet) Reverse Proxy agent
- [**39**星][2y] [Go] [googlecloudplatform/stackdriver-reverse-proxy](https://github.com/googlecloudplatform/stackdriver-reverse-proxy) Simple HTTP proxy to automatically traces the incoming requests
- [**38**星][4y] [Assembly] [sh3llc0d3r1337/windows_reverse_shell_1](https://github.com/sh3llc0d3r1337/windows_reverse_shell_1) Windows Reverse Shell shellcode
- [**34**星][1y] [JS] [franciscoknebel/nginx-reverseproxy](https://github.com/franciscoknebel/nginx-reverseproxy) A simple implementation of a multidomain nginx reverse proxy, using Node apps.
- [**33**星][7m] [flyfishsec/rsgen](https://github.com/flyfishsec/rsgen) An Universal Reverse Shell Command Genrator.
- [**29**星][4y] [PS] [ahhh/wifi_trojans](https://github.com/ahhh/wifi_trojans) A collection of wireless based bind and reverse connect shells for penetration testers to use in demonstrating persistence to a network via rouge access points.
- [**27**星][10m] [Rust] [felipenoris/hyper-reverse-proxy](https://github.com/felipenoris/hyper-reverse-proxy) A simple reverse proxy for use with Hyper and Tokio
- [**23**星][2y] [C] [p4p1/p4p1](https://github.com/p4p1/p4p1) Reverse shell for remote administration
- [**22**星][4d] [TS] [cedx/reverse-proxy.js](https://github.com/cedx/reverse-proxy.js) Personal reverse proxy server supporting WebSockets.
- [**5**星][7m] [PS] [audibleblink/gorsh](https://github.com/audibleblink/gorsh) A Golang Reverse Shell w/ a Tmux-driven psuedo-C2 Interface


### <a id="9d6789f22a280f5bb6491d1353b02384"></a>隧道&&穿透


- [**4690**星][4d] [Go] [ginuerzh/gost](https://github.com/ginuerzh/gost) GO语言实现的安全隧道
- [**3465**星][5m] [Go] [jpillora/chisel](https://github.com/jpillora/chisel) 基于HTTP的快速 TCP 隧道
- [**3359**星][5m] [C++] [wangyu-/udp2raw-tunnel](https://github.com/wangyu-/udp2raw-tunnel) udp 打洞。通过raw socket给UDP包加上TCP或ICMP header，进而绕过UDP屏蔽或QoS，或在UDP不稳定的环境下提升稳定性
- [**3227**星][4m] [C] [yarrick/iodine](https://github.com/yarrick/iodine) 通过DNS服务器传输(tunnel)IPV4数据
- [**2862**星][9m] [C++] [wangyu-/udpspeeder](https://github.com/wangyu-/udpspeeder) A Tunnel which Improves your Network Quality on a High-latency Lossy Link by using Forward Error Correction,for All Traffics(TCP/UDP/ICMP)
- [**2509**星][3y] [C] [dhavalkapil/icmptunnel](https://github.com/dhavalkapil/icmptunnel) Transparently tunnel your IP traffic through ICMP echo and reply packets.
- [**2180**星][2m] [Go] [mmatczuk/go-http-tunnel](https://github.com/mmatczuk/go-http-tunnel) Fast and secure tunnels over HTTP/2
- [**1826**星][6m] [C++] [iagox86/dnscat2](https://github.com/iagox86/dnscat2) 在 DNS 协议上创建加密的 C&C channel
- [**1741**星][2y] [Go] [vzex/dog-tunnel](https://github.com/vzex/dog-tunnel) p2p tunnel,(udp mode work with kcp,
- [**1480**星][6y] [C] [alibaba/lvs](https://github.com/alibaba/lvs) A distribution of Linux Virtual Server with some advanced features. It introduces a new packet forwarding method - FULLNAT other than NAT/Tunneling/DirectRouting, and defense mechanism against synflooding attack - SYNPROXY.
- [**1345**星][2m] [Go] [davrodpin/mole](https://github.com/davrodpin/mole) cli app to create ssh tunnels
- [**1192**星][3y] [Roff] [matiasinsaurralde/facebook-tunnel](https://github.com/matiasinsaurralde/facebook-tunnel) Tunneling Internet traffic over Facebook chat.
- [**928**星][1m] [Go] [square/ghostunnel](https://github.com/square/ghostunnel) A simple SSL/TLS proxy with mutual authentication for securing non-TLS services
- [**809**星][4m] [Py] [secforce/tunna](https://github.com/secforce/tunna) Tunna is a set of tools which will wrap and tunnel any TCP communication over HTTP. It can be used to bypass network restrictions in fully firewalled environments.
- [**682**星][15d] [JS] [sadeghhayeri/greentunnel](https://github.com/sadeghhayeri/greentunnel) Green Tunnel is an anti-censorship utility designed to bypass DPI system that are put in place by various ISPs to block access to certain websites.
- [**626**星][6d] [Go] [antoniomika/sish](https://github.com/antoniomika/sish) An open source serveo/ngrok alternative. HTTP(S)/WS(S)/TCP Tunnels to localhost using only SSH.
- [**621**星][5m] [JS] [derhuerst/tcp-over-websockets](https://github.com/derhuerst/tcp-over-websockets) Tunnel TCP through WebSockets.
- [**601**星][3d] [Go] [cloudflare/cloudflared](https://github.com/cloudflare/cloudflared) Argo Tunnel client
- [**596**星][19d] [Py] [trustedsec/trevorc2](https://github.com/trustedsec/trevorc2) 通过正常的可浏览的网站隐藏 C&C 指令的客户端/服务器模型，因为时间间隔不同，检测变得更加困难，并且获取主机数据时不会使用 POST 请求
- [**592**星][3m] [Py] [pahaz/sshtunnel](https://github.com/pahaz/sshtunnel) SSH tunnels to remote server.
- [**560**星][1y] [Go] [cw1997/natbypass](https://github.com/cw1997/natbypass) 内网穿透，端口转发工具
- [**486**星][5d] [Go] [psiphon-labs/psiphon-tunnel-core](https://github.com/psiphon-labs/psiphon-tunnel-core) Psiphon client and server components implemented in Go. These components provides core tunnel functionality, handling all aspects of evading blocking and relaying traffic through Psiphon.
- [**465**星][3y] [Py] [trustedsec/meterssh](https://github.com/trustedsec/meterssh) MeterSSH is a way to take shellcode, inject it into memory then tunnel whatever port you want to over SSH to mask any type of communications as a normal SSH connection. The way it works is by injecting shellcode into memory, then wrapping a port spawned (meterpeter in this case) by the shellcode over SSH back to the attackers machine. Then conne…
- [**403**星][10m] [Go] [evilsocket/shellz](https://github.com/evilsocket/shellz) shellz is a small utility to track and control your ssh, telnet, web and custom shells and tunnels.
- [**401**星][3m] [C] [liudf0716/xkcptun](https://github.com/liudf0716/xkcptun) xkcptun is kcp tunnel for OpenWRT&LEDE, implemented in c language
- [**385**星][1y] [Ruby] [aphyr/tund](https://github.com/aphyr/tund) SSH reverse tunnel daemon
- [**375**星][3y] [Go] [q3k/crowbar](https://github.com/q3k/crowbar) Tunnel TCP over a plain HTTP session (warning: mediocre Go code)
- [**357**星][1y] [C] [emptymonkey/revsh](https://github.com/emptymonkey/revsh) A reverse shell with terminal support, data tunneling, and advanced pivoting capabilities.
- [**334**星][10m] [JS] [mhzed/wstunnel](https://github.com/mhzed/wstunnel) tunnel over websocket
- [**327**星][3y] [JS] [qgy18/pangolin](https://github.com/qgy18/pangolin) A light weight http tunnels to localhost.
- [**327**星][18d] [C#] [tmoonlight/nsmartproxy](https://github.com/tmoonlight/nsmartproxy) 内网穿透工具。采用.NET CORE的全异步模式打造
- [**326**星][2m] [C] [xelerance/xl2tpd](https://github.com/xelerance/xl2tpd) an implementation of the Layer 2 Tunnelling Protocol (RFC 2661)
- [**317**星][3y] [C++] [pipesocks/pipesocks](https://github.com/pipesocks/pipesocks) A pipe-like SOCKS5 tunnel system.
- [**303**星][9m] [C++] [wangyu-/udp2raw-multiplatform](https://github.com/wangyu-/udp2raw-multiplatform) multi-platform(cross-platform) version of udp2raw-tunnel, which supports Windows/Mac/BSD natively
- [**298**星][9m] [C] [basil00/reqrypt](https://github.com/basil00/reqrypt) HTTP 请求 tunneling 工具
- [**266**星][14d] [Py] [earthquake/xfltreat](https://github.com/earthquake/xfltreat) XFLTReaT tunnelling framework
- [**265**星][4m] [Go] [skx/tunneller](https://github.com/skx/tunneller) Allow internal services, running on localhost, to be accessed over the internet..
- [**249**星][3y] [C] [jamesbarlow/icmptunnel](https://github.com/jamesbarlow/icmptunnel) Tunnel IP over ICMP.
- [**244**星][10m] [C] [pegasuslab/ghosttunnel](https://github.com/PegasusLab/GhostTunnel) GhostTunnel is a covert backdoor transmission method that can be used in an isolated environment.
- [**233**星][2y] [C] [larsbrinkhoff/httptunnel](https://github.com/larsbrinkhoff/httptunnel) Bidirectional data stream tunnelled in HTTP requests.
- [**210**星][12m] [Go] [ooclab/otunnel](https://github.com/ooclab/otunnel) peer-to-peer tunnel tool
- [**197**星][18d] [Go] [esrrhs/pingtunnel](https://github.com/esrrhs/pingtunnel) a tool that advertises tcp/udp/sock5 traffic as icmp traffic for forwarding.流量转发工具.
- [**191**星][3y] [Go] [koding/tunnel](https://github.com/koding/tunnel) Tunnel proxy package in Go
- [**179**星][6m] [C#] [nettitude/sharpsocks](https://github.com/nettitude/sharpsocks) Tunnellable HTTP/HTTPS socks4a proxy written in C# and deployable via PowerShell
- [**170**星][1y] [C#] [eaglexiang/eagle.tunnel.dotnet.core](https://github.com/eaglexiang/eagle.tunnel.dotnet.core) 稳定易用的代理工具
- [**170**星][4d] [ObjC] [subito-it/sbtuitesttunnel](https://github.com/subito-it/sbtuitesttunnel) Enable network mocks and more in UI Tests
- [**169**星][9m] [Go] [mimah/gomet](https://github.com/mimah/gomet) Multi-platform agent written in Golang. TCP forwarding, socks5, tunneling, pivoting, shell, download, exec
- [**166**星][3y] [Haskell] [corsis/portfusion](https://github.com/corsis/portfusion) 跨平台传输层分布式反向/正向代理和隧道解决方案
- [**153**星][4y] [Go] [inconshreveable/go-tunnel](https://github.com/inconshreveable/go-tunnel) [DEPRECATED] Tunnel to localhost as a library
- [**132**星][14d] [Go] [inlets/inletsctl](https://github.com/inlets/inletsctl) Fast HTTP (L7) and TCP (L4) tunnels written in Go
- [**129**星][1y] [Py] [deepzec/grok-backdoor](https://github.com/deepzec/grok-backdoor) Simple python backdoor with Ngrok tunnel support
- [**119**星][12m] [CSS] [rootkiter/earthworm](https://github.com/rootkiter/earthworm) Tool for tunnel
- [**118**星][12m] [Shell] [patpadgett/corkscrew](https://github.com/patpadgett/corkscrew) Corkscrew is a tool for tunneling SSH through HTTP proxies.
- [**117**星][4y] [Go] [tutumcloud/ngrok](https://github.com/tutumcloud/ngrok) Introspected tunnels to localhost
- [**115**星][3m] [Go] [eaglexiang/eagle.tunnel.go](https://github.com/eaglexiang/eagle.tunnel.go) 稳定的代理工具，比.NET版本更轻量和易用
- [**115**星][3m] [PS] [jcqsteven/ghosttunnel](https://github.com/jcqsteven/ghosttunnel) 基于360提出的Ghost Tunnel攻击复现
- [**113**星][8m] [C] [jakkarth/icmptx](https://github.com/jakkarth/icmptx) IP-over-ICMP tunnel
- [**106**星][3y] [C] [greensea/mptunnel](https://github.com/greensea/mptunnel) MPUDP Tunnel (User space MultiPath UDP)
- [**104**星][2y] [Java] [ggrandes/bouncer](https://github.com/ggrandes/bouncer) Bouncer is a network TCP port redirector/forward proxy (like rinetd) with extra features like Reverse tunneling (like ssh -R), SSL tunneling (like stunnel), connection Failover, LoadBalancing and Clustering. In pure Java (BIO)
- [**100**星][10m] [Go] [superfly/wormhole](https://github.com/superfly/wormhole) Fly.io secure tunnel
- [**97**星][10m] [Shell] [sskaje/6in4](https://github.com/sskaje/6in4) IPv6-in-IPv4 Tunnel Server
- [**94**星][4y] [JS] [ro31337/hacktunnel](https://github.com/ro31337/hacktunnel) HackTunnel is web-based peer-to-peer chat software for anonymous and encrypted communication written with Go language
- [**94**星][6y] [C++] [stealth/fraud-bridge](https://github.com/stealth/fraud-bridge) ICMP and DNS tunneling via IPv4 and IPv6
- [**93**星][1y] [Go] [tarlogicsecurity/sasshimi](https://github.com/tarlogicsecurity/sasshimi) SSH Tunnelling in "RAW mode", via STDIN/OUT without using forwarding channels
- [**90**星][4y] [JS] [adafruit/adafruit-io-node](https://github.com/adafruit/adafruit-io-node) A Node.js Adafruit IO Node.js Client, Local Server, & io.adafruit.com TLS Tunnel.
- [**83**星][5y] [C] [chokepoint/crypthook](https://github.com/chokepoint/crypthook) TCP/UDP symmetric encryption tunnel wrapper
- [**83**星][2y] [Makefile] [kingsquare/docker-tunnel](https://github.com/kingsquare/docker-tunnel) a (simple) dockerized ssh tunnel
- [**81**星][1y] [Java] [googlecreativelab/tunnelvision](https://github.com/googlecreativelab/tunnelvision) Distort your surroundings through a collection of transformative filters
- [**79**星][1y] [Py] [cdhowie/netflix-no-ipv6-dns-proxy](https://github.com/cdhowie/netflix-no-ipv6-dns-proxy) Fix for Netflix blocking various IPv6 tunnels by returning no results for AAAA queries of Netflix domains
- [**77**星][5y] [C] [bishopfox/firecat](https://github.com/bishopfox/firecat) Firecat is a penetration testing tool that allows you to punch reverse TCP tunnels out of a compromised network.
- [**69**星][3y] [Nginx] [localtunnel/nginx](https://github.com/localtunnel/nginx) nginx container used as the localtunnel load balancer
- [**68**星][2y] [Go] [lubyruffy/tcptunnel](https://github.com/lubyruffy/tcptunnel) 将本地内网服务器映射到公网。
- [**68**星][3m] [Java] [netspi/burpcollaboratordnstunnel](https://github.com/netspi/burpcollaboratordnstunnel) A DNS tunnel utilizing the Burp Collaborator
- [**68**星][3d] [C#] [sailro/bdtunnel](https://github.com/sailro/bdtunnel) BoutDuTunnel is able to create virtual connections tunnelled in HTTP requests.
- [**67**星][1y] [C++] [oyyd/nysocks](https://github.com/oyyd/nysocks) Nysocks binds kcp and libuv to provide an aggressive tcp tunnel in nodejs.
- [**66**星][8m] [C] [v-e-o/rdp2tcp](https://github.com/v-e-o/rdp2tcp) rdp2tcp: open tcp tunnel through remote desktop connection.
- [**65**星][2m] [JS] [snail007/anytunnel](https://github.com/snail007/anytunnel) 内网穿透，内网穿透代理服务器，商用内网穿透代理系统，内网穿透平台，内网穿透多用户会员系统。
- [**64**星][9m] [Go] [dsnezhkov/sshorty](https://github.com/dsnezhkov/sshorty) A progressive, customizable armored SSH tunnel implant for Linux and MacOS systems
- [**64**星][8m] [Go] [smithclay/faassh](https://github.com/smithclay/faassh) simple go SSH server with reverse tunneling designed for running in cloud functions like AWS lambda
- [**61**星][2y] [C] [convisoappsec/firefox_tunnel](https://github.com/convisoappsec/firefox_tunnel) 使用Firefox来建立远程通信隧道, 使用cookie.sqlite/html/js实现payload上传下载
- [**60**星][17d] [C] [lnslbrty/ptunnel-ng](https://github.com/lnslbrty/ptunnel-ng) Tunnel TCP connections through ICMP.
- [**59**星][7m] [JS] [mdslab/wstun](https://github.com/mdslab/wstun) Tunnels and reverse tunnels over WebSocket
- [**58**星][3y] [Py] [epinna/stegosip](https://github.com/epinna/stegosip) TCP tunnel over RTP/SIP
- [**57**星][4y] [Py] [t3rry7f/badtunnel_exp](https://github.com/t3rry7f/badtunnel_exp) Usage: python badtunnel.py wpad_server_ip
- [**49**星][2y] [C] [coolervoid/firefox_tunnel](https://github.com/coolervoid/firefox_tunnel) The way to use firefox to make a tunnel to remote communication, bypass any firewall
- [**49**星][9d] [Go] [sandertv/gophertunnel](https://github.com/sandertv/gophertunnel) A Minecraft (Bedrock Edition) library written in Go used for creating proxies, servers, clients and tools
- [**48**星][3m] [Go] [rancher/remotedialer](https://github.com/rancher/remotedialer) HTTP in TCP in Websockets in HTTP in TCP, Tunnel all the things!
- [**46**星][7m] [Go] [ice-ice/dnstunnel](https://github.com/ice-ice/dnstunnel) dns tunnel backdoor DNS隧道后门
- [**43**星][8m] [Py] [jmagnusson/bgtunnel](https://github.com/jmagnusson/bgtunnel) Initiate SSH tunnels in the background in python
- [**43**星][3y] [Go] [madeye/obfs4-tunnel](https://github.com/madeye/obfs4-tunnel) obfs4 tunnel
- [**42**星][7m] [Go] [aschzero/hera](https://github.com/aschzero/hera) Automated secure tunnels for containers using Cloudflare Argo
- [**40**星][7m] [Go] [function61/holepunch-client](https://github.com/function61/holepunch-client) Totally self-contained SSH reverse tunnel written in Go
- [**40**星][2m] [Go] [opencoff/go-tunnel](https://github.com/opencoff/go-tunnel) TLS/SSL Tunnel - A modern STunnel replacement written in golang
- [**39**星][2y] [Py] [bonelee/dns_tunnel_dectect_with_cnn](https://github.com/bonelee/dns_tunnel_dectect_with_cnn) dns tunnel dectect with CNN
- [**38**星][1y] [JS] [lmammino/webhook-tunnel](https://github.com/lmammino/webhook-tunnel) A little HTTP proxy suitable to create tunnels for webhook endpoints protected behind a firewall or a VPN
- [**38**星][2y] [Java] [quhw/xtunnel](https://github.com/quhw/xtunnel) An useful TCP/SSL tunnel utility.
- [**37**星][2y] [JS] [kevva/caw](https://github.com/kevva/caw) Construct HTTP/HTTPS agents for tunneling proxies
- [**32**星][3y] [Go] [mwitkow/go-http-dialer](https://github.com/mwitkow/go-http-dialer) Go net.Dialer for HTTP(S) CONNECT Tunneling.
- [**32**星][3y] [Go] [localtunnel/go-localtunnel](https://github.com/localtunnel/go-localtunnel) golang client library for localtunnel.me
- [**28**星][3y] [JS] [markelog/adit](https://github.com/markelog/adit) SSH tunnels – in any way you want it
- [**27**星][2y] [Go] [jsimonetti/tlstun](https://github.com/jsimonetti/tlstun) A socks tunnel client and server using websockets over http and tls
- [**27**星][11m] [C#] [kostapc/putty-tunnel-manager](https://github.com/kostapc/putty-tunnel-manager) Fixes and new release. PuTTY Tunnel Manager allows you to easily open tunnels, that are defined in a PuTTY session, from the system tray. You can also move the tunnels from PuTTY to PuTTY Tunnel Manager. This allows you to use PuTTY just for SSH shell sessions (without opening tunnels), and use PuTTY Tunnel Manager just for tunneling.
- [**26**星][4y] [Shell] [hrishioa/nomohead](https://github.com/hrishioa/nomohead) Simple Bash script that announces IP Address and ngrok tunnel of Raspberry Pi at boot
- [**26**星][6m] [CSS] [remmina/et-electron](https://github.com/remmina/et-electron) Eagle Tunnel 的图形化客户端，一个简单的代理工具
- [**26**星][7m] [Py] [rofl0r/nat-tunnel](https://github.com/rofl0r/nat-tunnel) NAT Tunnel: to effortlessly serve from behind NAT
- [**25**星][1y] [Go] [rsrdesarrollo/sasshimi](https://github.com/rsrdesarrollo/sasshimi) SSH Tunnelling in "RAW mode", via STDIN/OUT without using forwarding channels
- [**24**星][1y] [Go] [root-gg/wsp](https://github.com/root-gg/wsp) HTTP tunnel over Websocket
- [**23**星][2y] [Go] [gnolizuh/quictun](https://github.com/gnolizuh/quictun) The simplest tunnel service based on QUIC.
- [**23**星][4m] [Py] [jonathansalwan/x-tunnel-opaque-predicates](https://github.com/jonathansalwan/x-tunnel-opaque-predicates) IDA+Triton plugin in order to extract opaque predicates using a Forward-Bounded DSE. Example with X-Tunnel.
- [**21**星][2y] [Py] [krrr/wstan](https://github.com/krrr/wstan) Tunneling TCP in WebSocket (ssh -D alternative)
- [**20**星][2y] [C] [izuolan/pshell](https://github.com/izuolan/pshell) ICMP/IP tunnel manager for Linux.
- [**19**星][2m] [C++] [markopaul0/datagramtunneler](https://github.com/markopaul0/datagramtunneler) Simple C++ cross-platform client/server app forwarding UDP datagrams through a TCP connection.
- [**18**星][7m] [Go] [dsnet/sshtunnel](https://github.com/dsnet/sshtunnel) SSH daemon for creating forward and reverse tunnels.
- [**17**星][4y] [Py] [notsosecure/icmp_tunnel_ex_filtrate](https://github.com/notsosecure/icmp_tunnel_ex_filtrate) Code snippet accompanying blog post
- [**14**星][2m] [Py] [codepr/aiotunnel](https://github.com/codepr/aiotunnel) HTTP tunnel on top of aiohttp and asyncio
- [**14**星][2m] [Java] [testingbot/testingbot-tunnel](https://github.com/testingbot/testingbot-tunnel) Tunnel to run Cloud Selenium tests on your local computer
- [**8**星][1y] [C] [lalawue/m_tunnel](https://github.com/lalawue/m_tunnel) A Secure Tunnel with SOCKS5 Proxy Interface, support Linux/MacOS/FreeBSD/Windows
- [**8**星][1y] [C++] [mrdoulestar/yunsle_ghost_tunnel](https://github.com/mrdoulestar/yunsle_ghost_tunnel) 尝试实现一下Ghost Tunnel中的通信方式
- [**4**星][4y] [Haskell] [bearice/tunnel-manager](https://github.com/bearice/tunnel-manager) HTTP API to manage PPTP2HTTP tunnels
- [**4**星][2y] [JS] [bubuflystudio/bbtunnel](https://github.com/bubuflystudio/bbtunnel) 基于 socksv5 的内网穿透工具
- [**4**星][3y] [PHP] [cristianefe/mysqltunnel](https://github.com/cristianefe/mysqltunnel) A http MySQL remote tunnel
- [**3**星][4m] [C++] [osrdrivers/tunnel](https://github.com/osrdrivers/tunnel) Demonstrate the behavior of the tunnel cache on Windows
- [**2**星][4m] [Dockerfile] [robzhu/nginx-local-tunnel](https://github.com/robzhu/nginx-local-tunnel) A docker container that redirects incoming HTTP traffic to a local port for reverse SSH tunneling
- [**1**星][2y] [C++] [kkkkke/udp2raw-tunnel](https://github.com/kkkkke/udp2raw-tunnel) A Tunnel which Turns UDP Traffic into Encrypted UDP/FakeTCP/ICMP Traffic by using Raw Socket,helps you Bypass UDP FireWalls(or Unstable UDP Environment),Anti-Replay-Attack
- [**0**星][1y] [PS] [jerryma0912/ghosttunnel](https://github.com/jerryma0912/ghosttunnel) 基于360提出的Ghost Tunnel攻击复现


### <a id="8ea8f890cf767c3801b5e7951fca3570"></a>公网访问局域网


- [**31162**星][25d] [Go] [fatedier/frp](https://github.com/fatedier/frp) 快速的反向代理, 将NAT或防火墙之后的本地服务器暴露到公网
- [**9330**星][3m] [JS] [localtunnel/localtunnel](https://github.com/localtunnel/localtunnel) expose yourself
- [**5047**星][7d] [Go] [inlets/inlets](https://github.com/inlets/inlets) Expose your local endpoints to the Internet
- [**1264**星][10d] [JS] [bubenshchykov/ngrok](https://github.com/bubenshchykov/ngrok) Expose your localhost to the web. Node wrapper for ngrok.
- [**949**星][4m] [Py] [christophetd/cloudflair](https://github.com/christophetd/cloudflair) a tool to find origin servers of websites protected by CloudFlare who are publicly exposed and don't restrict network access to the CloudFlare IP ranges as they should




***


## <a id="c8cc22e067df97d3c58ac53b91ebe240"></a>文章




# <a id="891b953fda837ead9eff17ff2626b20a"></a>VPN


***


## <a id="d62a971d37c69db9f3b9187318c3921a"></a>工具


- [**16279**星][10d] [Py] [trailofbits/algo](https://github.com/trailofbits/algo) algo：Ansible 脚本（基于Python），简化配置私人 IPSEC VPN 的过程，默认使用最安全的配置，支持常见云提供商，并且大多数设备都不需要客户端
- [**12171**星][1m] [Shell] [hwdsl2/setup-ipsec-vpn](https://github.com/hwdsl2/setup-ipsec-vpn) Scripts to build your own IPsec VPN server, with IPsec/L2TP and Cisco IPsec on Ubuntu, Debian and CentOS
- [**10735**星][] [Go] [txthinking/brook](https://github.com/txthinking/brook) Go语言编写的跨平台代理
- [**7613**星][3m] [Py] [sovereign/sovereign](https://github.com/sovereign/sovereign) A set of Ansible playbooks to build and maintain your own private cloud: email, calendar, contacts, file sync, IRC bouncer, VPN, and more.
- [**4548**星][17d] [C] [jedisct1/dsvpn](https://github.com/jedisct1/dsvpn) A Dead Simple VPN.
- [**4449**星][1y] [Py] [sshuttle/sshuttle](https://github.com/sshuttle/sshuttle) Transparent proxy server that works as a poor man's VPN. Forwards over ssh. Doesn't require admin. Works with Linux and MacOS. Supports DNS tunneling.
- [**4049**星][2m] [Swift] [lexrus/vpnon](https://github.com/lexrus/vpnon) Turn On your VPN like a hero.
- [**3773**星][17d] [jjqqkk/chromium](https://github.com/jjqqkk/chromium) Chromium browser with SSL VPN. Use this browser to unblock websites.
- [**3243**星][6d] [Shell] [gfw-breaker/ssr-accounts](https://github.com/gfw-breaker/ssr-accounts) 一键部署Shadowsocks服务；免费Shadowsocks账号分享；免费SS账号分享; 翻墙；无界，自由门，SquirrelVPN
- [**3152**星][3m] [Shell] [hwdsl2/docker-ipsec-vpn-server](https://github.com/hwdsl2/docker-ipsec-vpn-server) Docker image to run an IPsec VPN server, with IPsec/L2TP and Cisco IPsec
- [**2558**星][13d] [Shell] [teddysun/across](https://github.com/teddysun/across) This is a shell script for configure and start WireGuard VPN server
- [**2430**星][15d] [Py] [pritunl/pritunl](https://github.com/pritunl/pritunl) Enterprise VPN server
- [**2131**星][4d] [C] [wireguard/wireguard](https://github.com/wireguard/wireguard) fast, modern, secure kernel VPN tunnel
- [**1740**星][6m] [Shell] [quericy/one-key-ikev2-vpn](https://github.com/quericy/one-key-ikev2-vpn) A bash script base on Centos or Ubuntu help you to create IKEV2/L2TP vpn.
- [**1600**星][1m] [C] [ntop/n2n](https://github.com/ntop/n2n) Peer-to-peer VPN
- [**1526**星][2m] [Shell] [haugene/docker-transmission-openvpn](https://github.com/haugene/docker-transmission-openvpn) Docker container running Transmission torrent client with WebUI over an OpenVPN tunnel
- [**1489**星][8m] [C++] [wangyu-/tinyfecvpn](https://github.com/wangyu-/tinyfecvpn) A VPN Designed for Lossy Links, with Build-in Forward Error Correction(FEC) Support. Improves your Network Quality on a High-latency Lossy Link.
- [**1185**星][4m] [C] [ambrop72/badvpn](https://github.com/ambrop72/badvpn) NCD scripting language, tun2socks proxifier, P2P VPN
- [**1044**星][2m] [Py] [ezaquarii/vpn-at-home](https://github.com/ezaquarii/vpn-at-home) 1-click, self-hosted deployment of OpenVPN with DNS ad blocking sinkhole
- [**1023**星][12m] [Go] [twitchyliquid64/subnet](https://github.com/twitchyliquid64/subnet) Simple, auditable & elegant VPN, built with TLS mutual authentication and TUN.
- [**1000**星][8m] [Go] [adtac/autovpn](https://github.com/adtac/autovpn) THIS PROJECT IS UNMAINTAINED.
- [**994**星][4m] [C] [gsliepen/tinc](https://github.com/gsliepen/tinc) a VPN daemon
- [**911**星][9m] [Shell] [ivanilves/xiringuito](https://github.com/ivanilves/xiringuito) SSH-based "VPN for poors"
- [**910**星][4d] [Go] [mehrdadrad/radvpn](https://github.com/mehrdadrad/radvpn) Decentralized VPN
- [**884**星][2y] [Py] [nsacyber/gosecure](https://github.com/nsacyber/goSecure) An easy to use and portable Virtual Private Network (VPN) system built with Linux and a Raspberry Pi. #nsacyber
- [**721**星][7m] [C] [meyerd/n2n](https://github.com/meyerd/n2n) A development branch of the n2n p2p vpn software
- [**693**星][12d] [Kotlin] [mygod/vpnhotspot](https://github.com/mygod/vpnhotspot) Share your VPN connection over hotspot or repeater! (root required)
- [**688**星][1m] [OCaml] [moby/vpnkit](https://github.com/moby/vpnkit) A toolkit for embedding VPN capabilities in your application
- [**641**星][2y] [Shell] [kitten/setup-simple-ipsec-l2tp-vpn](https://github.com/kitten/setup-simple-ipsec-l2tp-vpn) Setup a simple IPSec/L2TP VPN Server for Ubuntu and Debian
- [**635**星][26d] [webdigi/aws-vpn-server-setup](https://github.com/webdigi/aws-vpn-server-setup) Setup your own private, secure, free* VPN on the Amazon AWS Cloud in 10 minutes. CloudFormation
- [**598**星][27d] [C] [openvpn/openvpn-gui](https://github.com/openvpn/openvpn-gui) OpenVPN GUI is a graphical frontend for OpenVPN running on Windows XP / Vista / 7 / 8. It creates an icon in the notification area from which you can control OpenVPN to start/stop your VPN tunnels, view the log and do other useful things.
- [**581**星][5d] [Go] [mysteriumnetwork/node](https://github.com/mysteriumnetwork/node) Mysterium Node - VPN server and client for decentralized Mysterium Network
- [**482**星][1y] [Swift] [icepa/icepa](https://github.com/icepa/icepa) iOS system-wide VPN based Tor client
- [**460**星][3y] [Py] [vpnguy-zz/ntpdos](https://github.com/vpnguy-zz/ntpdos) Create a DDOS attack using NTP servers
- [**452**星][2m] [Shell] [l-n-s/wireguard-install](https://github.com/l-n-s/wireguard-install) WireGuard VPN server installer
- [**429**星][3m] [Py] [jotygill/openpyn-nordvpn](https://github.com/jotygill/openpyn-nordvpn) Easily connect to and switch between, OpenVPN servers hosted by NordVPN on Linux (+patch leakes)
- [**416**星][3m] [Rust] [exodusvpn/exodus](https://github.com/ExodusVPN/exodus) network proxy and tunnel (VPN)
- [**350**星][6m] [Shell] [hackplayers/4nonimizer](https://github.com/hackplayers/4nonimizer) A bash script for anonymizing the public IP used to browsing Internet, managing the connection to TOR network and to different VPNs providers (OpenVPN)
- [**341**星][2y] [Py] [sarfata/voodooprivacy](https://github.com/sarfata/voodooprivacy) Roll your own VPN server on Amazon EC2 and battle-ready firewall for OS X
- [**327**星][2y] [Swift] [yichengchen/rabbitvpndemo](https://github.com/yichengchen/rabbitvpndemo) a demo project for testing iOS network extension with NEkit
- [**307**星][6m] [Batchfile] [lmc999/auto-add-routes](https://github.com/lmc999/auto-add-routes) China Route for VPN
- [**288**星][3m] [Py] [covertcodes/multitun](https://github.com/covertcodes/multitun) Tunnel arbitrary traffic through an innocuous WebSocket. Clients can 'see' each other, resulting in a stealth WebSocket VPN.
- [**263**星][2m] [C#] [airvpn/eddie](https://github.com/airvpn/eddie) OpenVPN UI
- [**255**星][4m] [Shell] [projectzeroindia/cve-2019-11510](https://github.com/projectzeroindia/cve-2019-11510) Exploit for Arbitrary File Read on Pulse Secure SSL VPN (CVE-2019-11510)
- [**251**星][3m] [Py] [corrad1nho/qomui](https://github.com/corrad1nho/qomui) Qomui (Qt OpenVPN Management UI)
- [**247**星][2y] [Py] [spaze/oprah-proxy](https://github.com/spaze/oprah-proxy) Generate credentials for Opera's "browser VPN"
- [**195**星][2y] [Py] [f3d0x0/gpon](https://github.com/f3d0x0/gpon) Exploit for Remote Code Execution on GPON home routers (CVE-2018-10562) written in Python. Initially disclosed by VPNMentor (
- [**190**星][4m] [Go] [cloudfoundry-incubator/cfdev](https://github.com/cloudfoundry-incubator/cfdev) A fast and easy local Cloud Foundry experience on native hypervisors, powered by LinuxKit with VPNKit
- [**185**星][1y] [Perl] [microsoft/pqcrypto-vpn](https://github.com/microsoft/pqcrypto-vpn) Post-quantum Cryptography VPN
- [**175**星][2m] [Go] [gavinguan24/ahri](https://github.com/gavinguan24/ahri) Ahri is an intranet sharing tool. Like VPN
- [**169**星][7m] [JS] [sentinel-official/sentinel](https://github.com/sentinel-official/sentinel) Sentinel is an interoperable secure network layer offering the Sentinel Service Chain exclusively for distributed & decentralized native services like - dVPN, Sentrix (dChat and dVoIP) and more.
- [**154**星][3y] [Makefile] [0x36/vpnpivot](https://github.com/0x36/vpnpivot) Explore the network using VPNPivot tool
- [**147**星][4y] [C] [valdikss/openvpn-fix-dns-leak-plugin](https://github.com/valdikss/openvpn-fix-dns-leak-plugin) OpenVPN plugin to fix Windows DNS Leaks
- [**143**星][10m] [Shell] [essandess/macos-openvpn-server](https://github.com/essandess/macos-openvpn-server) macOS OpenVPN Server and Client Configuration (OpenVPN, Tunnelblick, PF)
- [**142**星][4y] [C] [valdikss/p0f-mtu](https://github.com/valdikss/p0f-mtu) p0f with patches to save MTU value and export it via API (for VPN detection)
- [**140**星][4m] [Go] [skx/simple-vpn](https://github.com/skx/simple-vpn) A simple VPN allowing mesh-like communication between nodes, over websockets
- [**131**星][6d] [Shell] [binhex/arch-rtorrentvpn](https://github.com/binhex/arch-rtorrentvpn) Docker build script for Arch Linux base with ruTorrent, rTorrent, autodl-irssi, Privoxy and OpenVPN
- [**123**星][4y] [Shell] [91yun/vpn](https://github.com/91yun/vpn) vpn一键安装包
- [**115**星][2y] [Py] [dragon2fly/vpngate-with-proxy](https://github.com/dragon2fly/vpngate-with-proxy) vpn gate client for linux, be able to connect to open vpn server through proxy
- [**115**星][1y] [Shell] [wknapik/vpnfailsafe](https://github.com/wknapik/vpnfailsafe) IP leak prevention for OpenVPN
- [**113**星][2y] [bobnisco/adblocking-vpn](https://github.com/bobnisco/adblocking-vpn) 
- [**111**星][2y] [Shell] [adrelanos/vpn-firewall](https://github.com/adrelanos/vpn-firewall) Leak Protection (Fail Safe Mechanism) for (Open)VPN
- [**110**星][2y] [JS] [voidsec/webrtc-leak](https://github.com/voidsec/webrtc-leak) Check if your VPN leaks your IP address via the WebRTC technology
- [**105**星][4y] [Go] [netxfly/transparent-proxy-scanner](https://github.com/netxfly/transparent-proxy-scanner) 基于vpn和透明代理的web漏洞扫描器的实现思路及demo
- [**102**星][11m] [C] [ryd/chaosvpn](https://github.com/ryd/chaosvpn) Config generator for chaos vpn
- [**93**星][18d] [Py] [chadsr/nordvpn-networkmanager](https://github.com/chadsr/nordvpn-networkmanager) A CLI tool for automating the importing, securing and usage of NordVPN (and in the future, more) OpenVPN servers through NetworkManager.
- [**91**星][2y] [Py] [pry0cc/proxydock](https://github.com/pry0cc/proxydock) ProxyDock is a Dockerfile and Bash script that converts your OpenVPN files into local proxies.
- [**90**星][2y] [C++] [azirevpn/azclient](https://github.com/azirevpn/azclient) Customizable VPN client, meant to be simple and sleek.
- [**90**星][4y] [Shell] [primaryobjects/vpndemon](https://github.com/primaryobjects/vpndemon) Monitor a VPN connection on Linux and kill a process upon disconnect
- [**83**星][4d] [Shell] [esemeniuc/ezpptp](https://github.com/esemeniuc/ezpptp) Easy PPTP VPN setup script for Debian based VPS
- [**82**星][8m] [Go] [cogolabs/transcend](https://github.com/cogolabs/transcend) BeyondCorp-inspired Access Proxy. Secure internal services outside your VPN/perimeter network during a zero-trust transition.
- [**77**星][2m] [Py] [ab77/black.box](https://github.com/ab77/black.box) Plug-and-Play VPN router and unblocker
- [**76**星][1y] [Shell] [kolargol/openvpn](https://github.com/kolargol/openvpn) Shell 脚本，5分钟建立个人 VPN
- [**72**星][4d] [C++] [orchidtechnologies/orchid](https://github.com/OrchidTechnologies/orchid) Orchid: VPN, Personal Firewall
- [**72**星][4d] [C++] [orchidtechnologies/orchid](https://github.com/orchidtechnologies/orchid) Orchid: VPN, Personal Firewall
- [**70**星][1m] [Go] [vpn-kill-switch/killswitch](https://github.com/vpn-kill-switch/killswitch) VPN kill switch for macOS
- [**67**星][6m] [Shell] [tasket/qubes-vpn-support](https://github.com/tasket/qubes-vpn-support) VPN configuration in Qubes OS
- [**64**星][3y] [Perl] [0x90/vpn-arsenal](https://github.com/0x90/vpn-arsenal) VPN pentest tools and scripts
- [**58**星][7m] [Go] [dsnet/udptunnel](https://github.com/dsnet/udptunnel) Daemon for creating a simple VPN over UDP.
- [**55**星][3m] [Shell] [bishopfox/pwn-pulse](https://github.com/bishopfox/pwn-pulse) Exploit for Pulse Connect Secure SSL VPN arbitrary file read vulnerability (CVE-2019-11510)
- [**53**星][8m] [Shell] [laserbat/vpnify](https://github.com/laserbat/vpnify) vpnify - transparently route traffic of a process through VPN
- [**50**星][11m] [C] [acoinfo/kidvpn](https://github.com/acoinfo/kidvpn) The world's smallest VPN server and client.
- [**47**星][3y] [Go] [inszva/tap0901](https://github.com/inszva/tap0901) Go语言虚拟网卡库，可用于制作对战平台、加速器、防火墙、VPN等
- [**42**星][3y] [C] [lxdcn/simple-vpn-demo](https://github.com/lxdcn/simple-vpn-demo) A Simple Point-to-Point tunnelling implementation in C
- [**40**星][2y] [Shell] [xaqron/stunnel](https://github.com/xaqron/stunnel) Wrapping openvpn with stunnel
- [**36**星][4m] [Shell] [hromie/obfs4proxy-openvpn](https://github.com/hromie/obfs4proxy-openvpn) Obfuscating OpenVPN traffic using obfs4proxy
- [**34**星][3y] [Shell] [dlshad/openvpn-shapeshifter](https://github.com/dlshad/openvpn-shapeshifter) This script will automatically guide you to install and configure your OpenVPN server with Shapeshifter Dispatcher (obfuscation) which will allow you to bypass the DPI blockage on OpenVPN. This setup will offer the users the freedom to choose between regular OpenVPN connection or obfuscated one, they actually can use both! OpenVPN is the VPN pro…
- [**33**星][11m] [Py] [qwj/python-esp](https://github.com/qwj/python-esp) IPSec IKE(v1,v2) PSK VPN implemented in pure Python. (For Research Purposes Only)
- [**32**星][2m] [Go] [shikanon/socks5proxy](https://github.com/shikanon/socks5proxy) 一个简单的socks5代理转发服务(VPN)
- [**31**星][2y] [C] [alienrobotarmy/ctunnel](https://github.com/alienrobotarmy/ctunnel) ctunnel is a proxy and VPN software for tunneling TCP and UDP connections securely
- [**29**星][4y] [Makefile] [radicallyopensecurity/netaidkit](https://github.com/radicallyopensecurity/netaidkit) Standalone VPN/Tor WiFi router for journalists and activists
    - 重复区段: [匿名网络->工具->Tor](#e99ba5f3de02f68412b13ca718a0afb6) |
- [**27**星][2m] [HTML] [tkvpn/tkvpn.github.io](https://github.com/tkvpn/tkvpn.github.io) 这里提供全球多个网络加速节点，速度极快，提供免费试用。
- [**26**星][9m] [Shell] [shverni/raspberry-pi-vpn-gateway](https://github.com/shverni/raspberry-pi-vpn-gateway) Raspberry Pi VPN gateway installer for Private Internet Access
- [**25**星][1y] [Tcl] [fruho/fruhoapp](https://github.com/fruho/fruhoapp) Fruho VPN Manager - Universal VPN Client |
- [**25**星][9m] [Py] [letheanmovement/lethean-vpn](https://github.com/letheanmovement/lethean-vpn) Lethean Virtual Private Network (VPN)
- [**23**星][21d] [PHP] [ip2location/ip2proxy-php](https://github.com/ip2location/ip2proxy-php) PHP module for IP2Proxy database lookup. It allows user to query an IP address if it was being used as open proxy, web proxy, VPN anonymizer and TOR exits.
- [**23**星][8m] [PHP] [mrahmadt/smartgw](https://github.com/mrahmadt/smartgw) Domain based VPN Gateway/Proxy for all devices
- [**22**星][12d] [Py] [wisepythagoras/website-fingerprinting](https://github.com/wisepythagoras/website-fingerprinting) Deanonymizing Tor or VPN users with website fingerprinting and machine learning.
- [**22**星][3m] [Dockerfile] [kizzx2/docker-openvpn-client-socks](https://github.com/kizzx2/docker-openvpn-client-socks) Expose an OpenVPN tunnel as a SOCKS proxy
- [**22**星][12d] [Py] [wisepythagoras/website-fingerprinting](https://github.com/wisepythagoras/website-fingerprinting) Deanonymizing Tor or VPN users with website fingerprinting and machine learning.
- [**21**星][3y] [Py] [toolsprods/sniffvpn](https://github.com/toolsprods/sniffvpn) Traffic monitor for your VPN
- [**19**星][4y] [HTML] [cryptostorm-dev/cleanvpn.xyz](https://github.com/cryptostorm-dev/cleanvpn.xyz) A place to research & publicly certify malware-free, fully operational VPN services
- [**17**星][3y] [Shell] [jxzy199306/ipv6_dhclient_online_net](https://github.com/jxzy199306/ipv6_dhclient_online_net) seedbox一键脚本 Deluge+Flexget,rutorrent, rtorrent + ruTorrent,Transmission+Flexget,FTP,VPN,VNC,SSH Proxy,Rapidleec
- [**16**星][3m] [Py] [andresriancho/vpc-vpn-pivot](https://github.com/andresriancho/vpc-vpn-pivot) Pivot into private VPC networks using a VPN connection
- [**14**星][1y] [C#] [t0nic/killswitch-windows](https://github.com/t0nic/killswitch-windows) VPN kill switch for windows.
- [**11**星][6m] [Go] [threatstack/vpnnotify](https://github.com/threatstack/vpnnotify) It tells you when you VPN
- [**10**星][3y] [Shell] [perunworks/zenected](https://github.com/perunworks/zenected) Zenected Threat Defense VPN
- [**9**星][2y] [C] [guidovranken/softethervpn-fuzz-audit](https://github.com/guidovranken/softethervpn-fuzz-audit) 
- [**9**星][jasper-1024/shadowsocksr-csharp](https://github.com/jasper-1024/shadowsocksr-csharp) ShadowsocksR for Windows
- [**8**星][2y] [C] [penmast/chameleon](https://github.com/penmast/chameleon) A Windows application-specific VPN and network monitoring tool
- [**7**星][10d] [Py] [dlenski/what-vpn](https://github.com/dlenski/what-vpn) Identify servers running various SSL VPNs based on protocol-specific behaviors
- [**7**星][3y] [jas502n/ngrok.snvpn.org](https://github.com/jas502n/ngrok.snvpn.org) 自己搭建的一个ngrok服务器，可以全球访问
- [**5**星][5y] [C] [inode-/vpnc-brute](https://github.com/inode-/vpnc-brute) 
- [**5**星][3y] [JS] [mitchellurgero/pivpn-gui](https://github.com/mitchellurgero/pivpn-gui) THIS PROJECT IS DEAD. PLEASE USE OPENRSD WHICH INCLUDES THIS GUI -
- [**4**星][1m] [Shell] [gardener/vpn](https://github.com/gardener/vpn) Network connector between the control plane (deployed in a Seed cluster) and a Shoot cluster.
- [**4**星][3y] [Shell] [zecopro/fix-vpn-kali-linux](https://github.com/zecopro/fix-vpn-kali-linux) this script for fix problem vpn on kali linux "Rooling" only :)
- [**4**星][3y] [C] [ddlsmurf/sov](https://github.com/ddlsmurf/sov) Starcraft over VPN
- [**2**星][1y] [Py] [paloaltonetworks/microsoft_azure_virtual_wan](https://github.com/paloaltonetworks/microsoft_azure_virtual_wan) Implements the automation and integration framework to work with Azure Virtual WAN's and PANW to create VPN connections.
- [**0**星][2y] [alt3kx/cve-2009-4118](https://github.com/alt3kx/cve-2009-4118) Cisco VPN Client - Integer Overflow Denial of Service


***


## <a id="7cf7e8a30b73997985f20698eaf6b0c9"></a>OpenVPN


- [**10693**星][2m] [Shell] [nyr/openvpn-install](https://github.com/nyr/openvpn-install) OpenVPN road warrior installer for Debian, Ubuntu and CentOS
- [**4354**星][1m] [C] [openvpn/openvpn](https://github.com/openvpn/openvpn) OpenVPN is an open source VPN daemon
- [**4050**星][1m] [Shell] [angristan/openvpn-install](https://github.com/angristan/openvpn-install) Set up your own OpenVPN server on Debian, Ubuntu, Fedora, CentOS or Arch Linux.
- [**2708**星][24d] [Shell] [pivpn/pivpn](https://github.com/pivpn/pivpn) 树莓派的OpenVPN安装程序
- [**1834**星][2m] [Shell] [ttlequals0/autovpn](https://github.com/ttlequals0/autovpn) Create On Demand Disposable OpenVPN Endpoints on AWS.
- [**833**星][3y] [Shell] [robbintt/popup-openvpn](https://github.com/robbintt/popup-openvpn) Make a self hosted OpenVPN server in 15 minutes
- [**598**星][2m] [PHP] [chocobozzz/openvpn-admin](https://github.com/chocobozzz/openvpn-admin) Install and administrate OpenVPN with a web interface (logs visualisations, users managing...)
- [**357**星][12d] [C++] [openvpn/openvpn3](https://github.com/openvpn/openvpn3) OpenVPN 3 is a C++ class library that implements the functionality of an OpenVPN client, and is protocol-compatible with the OpenVPN 2.x branch.
- [**230**星][1y] [Py] [audibleblink/doxycannon](https://github.com/audibleblink/doxycannon) 为一堆OpenVPN文件分别创建Docker容器, 每个容器开启SOCKS5代理服务器并绑定至Docker主机端口, 再结合使用Burp或ProxyChains, 构建私有的Botnet
- [**214**星][2m] [C++] [ss-abramchuk/openvpnadapter](https://github.com/ss-abramchuk/openvpnadapter) Objective-C wrapper for OpenVPN library. Compatible with iOS and macOS.
- [**142**星][3m] [Gherkin] [iphoting/ovpnmcgen.rb](https://github.com/iphoting/ovpnmcgen.rb) An OpenVPN iOS Configuration Profile (.mobileconfig) Utility—Configures OpenVPN for use with VPN-on-Demand that are not exposed through Apple Configurator 2.
- [**35**星][20d] [Go] [mysteriumnetwork/go-openvpn](https://github.com/mysteriumnetwork/go-openvpn) 
- [**28**星][5y] [Py] [phaeilo/vol-openvpn](https://github.com/phaeilo/vol-openvpn) A Volatility plugin to extract credentials from the memory of a OpenVPN client.
- [**27**星][2y] [C] [guidovranken/openvpn](https://github.com/guidovranken/openvpn) OpenVPN is an open source VPN daemon
- [**23**星][2m] [Shell] [binhex/arch-int-openvpn](https://github.com/binhex/arch-int-openvpn) Docker build script for Arch Linux base with OpenVPN and Privoxy
- [**21**星][5y] [C] [valdikss/openvpn-radiusplugin](https://github.com/valdikss/openvpn-radiusplugin) Radiusplugin with various patches and fixes
- [**17**星][4y] [rootkitsmm/openvpn-pool-overflow](https://github.com/rootkitsmm/openvpn-pool-overflow) Pool Overflow in OpenVpn NDIS TAP Driver
- [**15**星][3y] [Go] [tazjin/watchblob](https://github.com/tazjin/watchblob) Connect to 2-factor WatchGuard VPNs on Linux with OpenVPN
- [**8**星][4m] [Py] [egeneralov/rkn-vpn-configurator](https://github.com/egeneralov/rkn-vpn-configurator) Configure OpenVPN with bypass rkn.gov.ru limits.
- [**6**星][1y] [C++] [mysteriumnetwork/openvpn3](https://github.com/mysteriumnetwork/openvpn3) OpenVPN 3 is a C++ class library that implements the functionality of an OpenVPN client, and is protocol-compatible with the OpenVPN 2.x branch.
- [**5**星][2y] [Shell] [devindevoir/openvpn-installer](https://github.com/devindevoir/openvpn-installer) Secure OpenVPN installer for Debian, Ubuntu, CentOS and Arch Linux.
- [**3**星][6m] [Shell] [2stacks/docker-ovpn](https://github.com/2stacks/docker-ovpn) OpenVPN Server in Docker Container
- [**3**星][2y] [HCL] [abacao/do_tinfoil](https://github.com/abacao/do_tinfoil) Create and provision a OpenVPN server in DigitalOcean with Terraform
- [**1**星][2y] [Shell] [entaopy/dostreisand](https://github.com/entaopy/dostreisand) Streisand sets up a new server running L2TP/IPsec, OpenConnect, OpenSSH, OpenVPN, Shadowsocks, sslh, Stunnel, a Tor bridge, and WireGuard. It also generates custom instructions for all of these services. At the end of the run you are given an HTML file with instructions that can be shared with friends, family members, and fellow activists.
- [**0**星][1y] [Shell] [frichetten/streisand](https://github.com/frichetten/streisand) Streisand sets up a new server running your choice of WireGuard, OpenConnect, OpenSSH, OpenVPN, Shadowsocks, sslh, Stunnel, or a Tor bridge. It also generates custom instructions for all of these services. At the end of the run you are given an HTML file with instructions that can be shared with friends, family members, and fellow activists.


# <a id="3c28b67524f117ed555daed9cc99e35e"></a>分析&&取证&&诊断&&探查&&检测&&嗅探


***


## <a id="7bf0f5839fb2827fdc1b93ae6ac7f53d"></a>工具


### <a id="b346105580b0240d693020ce8719ebca"></a>未分类


- [**3527**星][5d] [JS] [aol/moloch](https://github.com/aol/moloch) 数据包捕获、索引工具，支持数据库
- [**3000**星][4d] [JS] [ntop/ntopng](https://github.com/ntop/ntopng) 基于Web的流量监控工具
- [**1919**星][4d] [C] [ntop/ndpi](https://github.com/ntop/ndpi) Open Source Deep Packet Inspection Software Toolkit
- [**1893**星][6d] [C] [merbanan/rtl_433](https://github.com/merbanan/rtl_433) 解码来自以433.9 MHz广播的设备（例如温度传感器）的流量
- [**1283**星][1m] [Go] [dreadl0ck/netcap](https://github.com/dreadl0ck/netcap) A framework for secure and scalable network traffic analysis -
- [**957**星][1m] [Py] [fireeye/flare-fakenet-ng](https://github.com/fireeye/flare-fakenet-ng) 下一代动态网络分析工具
- [**934**星][2y] [Py] [tomchop/malcom](https://github.com/tomchop/malcom) Malcom - Malware Communications Analyzer
- [**918**星][2y] [HTML] [snorby/snorby](https://github.com/snorby/snorby) Ruby On Rails Application For Network Security Monitoring
- [**726**星][3m] [Py] [cloudflare/bpftools](https://github.com/cloudflare/bpftools) BPF Tools - packet analyst toolkit
- [**711**星][2y] [Py] [google/ssl_logger](https://github.com/google/ssl_logger) 解密并记录进程的SSL 流程
- [**519**星][5d] [C++] [kohler/click](https://github.com/kohler/click) The Click modular router: fast modular packet processing and analysis
- [**481**星][7d] [C#] [chmorgan/sharppcap](https://github.com/chmorgan/sharppcap) 用于捕获数据包的跨平台 (Windows, Mac, Linux)库，.NET编写
- [**448**星][3d] [C#] [malwareinfosec/ekfiddle](https://github.com/malwareinfosec/ekfiddle) Fiddler Web调试器的框架，用于研究漏洞利用工具包、恶意广告和恶意流量
    - 重复区段: [工具->fiddler](#31d28e8b2cf6c06411cd5d178dbd3e77) |
- [**441**星][3m] [C++] [pstavirs/ostinato](https://github.com/pstavirs/ostinato) Packet/Traffic Generator and Analyzer
- [**409**星][9m] [Py] [mitrecnd/chopshop](https://github.com/mitrecnd/chopshop) Protocol Analysis/Decoder Framework
- [**397**星][4d] [Py] [idaholab/malcolm](https://github.com/idaholab/malcolm) Malcolm is a powerful, easily deployable network traffic analysis tool suite for full packet capture artifacts (PCAP files) and Zeek logs.
- [**316**星][2y] [Py] [tnich/honssh](https://github.com/tnich/honssh) 记录客户端和服务器之间的所有 SSH 通信
- [**286**星][2m] [Shell] [tehw0lf/airbash](https://github.com/tehw0lf/airbash) 全自动的WPAPSK握手包捕获脚本, 用于渗透测试
- [**274**星][19d] [Py] [ghostop14/sparrow-wifi](https://github.com/ghostop14/sparrow-wifi) Next-Gen GUI-based WiFi and Bluetooth Analyzer for Linux
- [**210**星][8m] [JS] [dirtbags/pcapdb](https://github.com/dirtbags/pcapdb) 网络数据包捕获系统，分布式，对搜索进行了优化
- [**194**星][6m] [Go] [cuishark/cuishark](https://github.com/cuishark/cuishark) A protocol analyzer like a wireshark on CUI. cuishark is using libwireshark to analyze packets.
- [**67**星][3y] [JS] [pythonran/pcap_tools](https://github.com/pythonran/pcap_tools) 网络流量可配置嗅探，流量包解析，漏洞规则扫描，生成报告
- [**65**星][1y] [Py] [ch3k1/squidmagic](https://github.com/ch3k1/squidmagic) analyze a web-based network traffic


### <a id="8dd8c4c8d11c149aa803a221480687d2"></a>协议分析


- [**1454**星][4d] [Go] [skydive-project/skydive](https://github.com/skydive-project/skydive) An open source real-time network topology and protocols analyzer
- [**472**星][2m] [Py] [netzob/netzob](https://github.com/netzob/netzob) 通信协议逆向、建模和模糊测试


### <a id="9dfefb87c4dc3288b2eddf6780e8ffb9"></a>网络诊断


- [**2536**星][2y] [Py] [google/nogotofail](https://github.com/google/nogotofail) 帮助开发人员和安全研究人员在设备和应用程序上发现并修复弱TLS / SSL连接问题，定位敏感的明文流量。灵活、可扩展、功能强大
- [**2249**星][2y] [Go] [mehrdadrad/mylg](https://github.com/mehrdadrad/mylg) 网络诊断工具
- [**1302**星][17d] [C] [traviscross/mtr](https://github.com/traviscross/mtr) 结合“ traceroute”和“ ping”的功能，用于网络诊断


### <a id="b3811e8d4be5755957b0ec0e336715a2"></a>取证


- [**5208**星][7m] [Py] [usarmyresearchlab/dshell](https://github.com/usarmyresearchlab/dshell) 可扩展的网络取证分析框架。支持快速开发插件，以支持剖析网络数据包捕获。
- [**791**星][4m] [Py] [srinivas11789/pcapxray](https://github.com/srinivas11789/pcapxray) 网络取证工具：离线将捕获数据包可视化为网络图，包括设备标识，突出显示重要的通信和文件提取
- [**31**星][5y] [Py] [madpowah/forensicpcap](https://github.com/madpowah/forensicpcap) pcap取证
- [**11**星][3y] [Py] [nipunjaswal/wireless-forensics-framework](https://github.com/nipunjaswal/wireless-forensics-framework) Wireless Forensics Framework In Python


### <a id="07701b342951b5d7bfa839db7752f9dd"></a>Xx分析


- [**527**星][1m] [Py] [hatboy/pcap-analyzer](https://github.com/hatboy/pcap-analyzer) Python编写的可视化的离线数据包分析器
- [**381**星][5y] [JS] [le4f/pcap-analyzer](https://github.com/le4f/pcap-analyzer) 在线轻量Pcap流量文件分析工具
- [**211**星][1y] [Py] [mateuszk87/pcapviz](https://github.com/mateuszk87/pcapviz) 可视化网络拓扑，基于pcap文件收集图形统计信息
- [**122**星][5y] [JS] [thepacketgeek/cloud-pcap](https://github.com/thepacketgeek/cloud-pcap) Web PCAP存储和分析


### <a id="32739127f0c38d61b14448c66a797098"></a>嗅探&&Sniff


- [**3510**星][8m] [Go] [fanpei91/torsniff](https://github.com/fanpei91/torsniff) 从BitTorrent网络嗅探种子
- [**3510**星][8m] [Go] [fanpei91/torsniff](https://github.com/fanpei91/torsniff) 从BitTorrent网络嗅探种子
- [**1756**星][8d] [PHP] [wordpress/wordpress-coding-standards](https://github.com/wordpress/wordpress-coding-standards) PHP_CodeSniffer rules (sniffs) to enforce WordPress coding conventions
- [**1536**星][5d] [C++] [nmap/npcap](https://github.com/nmap/npcap) Nmap项目的针对Windows系统的数据包嗅探库，基于WinPcap/Libpcap，用NDIS6和LWF做了升级
- [**1338**星][3m] [C++] [mfontanini/libtins](https://github.com/mfontanini/libtins) High-level, multiplatform C++ network packet sniffing and crafting library.
- [**1333**星][1y] [C] [gamelinux/passivedns](https://github.com/gamelinux/passivedns) A network sniffer that logs all DNS server replies for use in a passive DNS setup
- [**1232**星][4d] [Py] [danmcinerney/net-creds](https://github.com/danmcinerney/net-creds) Sniffs sensitive data from interface or pcap
- [**1064**星][7m] [PS] [nytrorst/netripper](https://github.com/nytrorst/netripper) 后渗透工具,针对Windows, 使用API Hooking拦截网络流量和加密相关函数, 可捕获明文和加密前后的内容
- [**994**星][1y] [Py] [tylous/sniffair](https://github.com/tylous/sniffair) 无线渗透框架. 解析被动收集的无线数据, 执行复杂的无线攻击
- [**928**星][3y] [Eagle] [samyk/keysweeper](https://github.com/samyk/keysweeper) KeySweeper is a stealthy Arduino-based device, camouflaged as a functioning USB wall charger, that wirelessly and passively sniffs, decrypts, logs and reports back (over GSM) all keystrokes from any Microsoft wireless keyboard in the vicinity.
- [**922**星][2y] [JS] [diracdeltas/sniffly](https://github.com/diracdeltas/sniffly) Sniffing browser history using HSTS
- [**884**星][7m] [Go] [40t/go-sniffer](https://github.com/40t/go-sniffer) 
- [**796**星][8m] [Py] [phaethon/kamene](https://github.com/phaethon/kamene) Network packet and pcap file crafting/sniffing/manipulation/visualization security tool. Originally forked from scapy in 2015 and providing python3 compatibility since then.
    - 重复区段: [工具->Scapy](#01f99d208e245eb44f15f720043b50d4) |
- [**788**星][3m] [C] [netsniff-ng/netsniff-ng](https://github.com/netsniff-ng/netsniff-ng) A Swiss army knife for your daily Linux network plumbing.
- [**716**星][2y] [Py] [madeye/sssniff](https://github.com/madeye/sssniff) sssniff：ShadowSocks流量嗅探
- [**642**星][1y] [Go] [ga0/netgraph](https://github.com/ga0/netgraph) A cross platform http sniffer with a web UI
- [**639**星][2y] [C] [qihoo360/mysql-sniffer](https://github.com/qihoo360/mysql-sniffer) mysql-sniffer is a network traffic analyzer tool for mysql, it is developed by Qihoo DBA and infrastructure team
- [**635**星][2y] [Py] [mschwager/dhcpwn](https://github.com/mschwager/dhcpwn)  testing DHCP IP exhaustion attacks， sniff local DHCP traffic
- [**626**星][3m] [Go] [eldadru/ksniff](https://github.com/eldadru/ksniff) Kubectl plugin to ease sniffing on kubernetes pods using tcpdump and wireshark
- [**565**星][11d] [PHP] [object-calisthenics/phpcs-calisthenics-rules](https://github.com/object-calisthenics/phpcs-calisthenics-rules) Object Calisthenics rules for PHP_CodeSniffer
- [**478**星][7d] [pixelcyber/thor](https://github.com/pixelcyber/thor) HTTP Sniffer/Capture on iOS for Network Debug & Inspect.
- [**459**星][5m] [C] [jarun/keysniffer](https://github.com/jarun/keysniffer) 
- [**432**星][3m] [Ruby] [aderyabin/sniffer](https://github.com/aderyabin/sniffer) Log and Analyze Outgoing HTTP Requests
- [**427**星][6d] [Rust] [kpcyrd/sniffglue](https://github.com/kpcyrd/sniffglue) Secure multithreaded packet sniffer
- [**401**星][5m] [PHP] [floedesigntechnologies/phpcs-security-audit](https://github.com/floedesigntechnologies/phpcs-security-audit) phpcs-security-audit is a set of PHP_CodeSniffer rules that finds vulnerabilities and weaknesses related to security in PHP code
- [**316**星][5y] [C] [seastorm/puttyrider](https://github.com/seastorm/puttyrider) Hijack Putty sessions in order to sniff conversation and inject Linux commands.
- [**293**星][5m] [C] [pulkin/esp8266-injection-example](https://github.com/pulkin/esp8266-injection-example) Example project to demonstrate packet injection / sniffer capabilities of ESP8266 IC.
- [**291**星][10m] [C] [jiaoxianjun/btle](https://github.com/jiaoxianjun/btle) Bluetooth Low Energy (BLE) packet sniffer and generator for both standard and non standard (raw bit).
- [**264**星][2m] [Py] [xdavidhu/probesniffer](https://github.com/xdavidhu/probesniffer) 
- [**260**星][8m] [Py] [needmorecowbell/sniff-paste](https://github.com/needmorecowbell/sniff-paste) Pastebin OSINT Harvester
- [**250**星][1m] [C] [nccgroup/sniffle](https://github.com/nccgroup/sniffle) A sniffer for Bluetooth 5 and 4.x LE
- [**236**星][2y] [C++] [pellegre/libcrafter](https://github.com/pellegre/libcrafter) C++ 编写的网络数据包嗅探和解码库
- [**229**星][3y] [C] [omriiluz/nrf24-btle-decoder](https://github.com/omriiluz/nrf24-btle-decoder) Sniff and decode NRF24L01+ and Bluetooth Low Energy using RTL-SDR
- [**198**星][3y] [Py] [isofew/sssniff](https://github.com/isofew/sssniff) ShadowSocks(SS) traffic sniffer
- [**191**星][3m] [Py] [alainiamburg/sniffrom](https://github.com/alainiamburg/sniffrom) A tool for passive data capture and reconnaissance of serial flash chips. It is used in conjunction with a Saleae logic analyzer to reconstruct flash memory contents and extract contextual information about device operations.
- [**179**星][1y] [Shell] [brannondorsey/sniff-probes](https://github.com/brannondorsey/sniff-probes) Plug-and-play bash script for sniffing 802.11 probes requests
- [**179**星][6y] [Py] [syworks/wireless-ids](https://github.com/syworks/wireless-ids) Ability to detect suspicious activity such as (WEP/WPA/WPS) attack by sniffing the air for wireless packets.
- [**174**星][17d] [HTML] [openvizsla/ov_ftdi](https://github.com/openvizsla/ov_ftdi) FT2232H-based USB sniffer
- [**165**星][5y] [Perl] [xme/hoover](https://github.com/xme/hoover) Wireless Probe Requests Sniffer
- [**152**星][18d] [Py] [shirosaidev/sharesniffer](https://github.com/shirosaidev/sharesniffer) 远程文件系统自动嗅探、挂载和爬取
- [**151**星][1y] [C] [caesar0301/http-sniffer](https://github.com/caesar0301/http-sniffer) A multi-threading tool to sniff TCP flow statistics and embedded HTTP headers from PCAP file. Each TCP flow carrying HTTP is exported to text file in json format.
- [**150**星][2y] [Py] [vduddu/malware](https://github.com/vduddu/malware) Rootkits | Backdoors | Sniffers | Virus | Ransomware | Steganography | Cryptography | Shellcodes | Webshells | Keylogger | Botnets | Worms | Other Network Tools
- [**137**星][7y] [C] [t57root/pwnginx](https://github.com/t57root/pwnginx) Pwn nginx - a nginx backdoor provides shell access, socks5 tunneling, http password sniffing.
- [**135**星][2y] [ObjC] [objective-see/sniffmk](https://github.com/objective-see/sniffmk) sniff mouse and keyboard events
- [**120**星][6m] [Rust] [kanishkarj/snoopy](https://github.com/kanishkarj/snoopy) A highly configurable multi-threaded packet sniffer and parser build in rust-lang.
- [**116**星][1y] [C] [nospaceships/raw-socket-sniffer](https://github.com/nospaceships/raw-socket-sniffer) Packet capture on Windows without a kernel driver
- [**104**星][1m] [JS] [wilddeer/sniffer](https://github.com/wilddeer/sniffer) browser/engine/os/device detection tool
- [**101**星][1y] [Py] [macr0phag3/sniffer](https://github.com/macr0phag3/sniffer) A Sniffer for Open-WLAN
- [**101**星][2m] [C] [onotelli/justniffer](https://github.com/onotelli/justniffer) Justniffer Just A Network TCP Packet Sniffer .Justniffer is a network protocol analyzer that captures network traffic and produces logs in a customized way, can emulate Apache web server log files, track response times and extract all "intercepted" files from the HTTP traffic
- [**99**星][8y] [Java] [gadgetfactory/openbench-logic-sniffer](https://github.com/gadgetfactory/openbench-logic-sniffer) OLS is a $50 32 channel Logic Analyzer
- [**99**星][9y] [C] [tecknicaltom/dsniff](https://github.com/tecknicaltom/dsniff) dsniff is a collection of tools for network auditing and penetration testing.
- [**98**星][8m] [Swift] [kofktu/sniffer](https://github.com/kofktu/sniffer) Networking activity logger for Swift
- [**95**星][2y] [HTML] [frizb/sourcecodesniffer](https://github.com/frizb/sourcecodesniffer) The Source Code Sniffer is a poor man’s static code analysis tool (SCA) that leverages regular expressions. Designed to highlight high risk functions (Injection, LFI/RFI, file uploads etc) across multiple languages (ASP, Java, CSharp, PHP, Perl, Python, JavaScript, HTML etc) in a highly configurable manner.
- [**90**星][26d] [Ruby] [shopify/browser_sniffer](https://github.com/shopify/browser_sniffer) Properly detect what browser you are dealing with
- [**87**星][t] [Py] [r00ts3c/ddos-rootsec](https://github.com/r00ts3c/ddos-rootsec) DDOS Archive by RootSec (Scanners, BotNets (Mirai and QBot Premium & Normal and more), Exploits, Methods, Sniffers)
- [**80**星][13d] [PHP] [automattic/vip-coding-standards](https://github.com/automattic/vip-coding-standards) PHP_CodeSniffer ruleset to enforce WordPress.com VIP and VIP Go coding standards
- [**79**星][1y] [C] [adafruit/adafruit_blesniffer_python](https://github.com/adafruit/adafruit_blesniffer_python) Python API for Adafruit's Bluefruit LE Sniffer
- [**79**星][3y] [bastilleresearch/keysniffer](https://github.com/bastilleresearch/keysniffer) KeySniffer device discovery tools and public advisories
- [**78**星][4y] [C] [kala13x/scap](https://github.com/kala13x/scap) Network Sniffer (Scan and Capture Incoming Packets)
- [**76**星][5y] [C++] [yveaux/nrf24_sniffer](https://github.com/yveaux/nrf24_sniffer) Sniffer for Nordic NRF24L01+ modules with MySensors support
- [**74**星][10m] [Verilog] [denandz/lpc_sniffer_tpm](https://github.com/denandz/lpc_sniffer_tpm) A low pin count sniffer for ICEStick - targeting TPM chips
- [**72**星][2y] [C++] [vecna/sniffjoke](https://github.com/vecna/sniffjoke) a client-only layer of protection from the wiretap/sniff/IDS analysis
- [**66**星][5y] [Py] [adamlaurie/hdmi-sniff](https://github.com/AdamLaurie/hdmi-sniff) sniff HDMI DDC (I2C) traffic
- [**66**星][8m] [Py] [nordicsemiconductor/nrf-sniffer-for-802.15.4](https://github.com/NordicSemiconductor/nRF-Sniffer-for-802.15.4) nRF-based 802.15.4 sniffer (firmware and software)
- [**64**星][4y] [Py] [halit/isip](https://github.com/halit/isip) Interactive sip toolkit for packet manipulations, sniffing, man in the middle attacks, fuzzing, simulating of dos attacks.
- [**64**星][7y] [C++] [hurley25/sniffer](https://github.com/hurley25/sniffer) 一个跨平台的网络数据嗅探&抓包程序，基于Qt 4.x 以及 libpcap 库（Linux下）和 Winpcap库（Windows 下）。
- [**64**星][3y] [Py] [scipag/btle-sniffer](https://github.com/scipag/btle-sniffer) Passively scan for Bluetooth Low Energy devices and attempt to fingerprint them
- [**60**星][6y] [Py] [offensivepython/sniffy](https://github.com/offensivepython/sniffy) A Simple network sniffer implemented on Python 3
- [**59**星][2m] [PHP] [sirbrillig/phpcs-variable-analysis](https://github.com/sirbrillig/phpcs-variable-analysis) Find undefined and unused variables with the PHP Codesniffer static analysis tool.
- [**57**星][4y] [Go] [zond/qisniff](https://github.com/zond/qisniff) 
- [**56**星][4y] [Py] [geovation/wifispy](https://github.com/geovation/wifispy) Sniff Wifi traffic, log device addresses.
- [**52**星][10m] [Java] [ruedigergad/clj-net-pcap](https://github.com/ruedigergad/clj-net-pcap) A wrapper/facade/whatever to enable/ease the use of jNetPcap (a libpcap based packet sniffing lib) in Clojure
- [**51**星][14d] [Java] [p1sec/sigfw](https://github.com/p1sec/sigfw) Open Source Signaling Firewall for SS7, Diameter filtering, antispoof and antisniff
- [**51**星][5m] [HTML] [whatwg/mimesniff](https://github.com/whatwg/mimesniff) MIME Sniffing Standard
- [**51**星][1y] [Py] [zhovner/airport-sniffer](https://github.com/zhovner/airport-sniffer) Very simple Wi-Fi sniffer and dumps parser for built-in macbook AirPort Extreme card. Only native MacOS tools used.
- [**50**星][1y] [Go] [zredshift/mimemagic](https://github.com/zredshift/mimemagic) Powerful and versatile MIME sniffing package using pre-compiled glob patterns, magic number signatures, XML document namespaces, and tree magic for mounted volumes, generated from the XDG shared-mime-info database.
- [**49**星][7y] [C++] [1184893257/simplesniffer](https://github.com/1184893257/simplesniffer) 基于 WinPcap 的网络抓包软件，使用 MFC 做界面
- [**49**星][22d] [JS] [whichbrowser/parser-javascript](https://github.com/whichbrowser/parser-javascript) Browser sniffing gone too far — A useragent parser library for JavaScript
- [**48**星][2y] [C++] [anubisss/szimatszatyor](https://github.com/anubisss/szimatszatyor) World of Warcraft (WoW): SzimatSzatyor is an injector sniffer written in C++
- [**48**星][5m] [C] [chentingz/snifferui](https://github.com/chentingz/snifferui) 基于MFC和WinPcap库开发的网络抓包和协议分析软件
- [**48**星][3y] [C] [rodrigoalvesvieira/soundkeylogger](https://github.com/rodrigoalvesvieira/soundkeylogger) An experimental project to demonstrate how a user keyboard input may be sniffed through the pattern analysis of the sounds emitted by the keystrokes.
- [**47**星][2y] [Shell] [nyxgeek/dumpsniffer](https://github.com/nyxgeek/dumpsniffer) tools for analyzing strings from password lists
- [**45**星][9m] [C++] [ncatlin/exilesniffer](https://github.com/ncatlin/exilesniffer) A protocol decryption and dissection tool for the game 'Path of Exile'
- [**44**星][1y] [C] [petabi/sniffles](https://github.com/petabi/sniffles) Packet Capture Generator for IDS and Regular Expression Evaluation
- [**44**星][6y] [IDL] [riverloopsec/apimote](https://github.com/riverloopsec/apimote) ApiMote IEEE 802.15.4/ZigBee Sniffing Hardware
- [**42**星][4y] [Py] [xme/tweetsniff](https://github.com/xme/tweetsniff) Grab a Twitter user timeline for further processing (storing to Elasticsearch, highligthing, etc)
- [**41**星][3y] [Py] [tengzhangchao/websniff](https://github.com/tengzhangchao/websniff) 局域网http流量嗅探，并获取登陆的账号密码
- [**41**星][25d] [PHP] [xchwarze/cain](https://github.com/xchwarze/cain) Password recovery tool for Microsoft Operating Systems. It allows easy recovery of various kind of passwords by sniffing the network, cracking encrypted passwords using Dictionary, Brute-Force and Cryptanalysis attacks, recording VoIP conversations, decoding scrambled passwords, recovering wireless network keys, revealing password boxes, uncover…
- [**40**星][1y] [Shell] [adityashrm21/raspberrypi-packet-sniffer](https://github.com/adityashrm21/raspberrypi-packet-sniffer) An HTTP and HTTPS sniffing tool created using a Raspberry Pi
- [**40**星][5y] [Py] [flankerhqd/wifimonster](https://github.com/flankerhqd/wifimonster) Wifi sniffing and hijacking tool
- [**38**星][1y] [Py] [activecm/passer](https://github.com/activecm/passer) Passive service locator, a python sniffer that identifies servers, clients, names and much more
- [**38**星][7y] [Py] [mainframed/mfsniffer](https://github.com/mainframed/mfsniffer) Mainframe TN3270 unencrypted TSO session user ID and password sniffer
- [**34**星][2y] [C++] [chiehmin/sheepwall](https://github.com/chiehmin/sheepwall) Sniff plaintext account/password/cookie on router
- [**34**星][7y] [JS] [nv/setinterval-sniffer](https://github.com/nv/setinterval-sniffer) Keep tabs on your uncleared intervals. Hunt down lags and memory leaks.
- [**34**星][1y] [Py] [oros42/dns_sniffer](https://github.com/oros42/dns_sniffer) A python DNS sniffer
- [**31**星][2y] [PHP] [bmitch/codor](https://github.com/bmitch/codor) Custom PHPCS sniffs to find Code Smells
- [**31**星][2y] [Go] [paultag/sniff](https://github.com/paultag/sniff) Dispatch TLS Connections based on SNI
- [**31**星][2y] [Go] [pyinx/zk-sniffer](https://github.com/pyinx/zk-sniffer) sniffer and parse zookeeper packet
- [**30**星][24d] [PHP] [php-fig-rectified/psr2r-sniffer](https://github.com/php-fig-rectified/psr2r-sniffer) A PSR-2-R code sniffer and code-style auto-correction-tool - including many useful additions
- [**29**星][6y] [Py] [catalyst256/sniffmypackets](https://github.com/catalyst256/sniffmypackets) Canari local transforms pcap file analysis
- [**25**星][6y] [cbrunsch/wmbus-sniffer-muc](https://github.com/cbrunsch/wmbus-sniffer-muc) Source code of the demonstration programs showed in the Black Hat '13 presentation "Energy fraud and orchestrated blackouts: Issues with wireless metering protocols (WM-BUS)" by Cyrill Brunschwiler
- [**24**星][3m] [Py] [jplesperance/redis-sniffer](https://github.com/jplesperance/redis-sniffer) A Redis event sniffer and logging utility.
- [**23**星][7m] [Py] [antisomnus/sniffer](https://github.com/antisomnus/sniffer) Simple sniffer using scapy and PyQt5 on Windows 10
    - 重复区段: [工具->Scapy](#01f99d208e245eb44f15f720043b50d4) |
- [**22**星][2y] [C] [jerome-ps/jn516xsniffer](https://github.com/jerome-ps/jn516xsniffer) Transform a Xiaomi Zigbee gadget into a Zigbee sniffer.
- [**22**星][9y] [C] [zapotek/cdpsnarf](https://github.com/zapotek/cdpsnarf) CDPSnarf is a network sniffer exclusively written to extract information from CDP (Cisco Discovery Protocol) packets.
- [**21**星][1y] [PHP] [codeclimate/codeclimate-phpcodesniffer](https://github.com/codeclimate/codeclimate-phpcodesniffer) Code Climate Engine for PHP Code Sniffer
- [**20**星][3y] [C] [a232319779/phantom-3-standard](https://github.com/a232319779/phantom-3-standard) Used hackrf one to sniffer nrf24l0 and so on wireless packet.Application in PHANTOM 3 STANDARD RC signal sniffer.
- [**19**星][2y] [Verilog] [lynxis/lpc_sniffer](https://github.com/lynxis/lpc_sniffer) a low pin count sniffer for icestick
- [**19**星][2y] [C++] [namreeb/hacksniff](https://github.com/namreeb/hacksniff) A tool to monitor how a target process modifies other processes
- [**19**星][3y] [ObjC] [ura14h/blesniffer](https://github.com/ura14h/blesniffer) A Bluetooth LE sniffer for CC2540 USB dongle and Mac.
- [**19**星][7y] [C++] [6e726d/native-wifi-api-beacon-sniffer](https://github.com/6e726d/native-wifi-api-beacon-sniffer) Tool that dumps beacon frames to a pcap file. Works on Windows Vista or Later with any Wireless Card.
- [**18**星][6y] [Java] [taufderl/whatsapp-sniffer-android-poc](https://github.com/taufderl/whatsapp-sniffer-android-poc) proof of concept app to show how to upload and decrypt WhatsApp backup database
- [**18**星][7y] [Py] [eldraco/darm](https://github.com/eldraco/darm) darm - intelligent network sniffer for the masses darm is an attempt to create a very easy to use app that will sniff and report information about the activities happening on a live network. The main goal is to educate the public so that it becomes aware of the security of their communications. darm is being developed by leandrinux as a project …
- [**18**星][5y] [C++] [halfdanj/ofxsniffer](https://github.com/halfdanj/ofxsniffer) Network packet sniffing and crafting wrapper based on the libtins library.
- [**17**星][3y] [JS] [bugscanteam/bugrequest](https://github.com/bugscanteam/bugrequest) Sniffer vulnerabilities in http request (chrome extension)
- [**15**星][6y] [Py] [mbains/linux-802.15.4-sniffer](https://github.com/mbains/linux-802.15.4-sniffer) Linux Based 802.15.4/Zigbee Sniffer
- [**15**星][2y] [C] [ps2/rtlmm](https://github.com/ps2/rtlmm) Software to sniff minimed RF packets using a RTLSDR dongle
- [**14**星][2y] [C] [julioreynaga/sniffer](https://github.com/julioreynaga/sniffer) Packet Trace Parser for TCP, SMTP Emails, and HTTP Cookies
- [**13**星][2y] [Py] [lyyyuna/dht_sniffer](https://github.com/lyyyuna/dht_sniffer) DHT 公网嗅探器
- [**13**星][3y] [Py] [vshymanskyy/blesniffer_python](https://github.com/vshymanskyy/blesniffer_python) Software for nRF BLE Sniffer
- [**12**星][4y] [PS] [harmj0y/netripper](https://github.com/harmj0y/netripper) NetRipper - Smart traffic sniffing for penetration testers
- [**12**星][2y] [C] [majbthrd/cansniffer](https://github.com/majbthrd/cansniffer) CANbus sniffer using STM32F042 microcontroller
- [**12**星][5y] [Py] [sneakersinc/sniffmypacketsv2](https://github.com/sneakersinc/sniffmypacketsv2) Next major release of sniffMyPackets - Now with added packet loving
- [**12**星][3y] [C++] [coac/foybot](https://github.com/coac/foybot) MMO Packet sniffer experiment
- [**11**星][3y] [C] [mjdubell/sudo_sniff](https://github.com/mjdubell/sudo_sniff) Steal user's password when running sudo for post-exploitation purposes
- [**10**星][2m] [Py] [gisdev01/security-ssid-abi](https://github.com/gisdev01/security-ssid-abi) Sniff wifi probes from nearby devices (passive monitoring only) and logs to an InfluxDB time-series database
- [**10**星][1m] [PHP] [hostnet/css-sniffer](https://github.com/hostnet/css-sniffer) Static code analyses for CSS and LESS.
- [**10**星][4y] [C] [wifimon/wifimon](https://github.com/wifimon/wifimon) Wi-fi 802.11 Beacon Frame sniffer
- [**9**星][1y] [Py] [haopeiwen/sniffer](https://github.com/haopeiwen/sniffer) IS301 Computer Communication and Network Project
- [**8**星][1y] [Perl] [0xcesium/hackrf-gnu-radio](https://github.com/0xcesium/hackrf-gnu-radio) HackRF modules to sniff GSM 900MHz bands.
- [**8**星][6m] [Py] [amlight/ofp_sniffer](https://github.com/amlight/ofp_sniffer) An OpenFlow sniffer to help network troubleshooting in production networks.
- [**8**星][2y] [C++] [mgostih/snifferih](https://github.com/mgostih/snifferih) DLL Hooking Packet Sniffer
- [**8**星][7m] [JS] [piecioshka/xhr-sniffer](https://github.com/piecioshka/xhr-sniffer) 
- [**8**星][9m] [Py] [ajackal/cherrywasp](https://github.com/ajackal/cherrywasp) An 802.11 probe request and beacon sniffer.
- [**7**星][8m] [C#] [artman41/fenderstratocastorsniffer](https://github.com/artman41/fenderstratocastorsniffer) 
- [**7**星][2m] [Py] [programmingathlete/brutesniffing_fisher](https://github.com/programmingathlete/brutesniffing_fisher) hacking tool
- [**6**星][2y] [Go] [amyangxyz/dnssniffer](https://github.com/amyangxyz/dnssniffer) DNSQuery Sniffer in Golang
- [**6**星][2y] [Py] [crcarlo/arp-spoofing-python](https://github.com/crcarlo/arp-spoofing-python) A script for sniffing internet traffic between a machine and the gateway in your local network.
- [**6**星][3y] [Go] [jheise/dns-probe](https://github.com/jheise/dns-probe) Sniff for dns traffic and create a zero mq stream for it
- [**5**星][2y] [Py] [daymorelah/packetanalyzerandsniffer](https://github.com/daymorelah/packetanalyzerandsniffer) A simple python module that implements a packet sniffer and analyser. It sniffs and analyses TCP, UDP, IPV4 and IPV6 traffic.
- [**5**星][5y] [Ruby] [dotboris/hidden-hippo](https://github.com/dotboris/hidden-hippo) A tool that identifies the people around you by sniffing network traffic and mining social networks.
- [**5**星][3y] [roboremo/nrf24-demodulator](https://github.com/roboremo/nrf24-demodulator) Sniff NRF24L01 (and clones) packets and veiw bit-level structure using GNU Radio
- [**5**星][2y] [Lua] [spacewander/lua-resty-mime-sniff](https://github.com/spacewander/lua-resty-mime-sniff) Sniff the real MIME type of given data in your OpenResty app
- [**5**星][3y] [C++] [andreabont/project-riddle](https://github.com/andreabont/project-riddle) Modular Network Packet Sniffer
- [**4**星][7y] [Shell] [dc414/fakeap_pwnage](https://github.com/dc414/fakeap_pwnage) A fakeAP to sniff traffic or get CC numbers.
- [**4**星][6y] [Shell] [logic-gate/penbang](https://github.com/logic-gate/penbang) Penbang is a collection of tools aimed at the openbox environment. It includes Network Exploits, Vulnerability Assessment/Exploits, Network Analysis, Social Engineering tools, I.G.C, dsniff suite, and irpas. As well as a simple way of launching them.
- [**4**星][3y] [Py] [mellow-hype/keysniffer-poc](https://github.com/mellow-hype/keysniffer-poc) Simple PoC Linux keysniffer showing impact of a lack of GUI-isolation in X display server.
- [**4**星][4y] [Visual Basic .NET] [pyblendnet-js/realtermbuspiratesniff](https://github.com/pyblendnet-js/realtermbuspiratesniff) Bus Pirate SPI sniffer using RealTerm for highspeed transfer
- [**4**星][5y] [Ruby] [sneakersinc/sniffmypacketsv2-web](https://github.com/sneakersinc/sniffmypacketsv2-web) Web framework for sniffmypackets v2
- [**4**星][2y] [Py] [wangjksjtu/jksniffer](https://github.com/wangjksjtu/jksniffer) An implementation of Sniffer Tool using Python
- [**4**星][29d] [JS] [sipcapture/hepjack.js](https://github.com/sipcapture/hepjack.js) Elegantly Sniff Forward-Secrecy TLS/SIP to HEP at the source using Frida
- [**4**星][2m] [Py] [tastypeanut/carmela](https://github.com/tastypeanut/carmela) Makes network sniffing easy for everyone. Still a work in progress.
- [**3**星][4y] [C++] [aschen/cameleon-sniffer](https://github.com/aschen/cameleon-sniffer) A modular network sniffer daemon written in C++
- [**3**星][2y] [Py] [orf53975/malware](https://github.com/orf53975/malware) Rootkits | Backdoors | Sniffers | Virus | Ransomware | Steganography | Cryptography | Shellcodes | Webshells | Keylogger | Botnets | Worms | Other Network Tools
- [**3**星][5y] [C++] [simonberson/chromeurlsniffer](https://github.com/simonberson/chromeurlsniffer) Hook to Chrome Browser URL and show the current URL on simple textbox
- [**3**星][4y] [Py] [wirelesshack/desniffer](https://github.com/wirelesshack/desniffer) 802.11 wireless sniffer
- [**3**星][4y] [C] [bwoolf1122/tcp-seqnum](https://github.com/bwoolf1122/tcp-seqnum) Means to sniff 802.11 traffic and obtain TCP session info using netfiter_queue. Use that data to construct a packet in scappy.
- [**3**星][7y] [Py] [0x0d/wallofshame](https://github.com/0x0d/wallofshame) Multi protocol sniffer, created for ChaosConstruction conference HackSpace
- [**2**星][10m] [Shell] [b3n-j4m1n/flood-kick-sniff](https://github.com/b3n-j4m1n/flood-kick-sniff) Known Beacons attack tool
- [**2**星][1y] [Go] [progtramder/webproxy](https://github.com/progtramder/webproxy) A fiddler-like webproxy, support sniffing http/https content by implementing 'Sniffer' interface
    - 重复区段: [工具->fiddler](#31d28e8b2cf6c06411cd5d178dbd3e77) |
- [**2**星][5y] [Py] [depthdeluxe/dot11sniffer](https://github.com/depthdeluxe/dot11sniffer) Sniffs 802.11 traffic and counts the number of active wireless devices in an area
- [**2**星][2y] [C] [samclarke2012/ssidentity](https://github.com/samclarke2012/ssidentity) Passive sniffing of 802.11 probe requests, stored in a central database.
- [**2**星][9y] [de-ibh/mupe](https://github.com/de-ibh/mupe) MUltiPath Estimator - Create statistical analysis of 802.11 Radiotap sniffs
- [**1**星][3y] [Py] [wouterbudding/scapygelftograylog2](https://github.com/wouterbudding/scapygelftograylog2) sniff some 802.11 packages and send the date and MAC with GELF UDP to Graylog2
- [**1**星][4m] [Perl] [briandfoy/httpsniffer](https://github.com/briandfoy/httpsniffer) 
- [**1**星][4y] [Py] [dcrisan/wifi-802.11-demo-sniffer](https://github.com/dcrisan/wifi-802.11-demo-sniffer) This 802.11 sniffer written in Python provides a useful tool to raise awareness at the amount of data phones release for anyone to read.
- [**1**星][5y] [C] [gauravpatwardhan/wireless-sniffer](https://github.com/gauravpatwardhan/wireless-sniffer) A 802.11 wireless sniffer tool
- [**1**星][6y] [C] [saintkepha/airtraf](https://github.com/saintkepha/airtraf) wireless 802.11 network sniffer and analyzer
- [**0**星][11y] [C] [jackiexie168/como](https://github.com/jackiexie168/como) CoMo is a passive monitoring system that supports arbitrary real time traffic queries. Data streams may have different formats (e.g., packet/flow sequences, etc.) and originate from different platforms (e.g, packet sniffers, routers, wireless APs, ...).
- [**0**星][7y] [Py] [dappiu/rifsniff](https://github.com/dappiu/rifsniff) RIfSniff is a Remote Interface Sniffer


### <a id="d7485f829bd85cd784ff582cbddc8624"></a>捕获&&Capture


- [**1429**星][3m] [Go] [google/stenographer](https://github.com/google/stenographer) 数据包捕获解决方案，将所有数据包快速后台处理到磁盘，然后提供对这些数据包子集的简单、快速访问
- [**909**星][4d] [C++] [seladb/pcapplusplus](https://github.com/seladb/pcapplusplus) 多平台C ++库，用于捕获、解析和处理网络数据包。为最受欢迎的数据包处理引擎（例如libpcap，WinPcap，DPDK和PF_RING）提供了C ++包装器。高效、强大且易于使用。
- [**883**星][1m] [C] [cisco/joy](https://github.com/cisco/joy) 捕获和分析网络流数据和intraflow数据，用于网络研究、取证和安全监视
- [**854**星][t] [C] [zerbea/hcxtools](https://github.com/zerbea/hcxtools) 捕获无线局域网流量，并将其转换为hashcat格式和John Ripper格式
- [**680**星][t] [C] [zerbea/hcxdumptool](https://github.com/zerbea/hcxdumptool) 捕获来自无线设备的数据包
- [**456**星][3y] [C] [haka-security/haka](https://github.com/haka-security/haka) 捕获TCP / IP数据包，并根据Lua策略文件对其进行过滤
- [**423**星][3m] [C] [desowin/usbpcap](https://github.com/desowin/usbpcap) USB数据包捕获，用于Windows
- [**214**星][3m] [C] [dns-oarc/dnscap](https://github.com/dns-oarc/dnscap) 专为DNS流量设计的网络捕获工具
- [**141**星][2y] [Py] [secureworks/flowsynth](https://github.com/secureworks/flowsynth) 快速对网络流量进行建模，可用于生成基于文本的数据包的十六进制转储，和libpcap格式的数据包捕获
- [**110**星][3m] [C] [sipcapture/captagent](https://github.com/sipcapture/captagent) 用于RTC的HEP数据包捕获和镜像框架，功能强大、灵活、完全模块化。可用于任何类型的IP协议和封装方法
- [**46**星][3y] [C] [rpcapd-linux/rpcapd-linux](https://github.com/rpcapd-linux/rpcapd-linux) 为Windows版本的Wireshark提供远程流量捕获的守护程序
    - 重复区段: [工具->Wireshark](#6fa0e0d1f898fba299b2566a33602841) |
- [**32**星][6y] [C] [nbareil/net2pcap](https://github.com/nbareil/net2pcap) 类似于tcpdump的数据包捕获工具，只依赖libc
- [**29**星][2y] [Py] [nsacyber/serial2pcap](https://github.com/nsacyber/serial2pcap) 将通常从工业控制系统设备收集的串行IP数据转换为更常用的数据包捕获（PCAP）格式
- [**13**星][6m] [Java] [jxnet/jxnet](https://github.com/jxnet/jxnet) Jxnet is a Java library for capturing and sending custom network packet buffers with no copies. Jxnet wraps a native packet capture library (libpcap/winpcap/npcap) via JNI (Java Native Interface).


### <a id="471c124b012dbde8ea3288f35667efc8"></a>流量检测


- [**3341**星][4d] [Py] [stamparm/maltrail](https://github.com/stamparm/maltrail) 恶意网络流量检测系统




***


## <a id="384f5e1bef62f815c6745062f2975ba7"></a>文章




# <a id="c63cbfa77e689e485fc2d8bc5051f229"></a>Android


***


## <a id="863839860fab4b8601905205cac9b54f"></a>工具


- [**27960**星][9d] [Kotlin] [shadowsocks/shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android) A shadowsocks client for Android
- [**4966**星][12d] [TS] [jigsaw-code/outline-client](https://github.com/jigsaw-code/outline-client) Outline clients, developed by Jigsaw. The Outline clients use the popular Shadowsocks protocol, and lean on the Cordova and Electron frameworks to support Windows, Android / ChromeOS, Linux, iOS and macOS.
    - 重复区段: [iOS->工具](#692d86299dedab073fbb6144a5b2bd64) |
- [**3145**星][2y] [shadowsocksr-backup/shadowsocksr-android](https://github.com/shadowsocksr-backup/shadowsocksr-android) A ShadowsocksR client for Android
- [**1338**星][1y] [C] [madeye/proxydroid](https://github.com/madeye/proxydroid) Global Proxy for Android
- [**997**星][12m] [Java] [huolizhuminh/networkpacketcapture](https://github.com/huolizhuminh/networkpacketcapture) It is used to capture network packet via Android VPN.
- [**534**星][2y] [Java] [dawei101/shadowsocks-android-java](https://github.com/dawei101/shadowsocks-android-java) Shadowsocks android client, pure java version
- [**527**星][4y] [C] [neilalexander/sigmavpn](https://github.com/neilalexander/sigmavpn) Light-weight, secure and modular VPN solution which makes use of NaCl encryption (also available for Android using jnacl in "sigmavpn-android")
- [**450**星][2m] [Kotlin] [hmbsbige/shadowsocksr-android](https://github.com/hmbsbige/shadowsocksr-android) A ShadowsocksR client for Android, written in Kotlin.
- [**368**星][3y] [Java] [ssun125/lanmitm](https://github.com/ssun125/lanmitm) Android中间人攻击测试工具
- [**219**星][2y] [itrump/shadowsocksrss](https://github.com/itrump/shadowsocksrss) shadowsocksR backup, windows / android / mac downloads, source code backup
- [**201**星][4m] [Kotlin] [shadowsocks/v2ray-plugin-android](https://github.com/shadowsocks/v2ray-plugin-android) A SIP003 V2ray plugin on Android
- [**95**星][2y] [guardianproject/tor-browser](https://github.com/guardianproject/tor-browser) UPDATE: Orfox is being replaced by Tor Browser for Android. All future work and comments will be handled by Tor Project.
    - 重复区段: [匿名网络->工具->Tor](#e99ba5f3de02f68412b13ca718a0afb6) |
- [**88**星][1y] [Java] [frpccluster/frpc-android](https://github.com/frpccluster/frpc-android) Android,安卓版frpc，一个快速反向代理，可帮助您将NAT或防火墙后面的本地服务器暴露给Internet。
- [**86**星][1y] [Java] [vpnht/android](https://github.com/vpnht/android) VPN.ht Android Application. Based on ics-openvpn.
- [**74**星][1y] [Shell] [thelinuxchoice/keydroid](https://github.com/thelinuxchoice/keydroid) Android Keylogger + Reverse Shell
- [**34**星][3y] [C] [uwnetworkslab/cordova-plugin-tun2socks](https://github.com/uwnetworkslab/cordova-plugin-tun2socks) Cordova plugin to enable a system-wide VPN for Android devices.
- [**33**星][1y] [Shell] [cryptolok/ghostinthechaos](https://github.com/cryptolok/ghostinthechaos) Chaotic Crypto Stealth VPN for Anonymity and Untraceable Hacking Attacks with Linux and Android
- [**32**星][5y] [Ruby] [jduck/addjsif](https://github.com/jduck/addjsif) Metasploit Exploit Module for the Android addJavascriptInterface Issue (MITM)
- [**28**星][2y] [C] [shadowsocksr-live/ssrdroid](https://github.com/shadowsocksr-live/ssrdroid) ShadowsocksR (SSR) for Android
- [**23**星][1y] [Java] [shivam141296/android-firewall](https://github.com/shivam141296/android-firewall) Basic netguard app from playstore ,reduced to its minimum level for vpn and firewall logic
- [**22**星][4y] [C] [shadowsocks/openssl-android](https://github.com/shadowsocks/openssl-android) A fork of OpenSSL for shadowsocks-android


# <a id="70857140d346b443fe3b7ea3046f702a"></a>iOS


***


## <a id="692d86299dedab073fbb6144a5b2bd64"></a>工具


- [**7958**星][4y] [ObjC] [shadowsocks/shadowsocks-ios](https://github.com/shadowsocks/shadowsocks-ios) Removed according to regulations.
- [**6645**星][8d] [Py] [h2y/shadowrocket-adblock-rules](https://github.com/h2y/shadowrocket-adblock-rules) 提供多款 Shadowrocket 规则，带广告过滤功能。用于 iOS 未越狱设备选择性地自动翻墙。
- [**4966**星][12d] [TS] [jigsaw-code/outline-client](https://github.com/jigsaw-code/outline-client) Outline clients, developed by Jigsaw. The Outline clients use the popular Shadowsocks protocol, and lean on the Cordova and Electron frameworks to support Windows, Android / ChromeOS, Linux, iOS and macOS.
    - 重复区段: [Android->工具](#863839860fab4b8601905205cac9b54f) |
- [**1701**星][1y] [Swift] [haxpor/potatso](https://github.com/haxpor/potatso) Potatso is an iOS client that implements Shadowsocks proxy with the leverage of NetworkExtension framework. ***This project is unmaintained, try taking a look at this fork
- [**1211**星][t] [ObjC] [onionbrowser/onionbrowser](https://github.com/onionbrowser/onionbrowser) An open-source, privacy-enhancing web browser for iOS, utilizing the Tor anonymity network
    - 重复区段: [匿名网络->工具->Tor](#e99ba5f3de02f68412b13ca718a0afb6) |
- [**857**星][3y] [Py] [hubert3/isniff-gps](https://github.com/hubert3/isniff-gps) Passive sniffing tool for capturing and visualising WiFi location data disclosed by iOS devices
- [**407**星][3y] [C] [robertyim/shadowsocksx](https://github.com/RobertYim/ShadowsocksX) Fork of shadowsocks-iOS
- [**380**星][5y] [Py] [mfrister/pushproxy](https://github.com/mfrister/pushproxy) A man-in-the-middle proxy for iOS and OS X device push connections
- [**133**星][3y] [Swift] [kidneyband/potatso-ios](https://github.com/kidneyband/potatso-ios) Potatso is an iOS client that implements Shadowsocks proxy with the leverage of NetworkExtension framework in iOS 9.
- [**121**星][2y] [Swift] [lxdcn/nepackettunnelvpndemo](https://github.com/lxdcn/nepackettunnelvpndemo) iOS VPN client implementation demo based on iOS9 NetworkExtension NETunnelProvider APIs
- [**107**星][12m] [Swift] [lettleprince/qladder](https://github.com/lettleprince/qladder) QLadder is a project for iOS client. It uses shadowsocks as server-side.
- [**35**星][2y] [unbinilium/surge](https://github.com/unbinilium/surge) Shadowsocks Encrypt Support Module for Surge APP, iOS & MacOS Configuration
- [**25**星][1y] [ObjC] [skifary/c4msis](https://github.com/skifary/c4msis) ios shadowsocks app based on NEKit


# <a id="53da0cc607b98c444ec0e50a0b77f754"></a>网络攻击


***


## <a id="295e14c39bf33cd5136be8ced9383746"></a>工具


### <a id="07f06751f1de7ddd1f6a95323f0191c8"></a>PortKnocking


- [**515**星][14d] [Perl] [mrash/fwknop](https://github.com/mrash/fwknop) Single Packet Authorization > Port Knocking
- [**371**星][7y] [Py] [moxie0/knockknock](https://github.com/moxie0/knockknock) 简易、安全且隐蔽的Port Knocking工具，不使用libpcap，也不绑定到socket接口


### <a id="f855508acfc870b1f0d90ff316f1dd75"></a>伪造&&Spoof


- [**2174**星][1y] [JS] [iam4x/pokemongo-webspoof](https://github.com/iam4x/pokemongo-webspoof) 在PokémonGo伪造iOS设备GPS位置
- [**256**星][3y] [C] [w-shackleton/android-netspoof](https://github.com/w-shackleton/android-netspoof) Network Spoofer
- [**168**星][6d] [JS] [sereneblue/chameleon](https://github.com/sereneblue/chameleon) A WebExtension port of Random Agent Spoofer
- [**121**星][12m] [Py] [byt3bl33d3r/arpspoof](https://github.com/byt3bl33d3r/arpspoof) Python clone of arpspoof that can poison hosts via arp-requests as well as arp-replies
- [**95**星][9m] [C++] [hlldz/apc-ppid](https://github.com/hlldz/apc-ppid) Adds a user-mode asynchronous procedure call (APC) object to the APC queue of the specified thread and spoof the Parent Process.
- [**55**星][5y] [PHP] [troyhunt/pineapplesurprise](https://github.com/troyhunt/pineapplesurprise) Pineapple Surprise! is a PHP implementation for the Wi-Fi Pineapple or "Jasager". Used in conjunction with dnsspoof it will serve a "surprise" to any clients connected to the device when they make an HTTP request.
- [**52**星][9m] [Py] [fireeye/adfspoof](https://github.com/fireeye/adfspoof)  forge AD FS security tokens
- [**46**星][2m] [C++] [125k/esp8266_wifi_captive_portal](https://github.com/125k/esp8266_wifi_captive_portal) WiFi captive portal for NodeMCU (ESP8266 Module) with DNS spoofing. It phishes the WiFi password.
- [**23**星][3m] [Visual Basic .NET] [henriksb/extensionspoofer](https://github.com/henriksb/extensionspoofer) Spoof file icons and extensions in Windows
- [**21**星][9m] [Shell] [thelinuxchoice/lizard](https://github.com/thelinuxchoice/lizard) Extension spoofer and reveser shell generator
- [**20**星][1y] [C] [nofvcks/aimkit-pasted-driver](https://github.com/nofvcks/aimkit-pasted-driver) The BlackBone + Chinese spoofer paste that GreenTea denied. AimKit is a scam. GreenTea is a fraud. Don't waste your money.
- [**19**星][3y] [Py] [wjdigby/apd_launchpad](https://github.com/wjdigby/apd_launchpad) Script for generating hostapd-wpe configuration files and spoofed certificates
- [**18**星][2y] [Py] [zxsecurity/nmeadesync](https://github.com/zxsecurity/nmeadesync) A tool which allows an attacker to change the time on a GPS-enabled NTP server by using spoofed NEMA sentences
- [**17**星][9y] [C] [maurotfilho/dns-spoof](https://github.com/maurotfilho/dns-spoof) DNS Spoof
- [**17**星][11m] [JS] [tobinshields/zaqar_emailspoofer](https://github.com/tobinshields/zaqar_emailspoofer) A powerful PHP email spoofer with a polished UI, rich text editor, and multiple sending options.
- [**17**星][3y] [Py] [blechschmidt/fakeroute](https://github.com/blechschmidt/fakeroute) Simple traceroute fake hop generator through IP spoofing
- [**16**星][2y] [C#] [rushyo/vindicatetool](https://github.com/rushyo/vindicatetool) LLMNR/NBNS/mDNS Spoofing Detection Toolkit
- [**15**星][2y] [Swift] [hungtruong/deadringer](https://github.com/hungtruong/deadringer) A proof of concept iPhone X lock screen spoof
- [**15**星][6y] [Java] [mcourteaux/spooferbt](https://github.com/mcourteaux/spooferbt) Relay torrent tracker communication via TCP to bypass a blocked UDP network.
- [**14**星][3y] [C] [coolervoid/hyde](https://github.com/coolervoid/hyde) just another tool in C to test DoS spoofing - beta
- [**14**星][2y] [Py] [vtr0n/fakeap](https://github.com/vtr0n/fakeap) Fake access point using dns spoof and ssl stripping
- [**13**星][6y] [Py] [zackiles/rspoof](https://github.com/zackiles/rspoof) Wifi Automated Fake HotSpot Hijacking with aicrack-ng, airbase, ssl-strip, and dns spoof in Python.
- [**12**星][2y] [Go] [virus-v/arpzebra](https://github.com/virus-v/arpzebra) ARP+DNS欺骗工具，网络安全第三次实验，课堂演示用，严禁非法用途。ARPSpoof，wifi hijack，dns spoof
- [**12**星][2y] [Py] [imadhsissou/python-arp-spoofer](https://github.com/imadhsissou/python-arp-spoofer) A friendly command-line spoofing tool written in python using scapy and netifaces.
    - 重复区段: [工具->Scapy](#01f99d208e245eb44f15f720043b50d4) |
- [**12**星][3y] [Go] [sabey/spoofgo](https://github.com/sabey/spoofgo) An Application for Spoofing Movement written in Golang
- [**9**星][2y] [Py] [balaganeshgbhackers/emailspoofing](https://github.com/balaganeshgbhackers/emailspoofing) 
- [**9**星][4y] [Perl] [davi200180/ddos-scripts](https://github.com/davi200180/ddos-scripts) Diversi Script installabili e utilizzabili su Server Linux (Spoof e non) per poter fare attacchi DDoS
- [**9**星][2y] [Py] [porthunter/smoof](https://github.com/porthunter/smoof) SMS Spoofer for Social Engineering/Pentest Engagements
- [**9**星][5y] [PHP] [xtr4nge/module_dnsspoof](https://github.com/xtr4nge/module_dnsspoof) FruityWifi dnsspoof module
- [**9**星][6y] [sin5678/zxarps](https://github.com/sin5678/zxarps) arp spoof tool by lzx
- [**8**星][5y] [Py] [ickerwx/arpspoof](https://github.com/ickerwx/arpspoof) ARP poisoning tool written in python with command line interface to add and remove targets on the fly
- [**8**星][4y] [Shell] [jgamblin/mana-common](https://github.com/jgamblin/mana-common) Using Mana to Spoof Common SSIDs
- [**6**星][10m] [Py] [avantasia/inventedattack](https://github.com/avantasia/inventedattack) A POC attack combining IP SPoofing, SYN Flood and IP Fragmentation
- [**6**星][9m] [C++] [rgerganov/spoof_temp](https://github.com/rgerganov/spoof_temp) Spoof temperature sensor with HackRF
- [**6**星][3y] [Py] [securitymouse/moops-public](https://github.com/securitymouse/moops-public) My Object Oriented Packet Spoofer
- [**6**星][13d] [Go] [irai/arp](https://github.com/irai/arp) A go package to monitor ARP changes and notify when mac is online or offline. Also allow forced IP address change (IP spoofing).
- [**4**星][3y] [HTML] [649/cve-2017-5415](https://github.com/649/cve-2017-5415) Addressbar spoofing through blob URL (Firefox browser). An attack can use a blob URL and script to spoof an arbitrary addressbar URL prefaced by blob: as the protocol, leading to user confusion and further spoofing attacks.
- [**4**星][3y] [SourcePawn] [lordzy/safedialogs](https://github.com/lordzy/safedialogs) safeDialogs prevents the server from receiving fake or spoofed dialog responses. This includes faking dialog ID, listitem or even the inputtext in cases of lists. Faking listitem or inputtext can lead to many risks of user breaking into server security depending on how they're used. This include ensures that everything's safe and also contains a…
- [**3**星][5m] [Py] [tg12/slow_the_bots](https://github.com/tg12/slow_the_bots) Slow the bot's by spoofing what they are looking for!
- [**2**星][3y] [Java] [simonfrey/netsecure](https://github.com/simonfrey/netSecure) Macaddress Spoofing - IPv6 Randomising - SYN Attack Protection *** Android Root App
- [**1**星][5y] [HTML] [qfc9/email-spoof](https://github.com/qfc9/email-spoof) A template on how to email spoof people
- [**1**星][4y] [C] [garbaz/ipspoof](https://github.com/garbaz/ipspoof) IP spoof stuff
- [**0**星][5y] [C++] [illahaha/zxarps](https://github.com/illahaha/zxarps) arpspoof
- [**0**星][5y] [oxtoacart/flashlight](https://github.com/oxtoacart/flashlight) Lightweight host-spoofing web proxy written in go
- [**0**星][3y] [Java] [uddhavpgautam/ip-spoofing-detection-prevention-for-network-intrusion-detection-prevention-based-on-tcp-seq-number](https://github.com/uddhavpgautam/ip-spoofing-detection-prevention-for-network-intrusion-detection-prevention-based-on-tcp-seq-number) IP Spoofing detection prevention for network intrusion detection prevention based on TCP sequence number prediction attack


### <a id="62b461e2ceead9edb75c1b51f6eecdfd"></a>检测绕过


- [**3189**星][2m] [C] [valdikss/goodbyedpi](https://github.com/valdikss/goodbyedpi) 绕过许多已知的网络服务提供商提供的阻止访问某些网站的深度数据包检查系统


### <a id="3bd67ee9f322e2c85854991c85ed6da0"></a>投毒&&Poisoning


- [**5173**星][1y] [JS] [samyk/poisontap](https://github.com/samyk/poisontap) Exploits locked/password protected computers over USB, drops persistent WebSocket-based backdoor, exposes internal router, and siphons cookies using Raspberry Pi Zero & Node.js.
- [**767**星][5y] [Py] [shadowsocks/chinadns-python](https://github.com/shadowsocks/chinadns-python) Protect yourself against DNS poisoning in China.
- [**106**星][1y] [Py] [5alt/ultrarelay](https://github.com/5alt/ultrarelay) poison and relay NTLM credentials
- [**66**星][7m] [C] [hc0d3r/sshd-poison](https://github.com/hc0d3r/sshd-poison) a tool to get creds of pam based sshd authentication
- [**44**星][4m] [Py] [bieberg0n/bjdns](https://github.com/bieberg0n/bjdns) A dns server which can protect yourself against DNS poisoning in China. / 抗污染 带缓存的dns服务器
- [**29**星][2y] [Py] [aarreedd/arp-defense](https://github.com/aarreedd/arp-defense) ARP Poisoning Defense Scripts
- [**26**星][5y] [Py] [oros42/arp_poisoning_detector](https://github.com/oros42/arp_poisoning_detector) Simple detector of ARP poisoning attack
- [**24**星][5m] [Go] [skeeto/pgp-poisoner](https://github.com/skeeto/pgp-poisoner) PGP key poisoner
- [**22**星][6y] [C] [t00sh/elf-poison](https://github.com/t00sh/elf-poison) Proof Of Concept for inserting code in ELF binaries.
- [**20**星][4m] [C] [en14c/erebus](https://github.com/en14c/erebus) Poc for ELF64 runtime infection via GOT poisoning technique by elfmaster
- [**17**星][7y] [C] [m0nad/arp-poison](https://github.com/m0nad/arp-poison) arp-poison (aka arp spoof) tool
- [**12**星][4y] [Perl] [mattiasgeniar/slowloris](https://github.com/mattiasgeniar/slowloris) Slowloris - the low bandwidth, yet greedy and poisonous HTTP client
- [**8**星][4y] [Java] [mehiar/arp-poisoning-and-defend](https://github.com/mehiar/arp-poisoning-and-defend) 
- [**8**星][4y] [Go] [nkbai/arppoison](https://github.com/nkbai/arppoison) arp poison 可以进行dns欺骗，流量之类的操作
- [**5**星][4y] [Ruby] [msiavashi/ada-arp-defense](https://github.com/msiavashi/ada-arp-defense) Ada is a very simple tool written in pure ruby and on top of packetfu to detect arp poisoned packets and defend you automatically from the attack while even find the attacker for you .
- [**4**星][4m] [C] [srjanel/arp_poisoning](https://github.com/srjanel/arp_poisoning) Arp Poisoning tool in C using raw sockets
- [**3**星][2y] [Py] [b2dfir/linuxpoisonablelogfinder](https://github.com/b2dfir/linuxpoisonablelogfinder) Security Testing Tool to identify whether a list of common log files, which may be used for log poisoning, can be accessed from an known local file inclusion vulnerability.
- [**3**星][5m] [Py] [emreovunc/arp-poisoning-tool](https://github.com/emreovunc/arp-poisoning-tool) ARP Poisoning Tool
- [**2**星][1y] [Py] [fishyyh/arppoison](https://github.com/fishyyh/arppoison) 
- [**1**星][3y] [C] [abapat/dnspoison](https://github.com/abapat/dnspoison) A DNS packet injection and poisoning detection utility
- [**1**星][2y] [filipemgs/poisonjs](https://github.com/filipemgs/poisonjs) PoisonJS - De-obfuscate eval-based JavaScript obfuscation with monkey-patched eval(-like) functions.




# <a id="42ae221f526f55b5282ea221a376ec6c"></a>中间人&&MITM


***


## <a id="42f9e068b6511bcbb47d6b2b273097da"></a>未分类


- [**6523**星][28d] [Go] [bettercap/bettercap](https://github.com/bettercap/bettercap) 新版的bettercap, Go 编写. bettercap 是强大的、模块化、可移植且易于扩展的 MITM 框架, 旧版用 Ruby 编写
- [**2989**星][5d] [JS] [evilsocket/pwnagotchi](https://github.com/evilsocket/pwnagotchi) 深度学习+Bettercap，基于A2C，从周围的WiFi环境中学习，以最大程度地利用捕获的WPA关键信息
- [**2905**星][1y] [Py] [byt3bl33d3r/mitmf](https://github.com/byt3bl33d3r/mitmf) Framework for Man-In-The-Middle attacks
- [**2829**星][2m] [Go] [kgretzky/evilginx2](https://github.com/kgretzky/evilginx2) 独立的MITM攻击工具，用于登录凭证钓鱼，可绕过双因素认证
- [**2551**星][2y] [evilsocket/bettercap](https://github.com/evilsocket/bettercap) 中间人攻击框架，功能完整，模块化设计，轻便且易于扩展。
- [**1425**星][2m] [Py] [xdavidhu/mitmap](https://github.com/xdavidhu/mitmap) 
- [**1385**星][11d] [Go] [unrolled/secure](https://github.com/unrolled/secure) HTTP middleware for Go that facilitates some quick security wins.
- [**1295**星][2y] [Go] [malfunkt/hyperfox](https://github.com/malfunkt/hyperfox) 在局域网上代理和记录 HTTP 和 HTTPs 通信
- [**1204**星][4m] [C] [droe/sslsplit](https://github.com/droe/sslsplit) 透明SSL/TLS拦截
- [**1194**星][3m] [Py] [jtesta/ssh-mitm](https://github.com/jtesta/ssh-mitm) SSH 中间人攻击工具
- [**1101**星][8m] [Ruby] [lionsec/xerosploit](https://github.com/lionsec/xerosploit) Efficient and advanced man in the middle framework
- [**1046**星][4m] [PS] [kevin-robertson/inveigh](https://github.com/kevin-robertson/inveigh) Windows PowerShell ADIDNS/LLMNR/mDNS/NBNS spoofer/man-in-the-middle tool
- [**1008**星][2m] [Go] [justinas/nosurf](https://github.com/justinas/nosurf) CSRF protection middleware for Go.
- [**985**星][1y] [HTML] [sensepost/mana](https://github.com/sensepost/mana) *DEPRECATED* mana toolkit for wifi rogue AP attacks and MitM
- [**980**星][2m] [Py] [syss-research/seth](https://github.com/syss-research/seth) Perform a MitM attack and extract clear text credentials from RDP connections
- [**949**星][2y] [Py] [arnaucube/coffeeminer](https://github.com/arnaucube/coffeeMiner) collaborative (mitm) cryptocurrency mining pool in wifi networks
- [**845**星][1y] [Py] [kgretzky/evilginx](https://github.com/kgretzky/evilginx) man-in-the-middle attack framework used for phishing credentials and session cookies of any web service
- [**596**星][9m] [Py] [fox-it/mitm6](https://github.com/fox-it/mitm6) exploits the default configuration of Windows to take over the default DNS server
- [**582**星][12m] [HTML] [r00t-3xp10it/morpheus](https://github.com/r00t-3xp10it/morpheus) Morpheus - Automating Ettercap TCP/IP (MITM-hijacking Tool)
- [**547**星][2y] [TS] [samdenty/injectify](https://github.com/samdenty/injectify) 对网站实行中间人攻击的框架
- [**522**星][4y] [C] [jondonym/peinjector](https://github.com/jondonym/peinjector) peinjector - MITM PE file infector
- [**515**星][13d] [JS] [moll/node-mitm](https://github.com/moll/node-mitm) Intercept and mock outgoing Node.js network TCP connections and HTTP requests for testing. Intercepts and gives you a Net.Socket, Http.IncomingMessage and Http.ServerResponse to test and respond with. Super useful when testing code that hits remote servers.
- [**473**星][3y] [CoffeeScript] [rastapasta/pokemon-go-mitm](https://github.com/rastapasta/pokemon-go-mitm) 
- [**443**星][23d] [TS] [shroudedcode/apk-mitm](https://github.com/shroudedcode/apk-mitm) 
- [**439**星][1y] [JS] [digitalsecurity/btlejuice](https://github.com/digitalsecurity/btlejuice) BtleJuice Bluetooth Smart (LE) Man-in-the-Middle framework
- [**434**星][8y] [C++] [moxie0/sslsniff](https://github.com/moxie0/sslsniff) A tool for automated MITM attacks on SSL connections.
- [**399**星][4m] [Go] [cloudflare/mitmengine](https://github.com/cloudflare/mitmengine) A MITM (monster-in-the-middle) detection tool. Used to build MALCOLM:
- [**391**星][2y] [Py] [conorpp/btproxy](https://github.com/conorpp/btproxy) Man in the Middle analysis tool for Bluetooth.
- [**391**星][1m] [JS] [joeferner/node-http-mitm-proxy](https://github.com/joeferner/node-http-mitm-proxy) HTTP Man In The Middle (MITM) Proxy
- [**385**星][1y] [JS] [securing/gattacker](https://github.com/securing/gattacker) A Node.js package for BLE (Bluetooth Low Energy) security assessment using Man-in-the-Middle and other attacks
- [**368**星][11m] [Py] [crypt0s/fakedns](https://github.com/crypt0s/fakedns) A regular-expression based python MITM DNS server with support for DNS Rebinding attacks
- [**355**星][26d] [Py] [gosecure/pyrdp](https://github.com/gosecure/pyrdp) RDP man-in-the-middle (mitm) and library for Python 3 with the ability to watch connections live or after the fact
- [**347**星][1y] [Py] [quickbreach/smbetray](https://github.com/quickbreach/smbetray) SMB MiTM tool with a focus on attacking clients through file content swapping, lnk swapping, as well as compromising any data passed over the wire in cleartext.
- [**342**星][2y] [Shell] [brannondorsey/mitm-router](https://github.com/brannondorsey/mitm-router) mitm-router：将任何一台Linux 计算机转变成公开的 Wi-Fi 网络，并且默认Man-in-the-middle 所有 http 流量
- [**296**星][1y] [Shell] [cryptolok/ghostinthenet](https://github.com/cryptolok/ghostinthenet) Ultimate Network Stealther that makes Linux a Ghost In The Net and protects from MITM/DOS/scan
- [**290**星][2y] [Py] [websploit/websploit](https://github.com/websploit/websploit) websploit is an advanced MITM framework
- [**279**星][3y] [JS] [wuchangming/https-mitm-proxy-handbook](https://github.com/wuchangming/https-mitm-proxy-handbook) 基于Node.js的HTTPS MITM(中间人)代理的原理和实现
- [**251**星][4m] [C#] [kevin-robertson/inveighzero](https://github.com/kevin-robertson/inveighzero) Windows C# LLMNR/mDNS/NBNS/DNS spoofer/man-in-the-middle tool
- [**240**星][4y] [Py] [intrepidusgroup/mallory](https://github.com/intrepidusgroup/mallory) Mallory - MiTM TCP and UDP Proxy
- [**236**星][4y] [Py] [withdk/badusb2-mitm-poc](https://github.com/withdk/badusb2-mitm-poc) BadUSB 2.0 USB-HID MiTM POC
- [**229**星][9m] [Py] [ivanvza/arpy](https://github.com/ivanvza/arpy) Mac OSX ARP spoof (MiTM) tool that can also plug into Gource
- [**228**星][19d] [sab0tag3d/mitm-cheatsheet](https://github.com/sab0tag3d/mitm-cheatsheet) All MITM attacks in one place.
- [**188**星][3m] [Py] [internetarchive/warcprox](https://github.com/internetarchive/warcprox) WARC writing MITM HTTP/S proxy
- [**181**星][3y] [Py] [ctxis/wsuspect-proxy](https://github.com/ctxis/wsuspect-proxy) WSUSpect Proxy - a tool for MITM'ing insecure WSUS connections
- [**177**星][4y] [Shell] [floyd-fuh/tiny-mitm-proxy](https://github.com/floyd-fuh/tiny-mitm-proxy) Probably one of the smallest SSL MITM proxies you can make
- [**175**星][3y] [Shell] [praetorian-code/mitm-vm](https://github.com/praetorian-code/mitm-vm) An easy-to-deploy virtual machine that can provide flexible man-in-the-middle capabilities.
- [**171**星][3y] [HTML] [purpleteam/snarf](https://github.com/purpleteam/snarf) Snarf man-in-the-middle / relay suite
- [**166**星][2m] [C] [elementsproject/secp256k1-zkp](https://github.com/elementsproject/secp256k1-zkp) Experimental fork of libsecp256k1 with support for pedersen commitments and range proofs.
- [**161**星][3y] [Py] [pentesteres/delorean](https://github.com/pentesteres/delorean) NTP Main-in-the-Middle tool
- [**148**星][5y] [Py] [mveytsman/dilettante](https://github.com/mveytsman/dilettante) Maven central doesn't do SSL when serving you JARs. Dilettante is a MiTM proxy for exploiting that.
- [**146**星][2y] [Go] [magisterquis/sshhipot](https://github.com/magisterquis/sshhipot) High-interaction MitM SSH honeypot
- [**137**星][29d] [Shell] [reb311ion/tornado](https://github.com/reb311ion/tornado) All in one MITM tool .
- [**134**星][19d] [Py] [certcc/tapioca](https://github.com/certcc/tapioca) CERT Tapioca for MITM network analysis
- [**128**星][4y] [Py] [andrewhilts/snifflab](https://github.com/andrewhilts/snifflab) Scripts to create your own MITM'ing, packet sniffing WiFi access point
- [**118**星][1y] [Py] [amossys/memitm](https://github.com/amossys/memitm) Tool to make in memory man in the middle
- [**113**星][2y] [Shell] [pimps/wsuxploit](https://github.com/pimps/wsuxploit) wsuxploit：MiTM 漏洞利用脚本，用于将“假冒”更新注入到非 SSL WSUS 流量中
- [**112**星][3y] [Py] [codepr/creak](https://github.com/codepr/creak) Poison, reset, spoof, redirect MITM script
- [**95**星][3y] [JS] [compewter/copycat](https://github.com/compewter/copycat) Universal MITM web server
- [**87**星][8m] [Shell] [1n3/prism-ap](https://github.com/1n3/prism-ap) An automated Wireless RogueAP MITM attack framework.
- [**85**星][4y] [Py] [liuhui0613/thewind](https://github.com/liuhui0613/thewind) a MITM attack tool
- [**82**星][6m] [Ruby] [argos83/ritm](https://github.com/argos83/ritm) Ruby In The Middle (HTTP/HTTPS interception proxy)
- [**77**星][4y] [CoffeeScript] [olegberman/mitm-omegle](https://github.com/olegberman/mitm-omegle) Watch strangers talk on Omegle (man in the middle attack)
- [**76**星][6y] [Shell] [neohapsis/suddensix](https://github.com/neohapsis/suddensix) IPV6 MITM attack tool
- [**69**星][2y] [Haskell] [adjoint-io/pedersen-commitment](https://github.com/adjoint-io/pedersen-commitment) Cryptographic Commitment Schemes
- [**66**星][4y] [JS] [etherdream/mitm-http-cache-poisoning](https://github.com/etherdream/mitm-http-cache-poisoning) HTTP Cache Poisoning Demo
- [**58**星][3y] [Shell] [r00t-3xp10it/netool-toolkit](https://github.com/r00t-3xp10it/netool-toolkit) MitM pentesting opensource toolkit (scan/sniff/exploit) -- NOT SUPORTED ANYMORE --
- [**55**星][2y] [C++] [caseysmithrc/memmitm](https://github.com/caseysmithrc/memmitm) SSL In Memory Inspection - Proof Of Concept.
- [**52**星][3y] [Py] [cylance/mitmcanary](https://github.com/cylance/mitmcanary) Tool/service to detect Man in the Middle attacks with Canary Requests
- [**51**星][1y] [Go] [mrexodia/haxxmap](https://github.com/mrexodia/haxxmap) Some simple go tools to perform a Man-in-the-middle (MITM) attack on your IMAP server in case you forgot your password.
- [**48**星][2y] [PS] [clr2of8/detect-sslmitm](https://github.com/clr2of8/detect-sslmitm) This PowerShell script will determine if your connection to external servers over HTTPS is being decrypted by an intercepting proxy such as the internet proxies commonly found in corporate environments. It does this by comparing the SSL intermediate certificate being used for your connection to the true/known SSL certificate for the server.
- [**47**星][4y] [C++] [mozmark/ringleader](https://github.com/mozmark/ringleader) A tool for configuring and using MITM proxies from firefox
- [**47**星][10m] [Py] [lorenzb/libsubmarine](https://github.com/lorenzb/libsubmarine) Implementation of a novel practical scheme for submarine commitments
- [**42**星][5y] [Py] [husam212/mitmer](https://github.com/husam212/mitmer) Automated man-in-the-middle attack tool.
- [**42**星][1y] [C#] [advancedhacker101/c-sharp-proxy-server](https://github.com/advancedhacker101/c-sharp-proxy-server) A proxy server built with c# can be both normal and MITM Proxy
- [**40**星][6y] [Py] [ipopov/starttls-mitm](https://github.com/ipopov/starttls-mitm) A starttls-capable transparent man-in-the-middle proxy
- [**38**星][2y] [Py] [m4n3dw0lf/sslkill](https://github.com/m4n3dw0lf/sslkill) Forced Man-In-The-Middle HTTPs-Avoiding Reverse Proxy
- [**38**星][7m] [Java] [hsiafan/cute-proxy](https://github.com/hsiafan/cute-proxy) A Man-In-The-Middle Proxy as Fiddle and Charles, using Netty, JavaFX
- [**36**星][3y] [JS] [jackgu1988/dsploit-scripts](https://github.com/jackgu1988/dsploit-scripts) Scripts that could be injected in MITM attacks using dSploit
- [**35**星][7d] [Rust] [scipr-lab/poly-commit](https://github.com/scipr-lab/poly-commit) A Rust library for polynomial commitments
- [**33**星][5d] [Py] [kevcui/mitm-scripts](https://github.com/kevcui/mitm-scripts) 
- [**33**星][3y] [Py] [syss-research/dns-mitm](https://github.com/syss-research/dns-mitm) A minimal DNS service that can provide spoofed replies
- [**32**星][5y] [Perl] [linvex/mitm-squid](https://github.com/linvex/mitm-squid) sharing some files of MITM-squid attack.
- [**31**星][26d] [Ruby] [gplcc/gplcc](https://github.com/gplcc/gplcc) GPL Cooperation Commitment
- [**31**星][1y] [Py] [thusoy/postgres-mitm](https://github.com/thusoy/postgres-mitm) Test whether your Postgres connections are vulnerable to MitM attacks
- [**30**星][8y] [Py] [hubert3/isniff](https://github.com/hubert3/isniff) SSL man-in-the-middle tool targeting iOS devices < 4.3.5
- [**29**星][5y] [C] [conorpp/mitm-http-proxy](https://github.com/conorpp/mitm-http-proxy) A simple, low level http/https proxy server with MiTM pranking features.
- [**29**星][2m] [JS] [dangkyokhoang/man-in-the-middle](https://github.com/dangkyokhoang/man-in-the-middle) Modify requests, inject JavaScript and CSS into pages
- [**28**星][3y] [Java] [elynx/pokemon-go-xposed-mitm](https://github.com/elynx/pokemon-go-xposed-mitm) MITM attack on Pokemon Go (c) via XPosed framework
- [**28**星][3y] [Py] [mvondracek/wifimitm](https://github.com/mvondracek/wifimitm) Automation of MitM Attack on Wi-Fi Networks
- [**26**星][4y] [C] [gregwar/mitm](https://github.com/gregwar/mitm) Man in the middle tool
- [**25**星][2y] [Py] [the404hacking/websploit](https://github.com/the404hacking/websploit) Websploit is an advanced MITM framework.
- [**24**星][7y] [Java] [akdeniz/mitmsocks4j](https://github.com/akdeniz/mitmsocks4j) SOCKS代理协议的拦截器，可以转储任何连接的内容，即便有SSL进行保护
- [**24**星][2m] [TS] [dialogs/electron-ssl-pinning](https://github.com/dialogs/electron-ssl-pinning) Prevents MITM in Electron applications
- [**24**星][11m] [Nim] [imgp3dev/drmitm](https://github.com/imgp3dev/drmitm) DrMITM is a program designed to globally log all traffic of a website.
- [**23**星][8y] [C#] [sensepost/suru](https://github.com/sensepost/suru) Suru is one of the original Man In The Middle (MITM) proxies that sits between the user's browser and the web application.
- [**22**星][2m] [Py] [lockgit/py](https://github.com/lockgit/py) rsa,base64,ac,kmp,svm,knn,mitm,hash table...
- [**21**星][4y] [Shell] [psrcek/kali-mitm-evil-twin](https://github.com/psrcek/kali-mitm-evil-twin) A script that creates a wifi hotspot on kali linux that can view usernames and passwords of ssl logins.
- [**19**星][2y] [Py] [jakev/mitm-helper-wifi](https://github.com/jakev/mitm-helper-wifi) WiFi MITM Helper
- [**17**星][2y] [Py] [shramos/winregmitm](https://github.com/shramos/winregmitm) Perform MiTM attack and remove encryption on Windows Remote Registry Protocol.
- [**16**星][7m] [Java] [aquazus/d1proxy](https://github.com/aquazus/d1proxy) A simple yet powerful Java 11 TCP MITM proxy for Dofus 1.29.1
- [**15**星][7y] [Ruby] [yakindanegitim/mbfuzzer](https://github.com/yakindanegitim/mbfuzzer) Mobile Application Fuzzer via SSL MITM
- [**14**星][6m] [Rust] [nlevitt/monie](https://github.com/nlevitt/monie) man-in-the-middle http/https proxy library in rust
- [**12**星][1y] [Go] [syncsynchalt/dime-a-tap](https://github.com/syncsynchalt/dime-a-tap) Man-in-the-middle TLS intercept proxy with tcpdumpable loopback
- [**12**星][2y] [C++] [wakbox/wakxy](https://github.com/wakbox/wakxy) Wakxy is a Wakfu packet sniffer (MITM). Written in C++/Qt with Javascript scripting support.
- [**12**星][9m] [C++] [spx01/switch-nfp-mitm](https://github.com/spx01/switch-nfp-mitm) Man-in-the-middle the Nintendo Switch's nfp:user service to spoof Amiibos.
- [**11**星][11m] [Py] [nametoolong/oregano](https://github.com/nametoolong/oregano) Man-in-the-middle against Tor bridges
- [**10**星][6m] [HTML] [chinarulezzz/refluxion](https://github.com/chinarulezzz/refluxion) Refluxion -- MITM WPA attacks tool
- [**10**星][11m] [Py] [daniel4x/mitm-python](https://github.com/daniel4x/mitm-python) A simple as possible man in the middle written in python using scapy
    - 重复区段: [工具->Scapy](#01f99d208e245eb44f15f720043b50d4) |
- [**9**星][5m] [Py] [skyplabs/scapy-mitm](https://github.com/skyplabs/scapy-mitm) ARP cache poisoning implementation using Scapy
    - 重复区段: [工具->Scapy](#01f99d208e245eb44f15f720043b50d4) |
- [**9**星][4y] [8tiqa/vpn-security-analysis](https://github.com/8tiqa/vpn-security-analysis) Investigation of the core VPN technologies | Penetration testing of an IPsec-VPN (using Ike-scan and psk-crack) | MitM Attack on PPTP-VPN (using ARPspoof, chap2asleap, CUPP2 and ASLEAP) | In-depth research of IPv6 Leakage and DNS Hijacking i
- [**8**星][3y] [johnmccabe/mitmweb-docker](https://github.com/johnmccabe/mitmweb-docker) Docker image for the mitmproxy web interface mitmweb
- [**8**星][1m] [Go] [adguardteam/gomitmproxy](https://github.com/adguardteam/gomitmproxy) Simple golang mitm proxy implementation
- [**7**星][1y] [Py] [mathewmarcus/stoptls](https://github.com/mathewmarcus/stoptls) MitM proxy which performs opportunistic SSL/TLS stripping
- [**7**星][2y] [C++] [pfussell/pivotal](https://github.com/pfussell/pivotal) A MITM proxy server for reflective DLL injection through WinINet
- [**7**星][2y] [socprime/muddywater-apt](https://github.com/socprime/muddywater-apt) MuddyWater is an APT group that has been active throughout 2017, targeting victims in Middle East with in-memory vectors leveraging on Powershell, in a family of attacks now identified as “Living off the land”, as they don’t require the creation of new binaries on the victim’s machine, thus maintaining a low detection profile and a low forensic footprint.  The name MuddyWater has been assigned by PaloAlto in an article that describes how the actor’s backdoor, called POWERSTATS, evolved over the past year. For the sake of clarity we decided to maintain the same names.  The operators behind MuddyWater are likely espionage motivated, we derive this information from the analysis of data and backdoors behaviors. We also find that despite the strong preponderance of victims from Pakistan, the most active targets appear to be in: Saudi Arabia, UAE and Iraq. Amongst the victims we identify a variety of entities with a stronger focus at Governments, Telcos and Oil companies.
- [**7**星][1m] [Py] [th3hurrican3/mitm](https://github.com/th3hurrican3/mitm) A simple yet effective python3 script to perform DNS spoofing via ARP poisoning
- [**6**星][2y] [Java] [arvahedi/gl4dius](https://github.com/arvahedi/gl4dius) A very powerful tool for All kind of MITM attacks
- [**6**星][10m] [JS] [cutenode/mitm.cool](https://github.com/cutenode/mitm.cool) source code for mitm.cool, a dead-simple site that doesn't have SSL... allowing public WiFi to MITM the request and get you authenticated
- [**6**星][2y] [Go] [pulkitsharma07/proxybench](https://github.com/pulkitsharma07/proxybench) Benchmark different man-in-the-middle proxies
- [**6**星][5y] [Shell] [mrmugiwara/airbase-ng-sslstrip-airstrip-](https://github.com/mrmugiwara/airbase-ng-sslstrip-airstrip-) While documenting some MitM attacks I was looking into setting up a fake AP with BT5 and my good old loved ALFA . There's a whole bunch of scripts out there which do the job nicely, if you are ready to modify them here and there. In order for it to work, you need to run airmon-ng to start the card in monitor mode, run airbase-ng to run it in AP …
- [**5**星][4y] [Py] [0x8008135/pymitm6](https://github.com/0x8008135/pymitm6) 
- [**5**星][18d] [JS] [hotstu/open-slim-mock](https://github.com/hotstu/open-slim-mock) A lightweight & flexible nodejs powered web server for mock testing & MITM reverse proxy 一款基于nodejs的服务端程序，用于在app的开发调试阶段更好的与后端人员协作，便于前后端分离，快速定位接口问题
- [**5**星][1y] [TS] [pogosandbox/node-pogo-mitm](https://github.com/pogosandbox/node-pogo-mitm) 
- [**5**星][2y] [C++] [xiaxiaoyu1988/smitm](https://github.com/xiaxiaoyu1988/smitm) A http and https mitm tool
- [**4**星][2y] [Py] [gteissier/cve-2016-6271](https://github.com/gteissier/cve-2016-6271) Proof of concept for ZRTP man-in-the-middle
- [**4**星][1y] [Py] [mh4x0f/kinproxy](https://github.com/mh4x0f/kinproxy) my implements transparent proxies (mitmproxy) can use to intercept and manipulate HTTP traffic modifying requests and responses. CLI
- [**4**星][2y] [C++] [robertblackwell/marvincpp](https://github.com/robertblackwell/marvincpp) a C++ version of the man-in-the-middle proxy based around BOOST/ASIO's async IO model
- [**4**星][1y] [Py] [tanc7/facerider](https://github.com/tanc7/facerider) New and improved Man-In-The-Middle Framework fixes for Nethunter Phones and Tablets
- [**4**星][6y] [wshen0123/mitm-rogue-wifi-ap](https://github.com/wshen0123/mitm-rogue-wifi-ap) MITM Attack Example Code with Rogue Wi-Fi AP
- [**3**星][5y] [Perl] [em616/juli](https://github.com/em616/juli) A simple automated perl script for MiTM ( man-in-the-middle ) attacks.
- [**2**星][2y] [Py] [alvarogzp/man-in-the-middle](https://github.com/alvarogzp/man-in-the-middle) Python library implementing a network proxy with the ability to modify stream data
- [**2**星][3y] [Go] [andream16/gocrackerino](https://github.com/andream16/gocrackerino) Go Meet in The Middle Key Cracker
- [**2**星][1y] [Shell] [apacketofsweets/buttertrace](https://github.com/apacketofsweets/buttertrace) A wrapper that combines the use of arpspoof & tcpdump in order to perform MITM traffic interception
- [**2**星][8y] [Py] [crapworks/nervensaege](https://github.com/crapworks/nervensaege) SSL MitM Proxy for attacking online banking transactions
- [**2**星][2m] [Py] [danngalann/arpdos](https://github.com/danngalann/arpdos) A python script to DoS / MITM every device on the network (except yourself ;))
- [**2**星][3y] [Py] [gosecure/wsuspect-proxy](https://github.com/gosecure/wsuspect-proxy) WSUSpect Proxy - a tool for MITM'ing insecure WSUS connections
- [**2**星][4y] [C#] [hotallday/xat-mitm](https://github.com/hotallday/xat-mitm) Man in the middle attack on xat chats
- [**2**星][6y] [Py] [koto/exceed-mitm](https://github.com/koto/exceed-mitm) Exceed OnDemand MITM proof-of-concept
- [**2**星][2m] [Py] [nametoolong/mesona](https://github.com/nametoolong/mesona) MITM proxy with GnuTLS's record length hiding
- [**2**星][2y] [Swift] [windblaze/aegis](https://github.com/windblaze/aegis) MITM protection for MacOS
- [**1**星][2y] [JS] [keygen-sh/example-signature-verification](https://github.com/keygen-sh/example-signature-verification) An example implementation of verifying response signatures using RSA cryptography to prevent tampering with API response payloads, licensing bypasses, MITM attacks, etc.
- [**1**星][2y] [Ruby] [samyoyo/bettercap](https://github.com/samyoyo/bettercap) A complete, modular, portable and easily extensible MITM framework.
- [**1**星][2y] [Java] [vincent-winner/lanmitm](https://github.com/vincent-winner/lanmitm) 中间人攻击-安卓
- [**0**星][2y] [Py] [bioverflow/injectionpoint](https://github.com/bioverflow/injectionpoint) MiTM attack to inject JS code in a public WiFi hotspot, initially to cryptocurrency
- [**0**星][6y] [Shell] [ekultek/suddensix](https://github.com/ekultek/suddensix) IPV6 MITM attack tool
- [**0**星][3y] [C#] [klemenb/fiddly](https://github.com/klemenb/fiddly) A simple man-in-the-middle attack tool used for applying filters to the HTTP traffic on the local network.


***


## <a id="4958460c709a66ca528f1732117e8dfd"></a>收集


- [**145**星][2y] [chan9390/awesome-mitm](https://github.com/chan9390/awesome-mitm) Curated List of MitM frameworks on GitHub


***


## <a id="b4959a15647a6dcf79901f76655d0ca8"></a>mitmproxy


- [**17196**星][7d] [Py] [mitmproxy/mitmproxy](https://github.com/mitmproxy/mitmproxy) An interactive TLS-capable intercepting HTTP proxy for penetration testers and software developers.
- [**779**星][2y] [Py] [secretsquirrel/bdfproxy](https://github.com/secretsquirrel/bdfproxy) Patch Binaries via MITM: BackdoorFactory + mitmProxy. (NOT SUPPORTED)
- [**261**星][2y] [Go] [zboya/gomitmproxy](https://github.com/zboya/gomitmproxy) gomitmproxy是想用golang语言实现[mitmproxy]，实现http(s)代理
- [**170**星][3m] [JS] [wuchangming/node-mitmproxy](https://github.com/wuchangming/node-mitmproxy) node-mitmproxy is an extensible man-in-the-middle(MITM) proxy server for HTTP/HTTPS base on Node.js.
- [**96**星][2y] [Py] [jjf012/passivescanner](https://github.com/jjf012/passivescanner) a passive scanner based on Mitmproxy and Arachni
- [**68**星][1y] [Py] [feeicn/webproxy](https://github.com/feeicn/webproxy) Create an HTTP / HTTPS proxy server based on MITMProxy and log all requests to the log file and parse the log for rewriting into the database.
- [**59**星][2y] [Py] [cortesi/mitmproxy](https://github.com/cortesi/mitmproxy) An interactive SSL-capable intercepting HTTP proxy for penetration testers and software developers
- [**23**星][7m] [TS] [jvilk/mitmproxy-node](https://github.com/jvilk/mitmproxy-node) A bridge between Python's mitmproxy and Node.JS programs. Rewrite network requests using Node.JS!
- [**11**星][12m] [JS] [xtr4nge/fruityproxy](https://github.com/xtr4nge/fruityproxy) FruityProxy allows MITM attacks. MITMproxy inline scripts can be imported. It is possible to set an upstream proxy. FruityProxy is part of FruityWifi project. It provides a RESTful API.
- [**7**星][6m] [Py] [muzuiget/mitmpcap](https://github.com/muzuiget/mitmpcap) 将mitmproxy的流量导出到pcap文件
- [**6**星][1y] [Py] [kr1tzb1tz/mitmproxy_pwnage](https://github.com/kr1tzb1tz/mitmproxy_pwnage) 
- [**1**星][6y] [kenjoe41/mitmproxy](https://github.com/kenjoe41/mitmproxy) An interactive SSL-capable intercepting HTTP proxy for penetration testers and software developers


# 贡献
内容为系统自动导出, 有任何问题请提issue