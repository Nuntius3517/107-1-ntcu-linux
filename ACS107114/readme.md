## HW8
### �Ĥ@�D
#### 1. �bVirtalBox���إߤ@�ӷs��Host-only �����d�A���q��192.168.100.1/24
* �إߤ@�ӷs�������d
![](https://i.imgur.com/toErw0K.png)

#### 2. �إߵ�������-1�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-1��������192.168.100.100/24
* �ϥ�`ip address add 198.168.100.100/24 broadcast + dev enp0s8` ���IP
* �A�ϥ�`ip address show enp0s8` �ˬd�O�_���\
![](https://i.imgur.com/so8gYjU.png)
 
 #### 3. �إߵ�������-2�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-2��������192.168.100.200/24
*  �ϥ�`ip address add 198.168.100.200/24 broadcast + dev enp0s8` ���IP
*  �A�ϥ�`ip address show enp0s8`�ˬd�O�_���\
![](https://i.imgur.com/6RYahGH.png)

#### 4. �N�G�x���������������]�w�s��/etc/sysconfig/network-scripts/�U�۹�����ifcfg-*�ɮסA���s�Ұʵ��������A�T�{����ip�]�w�L�~�C
*  �ϥ�`vi /etc/sysconfig/network-scripts/ifcfg-enp0s8`�d�ݭӭӪ�IP
![](https://i.imgur.com/ZRuMhi2.jpg)
