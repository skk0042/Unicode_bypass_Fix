# 进入你的内核源码根目录使用以下命令
cd kernel-android16-6.12/common

# 打补丁命令
patch -p1 < unicode_bypass_fix_xxx.patch

# 更新补丁
请使用新的修复patch,此前修复的方法是错误的，会破坏正常功能!
目前采用钱钱@realaviraxp 正确的修复方法来修复漏洞.
警告：这个补丁会造成文件查找性能下降! 请酌情考虑后再进行Patch
