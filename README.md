# 进入你的内核源码根目录使用以下命令
cd kernel-android16-6.12/common

# 打补丁命令
patch -p1 < unicode_bypass_fix_xxx.patch

# 说明
设备内核是6.1以下的需要加unicode_bypass_fix2这个补丁，也就是需要加入两个补丁，你是"6.1 6.6 6.12" 设备内核只用加第一个unicode_bypass_fix5.10-6.12通用补丁就可以了

# 警告！
请使用新的修复patch,之前的修复方法是错误的，会破坏正常功能!
目前采用钱钱@realaviraxp 正确的修复方法来修复漏洞
警告：这个补丁会造成文件查找性能下降! 请酌情考虑后再进行Patch
