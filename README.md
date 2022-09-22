# arp-spoof
arp 欺骗工具源码，不可用于非法用途

## 安装使用

**安装依赖包**
```
pip install -r 
```

**修改mian.py源码里的地址**
```
    # 目标IP
    target = "192.168.12.217"
    # 网关IP
    host = "192.168.12.1"
```

**运行**
```
pyhton3 main.py
[+] Sent to 192.168.12.1 : 192.168.12.22 is-at d0:x:x:x:x:x
[+] Sent to 192.168.12.1 : 192.168.12.22 is-at d0:x:x:x:x:x
[+] Sent to 192.168.12.1 : 192.168.12.22 is-at d0:x:x:x:x:x
```
