* ##  �bVirtalBox���إߤ@�ӷs��Host-only �����d�A���q��192.168.100.1/24
### �i�J����u�㤺��ܥD�������޲z���A�M����إߡA�A�����e�վ�IPv4 ��}192.168.100.1
![](https://i.imgur.com/OPMsAzC.png)
* ## �إߵ�������-1�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-1��������192.168.100.100/24
### �إߦW��net����������
![](https://i.imgur.com/Sh6c8OF.png)
### ��Jip address add 192.168.100.100/24 broadcast + dev enp0s3����ip��},�å�ip address show�T�{����
![](https://i.imgur.com/0pTPkAl.png)
* ## �إߵ�������-2�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-2��������192.168.100.200/24
### �@�˨ϥ�ip address add 192.168.100.200/24 broadcast + dev enp0s3����ip��},�å�ip address show�T�{����
![](https://i.imgur.com/dEaE8XN.png)
* ## �N�G�x���������������]�w�s��/etc/sysconfig/network-scripts/�U�۹�����ifcfg-*�ɮסA���s�Ұʵ��������A�T�{����ip�]�w�L�~�C
### ��Jvi /etc/sysconfig/network-scripts/ifcfg-,�M���JIPADDR=192.168.100.100
![](https://i.imgur.com/ZQYNOX9.png)
### ��t�@�x����������JIPADDR=192.168.100.200
![](https://i.imgur.com/NmP1oD6.png)
* ## �q��������-1 ping ��������-2�T�{�����O�s�q�A�ñq��������-2 ping ��������-1�A�T�{�����]�O�s�q�C
### ��ping 192.168.100.200�Mping 192.168.100.100�T�{�������s�q
![](https://i.imgur.com/LJHhQ0J.png)