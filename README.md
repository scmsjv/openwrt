## OpenWrt

<h2>.config</h2>

#### Target System----选择 x86
#### Subtarget--------选择 x86_64
#### Target Profile---选择 generic x86/64

#### Target Images
- build livecd image (iso)
- build virtualBox image (vdi)
- build vmware image files （vmdk）
- build hyper-v image files (vhdx)
- Kernel partition size           设置的1024
- Root filesystem partition size  设置的4096


#### LuCI
##### Collections
- luci-nginx
- luci-ssl-nginx
##### Applications
- luci-app-attendedsysupgrade
- luci-app-opkg

<hr/>
其他没有选择的就是默认设置
