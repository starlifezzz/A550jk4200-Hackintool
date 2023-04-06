# A550JK 4200H-MacOs-Ventura

A5500JK 4200H  
CPU: I5 4200H  
GPU：HD4600  
Memory: 8G DDR3 1600Mhz  
intel 8265AC


支持版本 10.15.7-13  


upload date 2023-04-06 重新上传  
Update Opencore 0.8.8 -> OC 0.9.1
更新kext  
原无线网卡替换intel网卡  
添加ausu电源管理，键盘支持原生快捷键
增加重置nvrm，修改sip快捷功能（引导界面操作）
Disable DGpu

可支持升级Ventura，但因为ventura中删除了相关显卡驱动，请自行下载opencore-pather 进行显卡驱动修补  https://github.com/dortania/OpenCore-Legacy-Patcher 
注意： 
1. 已经删除原有win引导，请自行用efi引导软件重新建立引导  
2. 自行替换3码，不然im，App Store受影响   Way: PI ->SystemSerialNumber、MLB、SystemUUID、ROM


siri     ✅  
麦克风    ✅  
cpu变频   ✅  
蓝牙      ✅  
wifi     ✅  
有线网卡  ✅   
