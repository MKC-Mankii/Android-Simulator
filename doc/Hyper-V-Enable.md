
按照docker的报错提示

![image](https://github.com/user-attachments/assets/888802e3-cd5f-4e6d-9a6f-07fbecb8cf55)

打开
[https://docs.docker.com/desktop/troubleshoot/topics/#virtualization](https://docs.docker.com/desktop/troubleshoot/topics/#virtualization)

找到Hyper-V的部分照做即可。

![image](https://github.com/user-attachments/assets/e082161f-5be0-4de0-93d0-4883077d1b3b)

上面步骤做完后如果还不行。试试下面步骤先禁用再启用

管理员打开PS或者CMD
用下面命令关闭
bcdedit /set hypervisorlaunchtype off

再用下面命令启用
bcdedit /set hypervisorlaunchtype auto
dism.exe /Online /Enable-Feature:Microsoft-Hyper-V /All

