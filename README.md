# Linux 相关

## Linux DD Windows Server 2022 Datacenter

```bash
wget -qO- inst.sh|bash -s - -p vda -w Adm1nH4ckChina -n xxx.xxx.xxx.xxx,255.255.255.0,xxx.xxx.xxx.1 -t https://dl.lamp.sh/vhd/zh-cn_win2022.xz
```
## Ubuntu 24.04.2 LTS
```bash
wget -qO- inst.sh|bash -s - -p vda -w Adm1nH4ckChina -t https://down.idc.wiki/Image/realServer-Template/2025-02-03/qcow2/ubuntu24.qcow2
```
## Ubuntu 20.04.2 LTS
```bash
wget -qO- inst.sh|bash -s - -p vda -w Adm1nH4ckChina -t https://down.idc.wiki/Image/realServer-Template/2025-02-03/qcow2/ubuntu20.qcow2
```
## Linux DD 脚本
https://github.com/minlearn/inst
## 科技Lion
```bash
bash <(curl -sL kejilion.sh)
```
## x-ui 面板
```bash
bash <(curl -Ls https://raw.githubusercontent.com/FranzKafkaYu/x-ui/master/install.sh)
```

---


# Windows 相关

## Windows Server 2022 Datacenter
```bash
slmgr /ipk WX4NM-KYWYW-QJJR4-XV3QB-6VM33
```
```bash
slmgr /skms kms.03k.org
```
```bash
slmgr /ato
```
## Windows 11 专业工作站版
```bash
slmgr /ipk NRG8B-VKK3Q-CXVCJ-9G2XF-6Q84J
```
```bash
slmgr /skms kms.03k.org
```
```bash
slmgr /ato
```
## 两步解决 Windows11 无法访问局域网共享
1.打开组策略，在“本地计算机策略 > 计算机配置 > 管理模板 > 网络 > Lanman 工作站”中启用“启用不安全的来宾登录”。  
2.打开组策略，在”本地计算机策略 > 计算机配置 > Windows 设置 > 安全设置 > 本地策略>安全选项”中禁用“Microsoft 网络客户端：对通信进行数字签名（始终）”。  

## 临时文件 windows更新清理
```bash
Dism.exe /online /Cleanup-Image /StartComponentCleanup
```
```bash
Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase
```


# 自动登录
```bash
control userpasswords2
```


---




# Android 相关

## Clash Meta

https://github.com/MetaCubeX/ClashMetaForAndroid



---



# Cloudflare 相关

## Cloudflare DNS API
```bash
4vasG00cOXJd7m8ht3qf-JG964mkWpfg08fY1hBN
```


---


