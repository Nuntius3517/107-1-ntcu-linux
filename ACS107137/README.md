## �Ш̻��������U�C�ާ@��������������������z�L�����ۤ����q�G<br>
### �bVirtalBox���إߤ@�ӷs��Host-only �����d�A���q��192.168.100.1/24<br>
![image](https://github.com/bill0330/107-1-ntcu-linux/blob/HW-8/ACS107137/img/1.PNG?raw=true)<br>
### �إߵ�������-1�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-1��������192.168.100.100/24<br>

```
ip address add 198.168.100.100/24 broadcast + dev enp0s8 (������root)
ip address show enp0s8 (�d��)
```
![image](https://github.com/bill0330/107-1-ntcu-linux/blob/HW-8/ACS107137/img/2.PNG?raw=true)<br>
![image](https://github.com/bill0330/107-1-ntcu-linux/blob/HW-8/ACS107137/img/3.PNG?raw=true)<br>

### �إߵ�������-2�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-2��������192.168.100.200/24<br>

```
ip address add 198.168.100.200/24 broadcast + dev enp0s8 (������root)
ip address show enp0s8 (�d��)
```
![image](https://github.com/bill0330/107-1-ntcu-linux/blob/HW-8/ACS107137/img/4.PNG?raw=true)<br>
![image](https://github.com/bill0330/107-1-ntcu-linux/blob/HW-8/ACS107137/img/5.PNG?raw=true)<br>

### �N�G�x���������������]�w�s��/etc/sysconfig/network-scripts/�U�۹�����ifcfg-*�ɮסA���s�Ұʵ��������A�T�{����ip�]�w�L�~<br>

```
vi /etc/sysconfig/network-scripts/ifcfg-enp0s8 (�]�w��ӵ��������������ɮ�)
reboot (���Ҿ���)
ip address show enp0s8 (�d��)
```
![image](https://github.com/bill0330/107-1-ntcu-linux/blob/HW-8/ACS107137/img/6.PNG?raw=true)<br>
![image](https://github.com/bill0330/107-1-ntcu-linux/blob/HW-8/ACS107137/img/7.PNG?raw=true)<br>
![image](https://github.com/bill0330/107-1-ntcu-linux/blob/HW-8/ACS107137/img/8.PNG?raw=true)<br>
![image](https://github.com/bill0330/107-1-ntcu-linux/blob/HW-8/ACS107137/img/9.PNG?raw=true)<br>
### �q��������-1 ping ��������-2�T�{�����O�s�q�A�ñq��������-2 ping ��������-1�A�T�{�����]�O�s�q<br>

```
��������1 ping 192.168.100.200
��������2 ping 192.168.100.100
```
![image](https://github.com/bill0330/107-1-ntcu-linux/blob/HW-8/ACS107137/img/10.PNG?raw=true)<br>
![image](https://github.com/bill0330/107-1-ntcu-linux/blob/HW-8/ACS107137/img/11.PNG?raw=true)<br>

