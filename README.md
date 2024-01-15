## 调试
- sudo lsmod | grep hello
- sudo insmod hello-1.ko
- sudo rmmod hello_1
- sudo journalctl --since "1 hour ago" | grep kernel

## 参考资料
- https://sysprog21.github.io/lkmpg/
