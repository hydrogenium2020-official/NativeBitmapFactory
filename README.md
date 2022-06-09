# 说明
增加了64位支持的https://github.com/bilibili/NativeBitmapFactory 仅仅去掉了armv5（armeabi），变量类型`uint32_t`->`uint64_t`，加入64编译就可

参考资料 https://hub.fastgit.xyz/bilibili/NativeBitmapFactory/issues/1
# 使用方法
Linux 
`NDK目录\ndk-build` 就可以了