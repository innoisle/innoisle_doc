---
description: 'Join our discord at: https://discord.innoisle.com/'
hidden: true
icon: reel
---

# SASCM-china version

## Not supported

(Global B platform)

Cadillac CT5 all years (2020年才上市，全都不行）

Cadillac CT6 2017 使用GM Harness，不能用pedal也不能用sascm，不支持ACC

***

## Supported Vehicle

**只要有acc就能装sascm**

如果自带的acc（自适应巡航）**能**跟车跟到停，且能跟车起步就可以支持红灯启停

如果自带的acc（自适应巡航）**不能**跟车跟到停，且不能跟车起步，就只能纵向跟车 （longitudinal control）

**Supported vehicles:**

* Chevy Volt (2016-2018)  （with Adaptive Cruise Control）
* Chevy Volt (2019) - _pedal also needed_
* Acadia Denali （2018）
* Buick Enclave
* Cadillac XT4
* Chevy Traverse  (2022-2023)
* Buick Baby Enclave
* Cadillac XT5
* Cadillac XT6
* Chevy Malibu XL
*

**中国specific 车**

firestar.link/kaofui\
这个是基于frogpilot的衍生fork，专门为sdgm和sascm做支持和优化过的。

Note：

国内的车，可能是SDGM也可能是ASCM，所以要问具体是什么线\
如果现在是用的SDGM线束就不用重新买线束了, 如果现在用的是ASCM线束就需要换我们的ASCM plus线束因为原来的线束少一条网关连接和一对接头, 这个ASCM plus把少的连接加上了.\
SDGM线束一般安装在驾驶位OBD接口的后面, 知道主动安全模块（ascm module）在哪的话就知道现在用的是什么线束了.

* Buick Envision (昂科威）2018 （with OP and ACC） - SDGM&#x20;
* Buick Verano 威朗 2017（with OP and ACC）(与欧洲opal同款，北美没有类似车型）- SDGM - 不一定可以红绿灯-有可能不支持，在等确认-不愿意试了已退。也许是不支持的
* Buick Enclave (昂科旗）2019-2022 - SDGM C- 已确定能用，可以用dragonpilot和frogpilot， dragonpilot 版本-0.10.2/dp3/827f237/jan05
* 别克君越 2020 有主动安全模块 - 在等确认

#### 回复：

先问

有没有装openpilot\
有没有ascm模块（主动安全模块）\
现在是怎么连接的什么配置

功能：

ascm或SDGM（根据车型分）是lkas （车道居中），sascm是acc （纵向控制）

## Installation Guide

The installation instruction for SASCM is basically the same as ASCM. While locating the ASCM, you will find the other port for SASCM.

Please refer to ASCM's installation instruction:

This is how you connect older style harness: https://docs.google.com/document/d/1bAoENo8edsbknXUx6bcx-L0-9dbgItJRCfd6DIyGDN0/edit?tab=t.0\
For the new ASCM harness, please locate the ASCM module and run the harness like a normal openpilot setup.
