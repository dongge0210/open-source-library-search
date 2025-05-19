# 精选 C/C++ 开源库推荐（高实用、高功能、稳定、高性能、主流）

本项目收录高实用、多功能、稳定、高性能、主流的 C/C++ 开源库。**轻量级/小众库已剔除，只保留行业公认主流或某领域极具代表性的库。**  
**YAML、XML、JSON、TOML 解析库必须包含。**

---

## 目录

- [基础功能/工具库](#基础功能工具库)
- [网络/协议/通信](#网络协议通信)
- [消息通信库](#消息通信库)
- [图形界面/多媒体](#图形界面多媒体)
- [数据/序列化/解析](#数据序列化解析)
- [图像/音视频处理](#图像音视频处理)
- [数据库/存储](#数据库存储)
- [安全/加密](#安全加密)
- [压缩](#压缩)
- [测试](#测试)
- [系统/硬件/性能/监控](#系统硬件性能监控)
- [2FA 认证/人机检测](#2fa-认证人机检测)

---

## 基础功能/工具库

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [Boost](https://www.boost.org/) | C++通用库集合，极其丰富 | BSL-1.0 | [GitHub](https://github.com/boostorg/boost) |
| [STL](https://github.com/microsoft/STL) | C++标准库实现 | Apache-2.0 | [GitHub](https://github.com/microsoft/STL) |
| [fmt](https://fmt.dev/) | 现代C++格式化库 | MIT | [GitHub](https://github.com/fmtlib/fmt) |
| [spdlog](https://github.com/gabime/spdlog) | 高性能日志库 | MIT | [GitHub](https://github.com/gabime/spdlog) |

## 网络/协议/通信

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [curl](https://curl.se/) | 跨平台HTTP等协议库 | curl license | [GitHub](https://github.com/curl/curl) |
| [libevent](http://libevent.org/) | 高性能事件驱动网络库 | BSD-3-Clause | [GitHub](https://github.com/libevent/libevent) |
| [libuv](https://libuv.org/) | 跨平台异步I/O库 | MIT | [GitHub](https://github.com/libuv/libuv) |
| [asio](https://think-async.com/) | C++异步IO | BSL-1.0 | [GitHub](https://github.com/chriskohlhoff/asio) |
| [libwebsockets](https://libwebsockets.org/) | WebSocket/HTTP/HTTPS 支持 | MIT | [GitHub](https://github.com/warmcat/libwebsockets) |
| [Mongoose](https://cesanta.com/mongoose) | 功能全面、嵌入式/跨平台 HTTP/HTTPS/WebSocket/HTTP3 服务器库 | GPL-2.0/Commercial | [GitHub](https://github.com/cesanta/mongoose) |
| [libssh](https://www.libssh.org/) | SSH 协议实现与客户端/服务器功能 | LGPL-2.1 | [GitHub](https://github.com/libssh/libssh) |

## 消息通信库

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [ZeroMQ](https://zeromq.org/) | 高性能异步消息队列通信库，适合分布式系统 | MPL-2.0 | [GitHub](https://github.com/zeromq/libzmq) |

## 图形界面/多媒体

| 名称 | 简介 | 协议 | 链接 | 适用平台 |
|---|---|---|---|---|
| [Qt](https://www.qt.io/) | 跨平台C++ GUI/QML/多媒体 | LGPL-3.0/GPL-2.0/Commercial | [GitHub](https://github.com/qt/qtbase) | 全平台 |
| [SDL](https://www.libsdl.org/) | 跨平台多媒体/游戏/音视频输入输出 | zlib | [GitHub](https://github.com/libsdl-org/SDL) | 全平台 |
| [ncurses](https://invisible-island.net/ncurses/) | 终端UI标准库 | MIT | [GitHub](https://github.com/mirror/ncurses) | 主流 Linux/UNIX 平台 |
| [PDCurses](https://github.com/wmcbrine/PDCurses) | ncurses 兼容的终端 UI 库 | Public Domain | [GitHub](https://github.com/wmcbrine/PDCurses) | Windows/SDL2/X11/OS2 等 |

## 数据/序列化/解析

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [nlohmann/json](https://github.com/nlohmann/json) | 现代C++ JSON解析库，极其流行 | MIT | [GitHub](https://github.com/nlohmann/json) |
| [yaml-cpp](https://github.com/jbeder/yaml-cpp) | C++ YAML解析库，主流 | MIT | [GitHub](https://github.com/jbeder/yaml-cpp) |
| [tinyxml2](https://github.com/leethomason/tinyxml2) | 轻量级XML解析库（主流应用最多） | Zlib | [GitHub](https://github.com/leethomason/tinyxml2) |
| [toml++](https://github.com/marzer/tomlplusplus) | C++ TOML解析库，主流 | MIT | [GitHub](https://github.com/marzer/tomlplusplus) |
| [inih](https://github.com/benhoyt/inih) | 超轻量INI配置文件解析库，易用高效 | BSD-3-Clause | [GitHub](https://github.com/benhoyt/inih) |

## 图像/音视频处理

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [OpenCV](https://opencv.org/) | 计算机视觉/图像处理/多平台 | Apache-2.0 | [GitHub](https://github.com/opencv/opencv) |
| [ffmpeg](https://ffmpeg.org/) | 最强音视频处理库 | LGPL-2.1/GPL-2.0 | [GitHub](https://github.com/FFmpeg/FFmpeg) |
| [libpng](http://www.libpng.org/pub/png/libpng.html) | PNG编解码 | libpng | [GitHub](https://github.com/glennrp/libpng) |
| [libjpeg-turbo](https://libjpeg-turbo.org/) | JPEG高性能编解码 | IJG/MIT/Custom | [GitHub](https://github.com/libjpeg-turbo/libjpeg-turbo) |
| [tesseract-ocr](https://github.com/tesseract-ocr/tesseract) | OCR文字识别 | Apache-2.0 | [GitHub](https://github.com/tesseract-ocr/tesseract) |

## 数据库/存储

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [sqlite](https://www.sqlite.org/) | 嵌入式关系型数据库 | Public Domain | [GitHub](https://github.com/sqlite/sqlite) |

## 安全/加密

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [openssl](https://www.openssl.org/) | 行业事实标准的通用加密库，支持SSL/TLS、对称/非对称加密、证书、哈希等，功能极其全面，广泛用于服务器、客户端、嵌入式等 | Apache-2.0 | [GitHub](https://github.com/openssl/openssl) |
| [libsodium](https://libsodium.gitbook.io/) | 现代、易用、高安全的加密库，API 简洁，适合新项目，涵盖加密、签名、密钥交换等 | ISC | [GitHub](https://github.com/jedisct1/libsodium) |
| [mbedTLS](https://www.trustedfirmware.org/projects/mbed-tls/) | 轻量级 SSL/TLS 加密库，适合嵌入式/物联网 | Apache-2.0 | [GitHub](https://github.com/Mbed-TLS/mbedtls) |
| [libssh](https://www.libssh.org/) | SSH 协议实现与客户端/服务器功能，广泛用于远程管理和安全传输 | LGPL-2.1 | [GitHub](https://github.com/libssh/libssh) |
| [Crypto++](https://www.cryptopp.com/) | C++开源高性能密码学库，涵盖对称/非对称加密、哈希、MAC、流密码、椭圆曲线、随机数等，算法丰富，头文件库，跨平台 | BSL-1.0 | [GitHub](https://github.com/weidai11/cryptopp) |

## 压缩

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [zlib](https://zlib.net/) | 通用压缩库，事实标准，ZIP/GZIP/PNG等都依赖 | zlib | [GitHub](https://github.com/madler/zlib) |

## 测试

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [Catch2](https://github.com/catchorg/Catch2) | 现代C++单元测试框架 | BSL-1.0 | [GitHub](https://github.com/catchorg/Catch2) |
| [doctest](https://github.com/doctest/doctest) | 超快C++单元测试 | MIT | [GitHub](https://github.com/doctest/doctest) |

## 系统/硬件/性能/监控

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [htop](https://github.com/htop-dev/htop) | 交互式进程/系统监控，支持CPU/内存/进程/负载等实时展示 | GPL-2.0 | [GitHub](https://github.com/htop-dev/htop) |
| [collectd](https://github.com/collectd/collectd) | 强大的系统性能数据采集守护进程，支持插件扩展，可采集CPU/内存/磁盘/网络/温度等 | MIT | [GitHub](https://github.com/collectd/collectd) |
| [sysstat](https://github.com/sysstat/sysstat) | 包含sar/iostat/mpstat等经典系统性能分析工具，统计历史与实时数据 | GPL-2.0 | [GitHub](https://github.com/sysstat/sysstat) |
| [lm-sensors](https://github.com/lm-sensors/lm-sensors) | Linux平台硬件传感器检测库/工具，支持温度、电压、风扇转速读取 | GPL-2.0 | [GitHub](https://github.com/lm-sensors/lm-sensors) |
| [smartmontools](https://github.com/mirror/smartmontools) | 硬盘S.M.A.R.T健康监控，检测磁盘健康状态、寿命、坏道等 | GPL-2.0 | [GitHub](https://github.com/mirror/smartmontools) |
| [LibreHardwareMonitor](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor) | 跨平台硬件监控库（C#实现，常用于与C/C++服务配合），可读取主板/CPU/显卡/硬盘等多项信息 | LGPL-3.0 | [GitHub](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor) |
| [hwloc](https://github.com/open-mpi/hwloc) | 硬件拓扑发现库，自动识别多核/NUMA/PCIe拓扑，便于资源绑定和亲和性优化 | BSD-3-Clause | [GitHub](https://github.com/open-mpi/hwloc) |

## 2FA 认证/人机检测

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [oath-toolkit (liboath)](https://github.com/OpenSC/oath-toolkit) | 功能强大的 TOTP/HOTP 双因素认证库，兼容 Google/Microsoft Authenticator 等主流 App | GPL-3.0 | [官方文档](https://www.nongnu.org/oath-toolkit/) |
| [SimpleCaptcha](https://github.com/hiroi-sora/SimpleCaptcha) | C++ 图形验证码生成库，支持扭曲字符、数学题、噪声等多种风格 | MIT | [GitHub](https://github.com/hiroi-sora/SimpleCaptcha) |

---

> 如需补充或专向领域推荐，欢迎提 issue/PR！
