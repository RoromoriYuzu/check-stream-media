# Introduce
The code for this script to detect streaming media unlocking is all from the open source project [https://github.com/lmc999/RegionRestrictionCheck](https://github.com/lmc999/RegionRestrictionCheck) , and the open source protocol is AGPL-3.0. This script is open source as required by the open source license. Thanks to the original author @lmc999 and everyone who made the pull request for this project for their contributions.

## 使用方法

**使用脚本前请确认curl已安装**
```
wget https://raw.githubusercontent.com/RoromoriYuzu/check-stream-media/main/csm.sh
bash csm.sh
```

````bash
bash csm.sh
````

##### 只检测IPv4结果：
````bash
bash csm.sh -M 4
````

##### 只检测IPv6结果：
````bash
bash csm.sh -M 6
````

##### 指定检测的代理：
````bash
bash csm.sh -I 172.17.0.2:40000
````
配合 [warp_unlock](https://github.com/fscarmen/warp_unlock/blob/main/README.md#docker-%E8%87%AA%E5%8A%A8%E8%A7%A3%E9%94%81%E6%96%B9%E6%A1%88) 使用
##### 选择脚本语言为英文：
````bash
bash csm.sh -E
````
