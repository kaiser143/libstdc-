# libstdc++
`Xcode 10`之后删除的`libstdc++`库

1. 先下载下来这个项目，然后打开终端`cd`到`libstdc--master`文件夹；
2. 如果你使用的是 Xcode 10，则将`install-Xcode_10.sh`拖到终端中执行即可。
3. Xcode 11 版则将`install-Xcode_11+.sh`拖到终端中执行。


PS.针对本地有多个版本的SDK，需要把目录1下的动态库拷贝到指定文件夹下
/Library/Developer/CoreSimulator/Profiles/Runtimes/`iOS 13.6.simruntime`/Contents/Resources/RuntimeRoot/usr/lib
