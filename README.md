# 借助 GitHub Actions 的 OpenWrt 在线自动编译.

### 固件发布:
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/fabian4/Actions-OpenWrt-AX6000?label=固件下载)](https://github.com/fabian4/Actions-OpenWrt-AX6000/releases/latest)

#### 固件源码来源
- [hanwckf/immortalwrt-mt798x](https://github.com/hanwckf/immortalwrt-mt798x).

#### Redmi AX6000 uboot
- [hanwckf/bl-mt798x](https://github.com/hanwckf/bl-mt798x)
- 20241115 [mt7986_redmi_ax6000-fip-fixed-parts-multi-layout.bin](./bin/mt7986_redmi_ax6000-fip-fixed-parts-multi-layout.bin)

    ```shell
    ➜  md5sum bin/mt7986_redmi_ax6000-fip-fixed-parts-multi-layout.bin
    99aff09b86fb427eda41bc358aa4992e  bin/mt7986_redmi_ax6000-fip-fixed-parts-multi-layout.bin
    ```

### 固件初始配置
- 默认管理IP:`192.168.100.1`
- 用户名:`root`
- 密码:`设置首次登录后台密码为空（进入openwrt后自行修改密码）`
