### 1.�Ш̻��������U�C�ާ@��������������������z�L�����ۤ����q�G

#### �bVirtalBox���إߤ@�ӷs��Host-only �����d�A���q��`192.168.100.1/24`

- �b�]�w�������������d2�s�W�ȭ��D���������d

> ![GITHUB](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-8/ACS107150/1.PNG?raw=true)

- �b�ߦn�]�w��������IPv4��}�]�w��192.168.100.1 �����B�n�]�w��255.255.255.0

> ![GITHUB](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-8/ACS107150/2.PNG?raw=true)

#### �إߵ�������-1�A�ñҥ�host-only�����d�A�z�L`ifconfig` �� `ip`���O�A�]�w��������-1��������`192.168.100.100/24`

- ��Jip address add 192.168.100.100/24 broadcast + dev enp0s3

- ��Jip address show�T�{

> ![GITHUB](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-8/ACS107150/3.PNG?raw=true)

#### �إߵ�������-2�A�ñҥ�host-only�����d�A�z�L`ifconfig` �� `ip`���O�A�]�w��������-2��������`192.168.100.200/24`

- ��Jip address add 192.168.100.200/24 broadcast + dev enp0s3

- ��Jip address show�T�{

> ![GITHUB](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-8/ACS107150/4.PNG?raw=true)

#### �N�G�x���������������]�w�s��`/etc/sysconfig/network-scripts/`�U�۹�����`ifcfg-*`�ɮסA���s�Ұʵ��������A�T�{����ip�]�w�L�~�C

> ![GITHUB](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-8/ACS107150/5.PNG?raw=true)

> ![GITHUB](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-8/ACS107150/6.PNG?raw=true)

#### �q��������-1 ping ��������-2�T�{�����O�s�q�A�ñq��������-2 ping ��������-1�A�T�{�����]�O�s�q�C

> ![GITHUB](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-8/ACS107150/7.PNG?raw=true)

> ![GITHUB](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-8/ACS107150/8.PNG?raw=true)