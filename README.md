# Hackintosh EFI Rog Strix B760-G 小吹雪

## 更新记录

### 2025-08-04

* 更新 OpenCore 至 `1.0.5`
* 更新一众 KEXT
* 取消使用 `V2.0.2 | CpuTopologyRebuild.kext`（升级以后会导致黑屏，具体问题没看，我已在 BIOS 里关闭小核，所以不需要了），**如果你在使用 12 - 14 代 CPU，并且 BIOS 里并未关闭小核，需要打开此项**