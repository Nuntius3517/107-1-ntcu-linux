### �Ш̻��������U�C�ާ@��������������������z�L�����ۤ����q�G

## �bVirtalBox���إߤ@�ӷs��Host-only �����d�A���q��192.168.100.1/24
![image](https://github.com/acs107102/107-1-ntcu-linux/blob/master/HW8-1.JPG)

## �إߵ�������-1�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-1��������192.168.100.100/24
 *  `ip address add 198.168.100.100/24 broadcast + dev enp0s8`
![image](https://github.com/acs107102/107-1-ntcu-linux/blob/master/HW8-3.JPG)
![image](https://github.com/acs107102/107-1-ntcu-linux/blob/master/HW8-4.JPG)
![image](https://github.com/acs107102/107-1-ntcu-linux/blob/master/HW8-5.JPG)

## �إߵ�������-2�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-2��������192.168.100.200/24
 *  `ip address add 198.168.100.200/24 broadcast + dev enp0s8`
![image](https://github.com/acs107102/107-1-ntcu-linux/blob/master/HW8-6.JPG)
![image](https://github.com/acs107102/107-1-ntcu-linux/blob/master/HW8-9.JPG)


## �N�G�x���������������]�w�s��/etc/sysconfig/network-scripts/�U�۹�����ifcfg-*�ɮסA���s�Ұʵ��������A�T�{����ip�]�w�L�~�C
 *  `vi /etc/sysconfig/network-scripts/ifcfg-enp0s8`
![image](https://github.com/acs107102/107-1-ntcu-linux/blob/master/HW8-7.JPG)
![image](https://github.com/acs107102/107-1-ntcu-linux/blob/master/HW8-10.JPG)
![image](https://github.com/acs107102/107-1-ntcu-linux/blob/master/HW8-14.JPG)

## �q��������-1 ping ��������-2�T�{�����O�s�q�A�ñq��������-2 ping ��������-1�A�T�{�����]�O�s�q�C
![image](https://github.com/acs107102/107-1-ntcu-linux/blob/master/HW8-8.JPG)
![image](https://github.com/acs107102/107-1-ntcu-linux/blob/master/HW8-11.JPG)
![image](https://github.com/acs107102/107-1-ntcu-linux/blob/master/HW8-12.JPG)
![image](https://github.com/acs107102/107-1-ntcu-linux/blob/master/HW8-13.JPG)