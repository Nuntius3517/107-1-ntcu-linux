* ���ϥ�
">" ���ϥ�
![]()
�ť|�Ӧ��t�@�إΪk

### 1.�Ш̻��������U�C�ާ@��������������������z�L�����ۤ����q�G

### �bVirtalBox���إߤ@�ӷs��Host-only �����d�A���q��192.168.100.1/24
![1](https://github.com/0905053883/107-1-ntcu-linux/blob/HW-8/ACS107134/1.PNG)
### �إߵ�������-1�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-1��������192.168.100.100/24

` ip address add 192.168.100.100/24 broadcast + dev �˸m�W�� label (�R�W) `
![2](https://github.com/0905053883/107-1-ntcu-linux/blob/HW-8/ACS107134/2.PNG)

### �إߵ�������-2�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-2��������192.168.100.200/24

` ip address add 192.168.100.200/24 broadcast + dev �˸m�W�� label (�R�W) `
![3](https://github.com/0905053883/107-1-ntcu-linux/blob/HW-8/ACS107134/3.PNG)

### �N�G�x���������������]�w�s��/etc/sysconfig/network-scripts/�U�۹�����ifcfg-*�ɮסA���s�Ұʵ��������A�T�{����ip�]�w�L�~�C

> �ϥ� ` reboot ` ���s�Ұ�
![4](https://github.com/0905053883/107-1-ntcu-linux/blob/HW-8/ACS107134/4.PNG)

### �q��������-1 ping ��������-2�T�{�����O�s�q�A�ñq��������-2 ping ��������-1�A�T�{�����]�O�s�q�C

#### ���\!!
![5](https://github.com/0905053883/107-1-ntcu-linux/blob/HW-8/ACS107134/5.PNG)