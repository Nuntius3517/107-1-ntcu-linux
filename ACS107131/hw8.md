## �Ш̻��������U�C�ާ@��������������������z�L�����ۤ����q�G    
    
## *�bVirtalBox���إߤ@�ӷs��Host-only �����d�A���q��192.168.100.1/24    
    
#### �I�D�������޲z���A�إ߷s�������d�A���q��192.168.100.1/24    
![1](https://github.com/edmundabc/107-1-ntcu-linux/blob/HW-8/ACS107131/1.PNG?raw=true)    
     
## *�إߵ�������-1�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-1��������192.168.100.100/24       
    
#### �إߵ�������1     
#### ip address add 192.168.100.100/24 broadcast + dev enp0s3     
#### ip address show enp0s3 �ˬd    
![2](https://github.com/edmundabc/107-1-ntcu-linux/blob/HW-8/ACS107131/2.PNG?raw=true)    
![4](https://github.com/edmundabc/107-1-ntcu-linux/blob/HW-8/ACS107131/4.PNG?raw=true)    
## *�إߵ�������-2�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-2��������192.168.100.200/24   
   
#### �إߵ�������2    
#### ip address add 192.168.100.200/24 broadcast + dev enp0s3     
#### ip address show enp0s3 �ˬd    
![3](https://github.com/edmundabc/107-1-ntcu-linux/blob/HW-8/ACS107131/3.PNG?raw=true)   
![5](https://github.com/edmundabc/107-1-ntcu-linux/blob/HW-8/ACS107131/5.PNG?raw=true)    
## *�N�G�x���������������]�w�s��/etc/sysconfig/network-scripts/�U�۹�����ifcfg-*�ɮסA���s�Ұʵ��������A�T�{����ip�]�w�L�~�C     
       
#### vi /etc/sysconfig/network-scripts/ifcfg-enp0s3   
![6](https://github.com/edmundabc/107-1-ntcu-linux/blob/HW-8/ACS107131/6.PNG?raw=true)   
![7](https://github.com/edmundabc/107-1-ntcu-linux/blob/HW-8/ACS107131/7.PNG?raw=true)   
#### i ��鷺�e    
#### �N onboot �令 yes    
#### :w �x�s     
#### :q ���}    
   
## *�q��������-1 ping ��������-2�T�{�����O�s�q�A�ñq��������-2 ping ��������-1�A�T�{�����]�O�s�q�C
     
#### ��������1 ping 192.168.100.100    
#### ��������2 ping 192.168.100.200    
#### ��ӵ��������n�P�ɦb�}�Ҫ��A     
![8](https://github.com/edmundabc/107-1-ntcu-linux/blob/HW-8/ACS107131/8.PNG?raw=true)     