# fio-cdm
fioでCrystalDiskMarkっぽい計測を行うコマンド

## Usage

```
fio-cdm <path>
```

### sample

```
# curl -s https://raw.githubusercontent.com/CloudRemix/fio-cdm.git-fix-version-/master/fio-cdm | sh /dev/stdin /var/tmp/
|      | Read(MB/s)|Write(MB/s)|
|------|-----------|-----------|
|  Seq |   1032.847|    208.667|
| 512K |    818.938|    173.015|
|   4K |     19.189|      4.089|
|4KQD32|     20.238|      4.088|
```

## 参考
* [LinuxのI/OベンチマークでCrystalDiskMarkと同等の計測をfioで実現 - WinKey](http://www.winkey.jp/article.php/20110310142828679)
