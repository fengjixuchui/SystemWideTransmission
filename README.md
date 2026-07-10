# SystemWideTransmission
## 系统全局变速

- 原理 : 劫持内核态计数器函数指针，篡改返回值以实现全局变速

- Principle : By hijacking the function pointer of the kernel‑mode counter and altering its returned value, global system‑wide speed adjustment is accomplished.

> 支持的系统 : Windows 8 ~ 11

> Supported systems : Windows 8 ~ 11

**警告 : 变速会使系统变得不稳定**
__(建议仅在虚拟机中使用)__

**WARNING : Speed changes may render the system unstable.**
__(It is recommended to use this only in a virtual machine.)__

- 在控制台中执行SystemWideTransmissionClient.exe, 查看用法 : 
```
        -speedup <ULONG>   加速 <ULONG> 倍

        -slowdown <ULONG>  减速 <ULONG> 倍

        -close             重置速度
```

- Run SystemWideTransmissionClient.exe in the console to view usage:
```
        -speedup <ULONG>   Speed up by <ULONG> times

        -slowdown <ULONG>  Slow down by <ULONG> times

        -close             Reset speed
```
