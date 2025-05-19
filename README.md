# 精选 C/C++ 开源库推荐（高实用、高功能、稳定、高性能、主流）

本项目收录高实用、多功能、稳定、高性能、主流的 C/C++ 开源库。**轻量级/小众库已剔除，只保留行业公认主流或某领域极具代表性的库。**  
**YAML、XML、JSON、TOML 解析库必须包含。**

---

## 目录

- [基础功能/工具库](#基础功能工具库)
- [网络/协议/通信](#网络协议通信)
- [图形界面/多媒体](#图形界面多媒体)
- [数据/序列化/解析](#数据序列化解析)
- [图像/音视频处理](#图像音视频处理)
- [数据库/存储](#数据库存储)
- [算法/科学/数学](#算法科学数学)
- [安全/加密](#安全加密)
- [测试](#测试)
- [系统/硬件/性能/监控](#系统硬件性能监控)
- [其他特色库](#其他特色库)

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

## 图形界面/多媒体

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [Qt](https://www.qt.io/) | 跨平台C++ GUI/QML/多媒体 | LGPL-3.0/GPL-2.0/Commercial | [GitHub](https://github.com/qt/qtbase) |
| [SDL](https://www.libsdl.org/) | 跨平台多媒体/游戏/音视频输入输出 | zlib | [GitHub](https://github.com/libsdl-org/SDL) |
| [Dear ImGui](https://github.com/ocornut/imgui) | 实时GUI工具库 | MIT | [GitHub](https://github.com/ocornut/imgui) |
| [ncurses](https://invisible-island.net/ncurses/) | 终端UI标准库 | MIT | [GitHub](https://github.com/mirror/ncurses) |

## 数据/序列化/解析

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [nlohmann/json](https://github.com/nlohmann/json) | 现代C++ JSON解析库，极其流行 | MIT | [GitHub](https://github.com/nlohmann/json) |
| [rapidjson](https://github.com/Tencent/rapidjson) | 极高性能JSON解析库 | MIT | [GitHub](https://github.com/Tencent/rapidjson) |
| [yaml-cpp](https://github.com/jbeder/yaml-cpp) | C++ YAML解析库，主流 | MIT | [GitHub](https://github.com/jbeder/yaml-cpp) |
| [tinyxml2](https://github.com/leethomason/tinyxml2) | 轻量级XML解析库（主流应用最多） | Zlib | [GitHub](https://github.com/leethomason/tinyxml2) |
| [libxml2](http://xmlsoft.org/) | 工业级XML解析库（C，极为稳定） | MIT | [GitHub](https://github.com/GNOME/libxml2) |
| [toml++](https://github.com/marzer/tomlplusplus) | C++ TOML解析库，主流 | MIT | [GitHub](https://github.com/marzer/tomlplusplus) |

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
| [rocksdb](https://rocksdb.org/) | 高性能KV数据库 | Apache-2.0 | [GitHub](https://github.com/facebook/rocksdb) |
| [lmdb](https://github.com/LMDB/lmdb) | 极快的嵌入式KV数据库 | OpenLDAP | [GitHub](https://github.com/LMDB/lmdb) |
| [libarchive](https://www.libarchive.org/) | 归档/压缩格式支持 | BSD-2-Clause | [GitHub](https://github.com/libarchive/libarchive) |

## 算法/科学/数学

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [eigen](https://eigen.tuxfamily.org/) | 现代C++线性代数/矩阵/数值 | MPL2 | [GitLab](https://gitlab.com/libeigen/eigen) |
| [OpenBLAS](https://www.openblas.net/) | 高性能BLAS/LAPACK | BSD-3-Clause | [GitHub](https://github.com/OpenMathLib/OpenBLAS) |
| [armadillo](https://arma.sourceforge.net/) | MATLAB风格线性代数 | Apache-2.0 | [GitHub](https://github.com/conradsnicta/armadillo) |
| [xtensor](https://github.com/xtensor-stack/xtensor) | C++多维数组/高性能数值计算 | BSD-3-Clause | [GitHub](https://github.com/xtensor-stack/xtensor) |

## 安全/加密

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [openssl](https://www.openssl.org/) | 功能最全加密库 | Apache-2.0 | [GitHub](https://github.com/openssl/openssl) |
| [mbedtls](https://mbed-tls.readthedocs.io/) | 轻量TLS加密库 | Apache-2.0 | [GitHub](https://github.com/Mbed-TLS/mbedtls) |
| [libsodium](https://libsodium.gitbook.io/) | 高安全加密库 | ISC | [GitHub](https://github.com/jedisct1/libsodium) |

## 测试

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [Catch2](https://github.com/catchorg/Catch2) | 现代C++单元测试框架 | BSL-1.0 | [GitHub](https://github.com/catchorg/Catch2) |
| [doctest](https://github.com/doctest/doctest) | 超快C++单元测试 | MIT | [GitHub](https://github.com/doctest/doctest) |

## 系统/硬件/性能/监控

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [LibreHardwareMonitor](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor) | 硬件监控，传感器读取 | LGPL-3.0 | [GitHub](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor) |
| [htop](https://github.com/htop-dev/htop) | 交互式进程/系统监控 | GPL-2.0 | [GitHub](https://github.com/htop-dev/htop) |
| [collectd](https://github.com/collectd/collectd) | 采集和监控系统性能 | MIT | [GitHub](https://github.com/collectd/collectd) |
| [sysstat](https://github.com/sysstat/sysstat) | 性能分析工具 (sar等) | GPL-2.0 | [GitHub](https://github.com/sysstat/sysstat) |
| [lm-sensors](https://github.com/lm-sensors/lm-sensors) | Linux硬件监控 | GPL-2.0 | [GitHub](https://github.com/lm-sensors/lm-sensors) |
| [smartmontools](https://github.com/mirror/smartmontools) | 硬盘SMART监控 | GPL-2.0 | [GitHub](https://github.com/mirror/smartmontools) |
| [hwloc](https://github.com/open-mpi/hwloc) | 硬件拓扑发现和绑定 | BSD-3-Clause | [GitHub](https://github.com/open-mpi/hwloc) |

## 其他特色库

| 名称 | 简介 | 协议 | 链接 |
|---|---|---|---|
| [sokol](https://github.com/floooh/sokol) | 极简跨平台多媒体/图形/音频等功能库 | zlib | [GitHub](https://github.com/floooh/sokol) |

---

## 协议说明

| 协议 | 说明 |
|---|---|
| MIT/BSD/zlib/Public Domain/Apache-2.0/BSL-1.0/ISC | 最宽松、允许闭源商用，优先推荐 |
| LGPL/GPL/MPL | 次之，限制较多，注意兼容性和闭源需求 |
| Custom/Commercial | 请详读协议内容，部分需购买 |

---

> 如需补充或专向领域推荐，欢迎提 issue/PR！