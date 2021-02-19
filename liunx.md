# Linux

- top

    > 用于实时显示 process 的动态

- iftop

    > 类似于top的实时流量监控工具

- iperf

    > 网络性能测试工具。Iperf可以测试最大TCP和UDP带宽性能，具有多种参数和UDP特性，可以根据需要调整，可以报告带宽、延迟抖动和数据包丢失。

- cp

    > copy file 命令主要用于复制文件或目录 
    - 拷贝不覆盖原有的文件
    > awk 'BEGIN { cmd="cp -ri ./demo/* ./test "; print "n" |cmd; }'
     
- scp
    
    > scp 是 secure copy 的缩写, scp 是 linux 系统下基于 ssh 登陆进行安全的远程文件拷贝命令。
        
- rsync
    
    > 可以实现增量备份的工具。配合任务计划，rsync能实现定时或间隔同步，配合inotify或sersync，可以实现触发式的实时同步。   