# Engine Patcher
🎞️ SMM:WE 本地化 &amp; 服务器补丁

#### 怎么用?

##### SMM:WE for PC

- 用 `patch.py` 替换字符串

- 用 `patch_server_ip.sh <SMM_WE_EngineTribe_XX.exe>` 替换游戏服务器 ip

- 用 `package_pc.sh` 打包补丁

##### SMM:WE for Android

- 在游戏文件中找到 `libyoyo.so`

- 用 `patch.py` 替换字符串

- 用 `patch_server_ip.sh <libyoyo.so>` 替换游戏服务器 ip

- 签名并替换 `libyoyo.so` 你的 apk


**需要注意的是，补丁只针对一刀斩发布的，如果你想自己使用，可能需要做些修改**

**sh 文件可能只适用于 Linux 和 macOS**
