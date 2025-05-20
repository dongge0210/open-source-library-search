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
- [远程控制/运维](#远程控制运维)

---

## 基础功能/工具库

| 名称 | 简介 | 协议 | 链接 | 主要语言 |
|---|---|---|---|---|
| [Boost](https://www.boost.org/) | C++通用库集合，极其丰富 | BSL-1.0 | [GitHub](https://github.com/boostorg/boost) | C++ 约 85.0%，C 约 8.0%，Python 约 2.0% |
| [STL](https://github.com/microsoft/STL) | C++标准库实现 | Apache-2.0 | [GitHub](https://github.com/microsoft/STL) | C++ 约 99.9%，其他 <0.1% |
| [fmt](https://fmt.dev/) | 现代C++格式化库 | MIT | [GitHub](https://github.com/fmtlib/fmt) | C++ 约 95.0%，CMake 约 3.0%，Python 约 2.0% |

## 网络/协议/通信

| 名称 | 简介 | 协议 | 链接 | 主要语言 |
|---|---|---|---|---|
| [curl](https://curl.se/) | 跨平台HTTP等协议库 | curl license | [GitHub](https://github.com/curl/curl) | C 约 90.0%，Python 约 5.0%，Others 约 5.0% |
| [libevent](http://libevent.org/) | 高性能事件驱动网络库 | BSD-3-Clause | [GitHub](https://github.com/libevent/libevent) | C 约 88.0%，C++ 约 6.0%，Others 约 6.0% |
| [asio](https://think-async.com/) | C++异步IO | BSL-1.0 | [GitHub](https://github.com/chriskohlhoff/asio) | C++ 约 96.0%，CMake 约 3.0%，Others 约 1.0% |
| [libwebsockets](https://libwebsockets.org/) | WebSocket/HTTP/HTTPS 支持 | MIT | [GitHub](https://github.com/warmcat/libwebsockets) | C 约 75.0%，C++ 约 20.0%，Others 约 5.0% |
| [Mongoose](https://cesanta.com/mongoose) | 功能全面、嵌入式/跨平台 HTTP/HTTPS/WebSocket/HTTP3 服务器库 | GPL-2.0/Commercial | [GitHub](https://github.com/cesanta/mongoose) | C 约 80.0%，C++ 约 15.0%，Others 约 5.0% |
| [libssh](https://www.libssh.org/) | SSH 协议实现与客户端/服务器功能 | LGPL-2.1 | [GitHub](https://github.com/libssh/libssh) | C 约 90.0%，Shell 约 5.0%，Others 约 5.0% |

## 消息通信库

| 名称 | 简介 | 协议 | 链接 | 主要语言 |
|---|---|---|---|---|
| [ZeroMQ](https://zeromq.org/) | 高性能异步消息队列通信库，适合分布式系统 | MPL-2.0 | [GitHub](https://github.com/zeromq/libzmq) | C++ 约 60.0%，C 约 35.0%，Others 约 5.0% |

## 图形界面/多媒体

| 名称 | 简介 | 协议 | 链接 | 适用平台 | 主要语言 |
|---|---|---|---|---|---|
| [Qt](https://www.qt.io/) | 跨平台C++ GUI/QML/多媒体 | LGPL-3.0/GPL-2.0/Commercial | [GitHub](https://github.com/qt/qtbase) | 全平台 | C++ 约 95.0%，QML/JS 约 3.0%，Others 约 2.0% |
| [SDL](https://www.libsdl.org/) | 跨平台多媒体/游戏/音视频输入输出 | zlib | [GitHub](https://github.com/libsdl-org/SDL) | 全平台 | C 约 86.0%，C++ 约 10.0%，Others 约 4.0% |
| [ncurses](https://invisible-island.net/ncurses/) | 终端UI标准库 | MIT | [GitHub](https://github.com/mirror/ncurses) | 主流 Linux/UNIX 平台 | C 约 95.0%，Shell 约 4.0%，Others 约 1.0% |
| [PDCurses](https://github.com/wmcbrine/PDCurses) | ncurses 兼容的终端 UI 库 | Public Domain | [GitHub](https://github.com/wmcbrine/PDCurses) | Windows/SDL2/X11/OS2 等 | C 约 98.0%，Others 约 2.0% |

## 数据/序列化/解析

| 名称 | 简介 | 协议 | 链接 | 主要语言 |
|---|---|---|---|---|
| [nlohmann/json](https://github.com/nlohmann/json) | 现代C++ JSON解析库，极其流行 | MIT | [GitHub](https://github.com/nlohmann/json) | C++ 约 98.0%，Others 约 2.0% |
| [yaml-cpp](https://github.com/jbeder/yaml-cpp) | C++ YAML解析库，主流 | MIT | [GitHub](https://github.com/jbeder/yaml-cpp) | C++ 约 98.0%，CMake 约 2.0% |
| [tinyxml2](https://github.com/leethomason/tinyxml2) | 轻量级XML解析库（主流应用最多） | Zlib | [GitHub](https://github.com/leethomason/tinyxml2) | C++ 约 98.0%，Others 约 2.0% |
| [toml++](https://github.com/marzer/tomlplusplus) | C++ TOML解析库，主流 | MIT | [GitHub](https://github.com/marzer/tomlplusplus) | C++ 约 99.0%，CMake 约 1.0% |
| [inih](https://github.com/benhoyt/inih) | 超轻量INI配置文件解析库，易用高效 | BSD-3-Clause | [GitHub](https://github.com/benhoyt/inih) | C++ 约 45.0%，C 约 45.0%，Others 约 10.0% |

## 图像/音视频处理

| 名称 | 简介 | 协议 | 链接 | 主要语言 |
|---|---|---|---|---|
| [OpenCV](https://opencv.org/) | 计算机视觉/图像处理/多平台 | Apache-2.0 | [GitHub](https://github.com/opencv/opencv) | C++ 约 85.0%，C 约 5.0%，Python 约 5.0% |
| [ffmpeg](https://ffmpeg.org/) | 最强音视频处理库 | LGPL-2.1/GPL-2.0 | [GitHub](https://github.com/FFmpeg/FFmpeg) | C 约 70.0%，Assembly 约 20.0%，C++ 约 5.0% |
| [libpng](http://www.libpng.org/pub/png/libpng.html) | PNG编解码 | libpng | [GitHub](https://github.com/glennrp/libpng) | C 约 98.0%，Makefile 约 2.0% |
| [libjpeg-turbo](https://libjpeg-turbo.org/) | JPEG高性能编解码 | IJG/MIT/Custom | [GitHub](https://github.com/libjpeg-turbo/libjpeg-turbo) | C 约 80.0%，Assembly 约 15.0%，Others 约 5.0% |
| [tesseract-ocr](https://github.com/tesseract-ocr/tesseract) | OCR文字识别 | Apache-2.0 | [GitHub](https://github.com/tesseract-ocr/tesseract) | C++ 约 75.0%，C 约 15.0%，Others 约 10.0% |

## 数据库/存储

| 名称 | 简介 | 协议 | 链接 | 主要语言 |
|---|---|---|---|---|
| [sqlite](https://www.sqlite.org/) | 嵌入式关系型数据库 | Public Domain | [GitHub](https://github.com/sqlite/sqlite) | C 约 70.0%，C++ 约 25.0%，Others 约 5.0% |

## 安全/加密

| 名称 | 简介 | 协议 | 链接 | 主��语言 |
|---|---|---|---|---|
| [openssl](https://www.openssl.org/) | 行业事实标准的通用加密库，支持SSL/TLS、对称/非对称加密、证书、哈希等，功能极其全面，广泛用于服务器、客户端... | Apache-2.0 | [GitHub](https://github.com/openssl/openssl) | C 约 85.0%，Perl 约 10.0%，Others 约 5.0% |
| [libssh](https://www.libssh.org/) | SSH 协议实现与客户端/服务器功能，广泛用于远程管理和安全传输 | LGPL-2.1 | [GitHub](https://github.com/libssh/libssh) | C 约 90.0%，Shell 约 5.0%，Others 约 5.0% |
| [Crypto++](https://www.cryptopp.com/) | C++开源高性能密码学库，涵盖对称/非对称加密、哈希、MAC、流密码、椭圆曲线、随机数等，算法丰富，头文件库，跨平台 | Boost Software License 1.0 | [GitHub](https://github.com/weidai11/cryptopp) | C++ 约 95.0%，C 约 3.0%，Others 约 2.0% |

## 压缩

| 名称 | 简介 | 协议 | 链接 | 主要语言 |
|---|---|---|---|---|
| [zlib](https://zlib.net/) | 通用压缩库，事实标准，ZIP/GZIP/PNG等都依赖 | zlib | [GitHub](https://github.com/madler/zlib) | C 约 88.0%，Makefile 约 10.0%，Others 约 2.0% |

## 测试

| 名称 | 简介 | 协议 | 链接 | 主要语言 |
|---|---|---|---|---|
| [Catch2](https://github.com/catchorg/Catch2) | 现代C++单元测试框架 | BSL-1.0 | [GitHub](https://github.com/catchorg/Catch2) | C++ 约 95.0%，CMake 约 5.0% |
| [doctest](https://github.com/doctest/doctest) | 超快C++单元测试 | MIT | [GitHub](https://github.com/doctest/doctest) | C++ 约 96.0%，CMake 约 4.0% |

## 系统/硬件/性能/监控

| 名称 | 简介 | 协议 | 链接 | 主要语言 |
|---|---|---|---|---|
| [hwloc](https://github.com/open-mpi/hwloc) | 硬件拓扑发现库，自动识别多核/NUMA/PCIe拓扑，便于资源绑定和亲和性优化 | BSD-3-Clause | [GitHub](https://github.com/open-mpi/hwloc) | C 约 85.0%，C++ 约 10.0%，Others 约 5.0% |
| [LibreHardwareMonitor](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor) | 跨平台硬件监控库（C#实现，常用于与C/C++服务配合），可读取主板/CPU/显卡/硬盘等... | MIT | [GitHub](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor) | C# 约 97.0%，Others 约 3.0% |
| [smartmontools](https://github.com/mirror/smartmontools) | 硬盘S.M.A.R.T健康监控，检测磁盘健康状态、寿命、坏道等 | GPL-2.0 | [GitHub](https://github.com/mirror/smartmontools) | C++ 约 45.0%，C 约 45.0%，Others 约 10.0% |

## 2FA 认证/人机检测

| 名称 | 简介 | 协议 | 链接 | 主要语言 |
|---|---|---|---|---|
| [oath-toolkit (liboath)](https://github.com/OpenSC/oath-toolkit) | 功能强大的 TOTP/HOTP 双因素认证库，兼容 Google/Microsoft Authenticator 等主流 App | GPL-3.0 | [官方文档](https://www.nongnu.org/oath-toolkit/) | C 约 90.0%，Others 约 10.0% |
| [SimpleCaptcha](https://github.com/hiroi-sora/SimpleCaptcha) | C++ 图形验证码生成库，支持扭曲字符、数学题、噪声等多种风格 | MIT | [GitHub](https://github.com/hiroi-sora/SimpleCaptcha) | C++ 约 95.0%，Others 约 5.0% |

## 远程控制/运维

| 名称 | 简介 | 协议 | 链接 | 主要语言 |
|---|---|---|---|---|
| [MeshCentral](https://github.com/Ylianst/MeshCentral) | 开源远程管理平台，支持跨平台远控（Windows/Linux/Mac）、远程桌面、终端、文件传输等多种场景，适合企业... | Apache-2.0 | [GitHub](https://github.com/Ylianst/MeshCentral) | JavaScript 约 85.0%，HTML 约 10.0%，Others 约 5.0% |

---

> 如需补充或专向领域推荐，欢迎提 issue/PR！