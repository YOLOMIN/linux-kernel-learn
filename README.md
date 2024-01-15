## 调试
- sudo lsmod | grep hello
- sudo insmod hello-1.ko
- sudo rmmod hello_1
- sudo journalctl --since "1 hour ago" | grep kernel
### hello-5模块的调试方式
$ sudo insmod hello-5.ko mystring="bebop" myintarray=-1
$ sudo dmesg -t | tail -7
$ sudo rmmod hello-5
$ sudo dmesg -t | tail -1

## 参考资料
- https://sysprog21.github.io/lkmpg/
