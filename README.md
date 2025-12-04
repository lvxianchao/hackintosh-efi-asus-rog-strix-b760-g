# Hackintosh EFI Rog Strix B760-G 小吹雪

## 更新记录

### 2025-12-04

* 更新一众 KEXT，升级到　MacOS 26 Tahoe。
* 取消 WhateverGreen.kext，解决开机无限重启进不去长统。
* 勾选　`Kernel -> Quirks -> DisableIoMapper`　以解决有线网卡　Intel I226 可以识别但无法正常工作的问题。
* 取消　AppleALC.kext，在　MacOS 25 Tahoe 中已无法继续使用，我直接使用了外围声卡连接我的音响。

### 2025-08-04

* 更新 OpenCore 至 `1.0.5`
* 更新一众 KEXT
* 取消使用 `V2.0.2 | CpuTopologyRebuild.kext`（升级以后会导致黑屏，具体问题没看，我已在 BIOS 里关闭小核，所以不需要了），**如果你在使用 12 - 14 代 CPU，并且 BIOS 里并未关闭小核，需要打开此项**