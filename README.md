## FGOUnlockFPSOnWSA
### 环境
- WSA版本 `2207.40000.8.0`
- Magisk Zygisk
### 文件
- Magisk模块 `zygisk-InjecterForWSA-v1.0.0-release.zip`
- 一个so文件 `librawi.so`
- 一个配置文件 `rawi.ini` (帧率大小,可以自己改)
### 使用
- 刷入Magisk模块 `zygisk-InjecterForWSA-v1.0.0-release.zip`
- 使用adb工具把 `librawi.so` 和 `rawi.ini` 两个文件push到WSA的 `/data/local/tmp` 目录下
