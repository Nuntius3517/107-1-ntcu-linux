## �bVirtalBox���إߤ@�ӷs��Host-only �����d�A���q��192.168.100.1/24�C
![](https://i.imgur.com/VaX5ECd.png)
## �ϥ�ifconfig��ip���O�A�N��������-1�������]�w��192.168.100.100/24�A�N��������-2�������]�w��192.168.100.200/24
(ip address add 198.168.100.100/24 broadcast + dev enp0s3)
(ip address add 198.168.100.200/24 broadcast + dev enp0s3)
![](https://i.imgur.com/QDjxGr4.png)
## �N��������1&2�������]�w�s��/etc/sysconfig/network-scripts/�U�۹�����ifcfg-*�ɮסA���s�Ұʵ��������A�T�{����ip�]�w�L�~�C 
(vi /etc/sysconfig/network-scripts/ifcfg-enp0s3)
![](https://i.imgur.com/nIWT8MJ.png)
## �q��������-1 ping ��������-2�T�{�����O�s�q�A�ñq��������-2 ping ��������-1�A�T�{�����]�O�s�q�C
(ping 192.168.100.100)
(ping 192.168.100.200)
![](https://i.imgur.com/eXVLc5m.png)
