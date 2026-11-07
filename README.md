Shadowsocks-Qt5
===============
Note: The original libQtShadowsocks no longer builds on current Linux (Botan 2.19). To compile this program yourself, first build and install the fixed library from https://github.com/hjzwerver/libQtShadowsocks. A ready-made .deb for Linux Mint 22 / Ubuntu 24.04 is available under Releases.
**This project is no longer being maintained**

[![Build Status](https://travis-ci.org/shadowsocks/shadowsocks-qt5.svg?branch=master)](https://travis-ci.org/shadowsocks/shadowsocks-qt5)

Please check [project's wiki](https://github.com/shadowsocks/shadowsocks-qt5/wiki) for "how-tos".

Introduction
------------

Shadowsocks-Qt5 is a native and cross-platform [shadowsocks](http://shadowsocks.org) GUI client with advanced features.

Features
--------

- Shadowsocks-Qt5 is written in C++ with Qt 5.
- Support traffic statistics
- Support server latency (lag) test
- Use multiple profiles simultaneously
- `config.ini` is located under `~/.config/shadowsocks-qt5/` on \*nix platforms, or under the application's directory on Windows.

LICENSE
-------

![](http://www.gnu.org/graphics/lgplv3-147x51.png)

Copyright © 2014-2017 Symeon Huang

This project is licensed under version 3 of the GNU Lesser General Public License.
