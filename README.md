# 借助 GitHub Actions 的 OpenWrt 在线自动编译.

### 固件发布:
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/fabian4/Actions-OpenWrt-AX6000?label=固件下载)](https://github.com/fabian4/Actions-OpenWrt-AX6000/releases/latest)

#### 固件源码来源
- openwrt-[openwrt/openwrt](https://github.com/openwrt/openwrt).
```bash
git clone -b master --single-branch https://github.com/openwrt/openwrt
```

- hanwckf-[hanwckf/immortalwrt-mt798x](https://github.com/hanwckf/immortalwrt-mt798x).
```bash
git clone -b openwrt-21.02 --single-branch https://github.com/hanwckf/immortalwrt-mt798x
```

#### Redmi AX6000 不死uboot
- [hanwckf大佬uboot地址](https://github.com/hanwckf/bl-mt798x/releases/latest) (自用方案)
    ```shell
  ➜  Actions-OpenWrt-AX6000 md5sum uboot/mt7986_redmi_ax6000-fip-fixed-parts.bin
  7610a1722073748c3c3a860b75d94d5d  uboot/mt7986_redmi_ax6000-fip-fixed-parts.bin
  ```
- [红米ax6000刷不死uboot](https://blog.w2aa.ga/post/ax6000-uboot.html).

### 固件初始配置
- 默认管理IP:`192.168.100.1`
- 用户名:`root`
- 密码:`设置首次登录后台密码为空（进入openwrt后自行修改密码）`
