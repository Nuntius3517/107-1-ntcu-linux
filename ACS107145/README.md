#1

1.������u��i�J����u��,�A�����W�����إ�,�إ߷s�������d,�M������W�������e,��鷺�e��192.168.100.1/24<br>
2.��ip address add 192.168.100.100/24 broadcast + dev enp0s8 �]�w��������1������,�å�ip a�ݬO�_���\�C��ip address add 192.168.100.200/24 broadcast + dev enp0s8 �]�w��������2������,�å�ip a�ݬO�_���\�C<br>
3.�� vi /etc/sysconfig/network-scripts/ifcfg-* �i�J�ɮסA�N ONBOOT=no �令 ONBOOT=yes,�[�J IPADDR=192.168.100.200 �ܵ��������@,�[�J IPADDR=192.168.100.100 �ܵ��������G,�T�{����ip�]�w�L�~�C<br>
4.�� ping 192.168.100.200 �T�{��������1�P��������2���s�u,�A�� ping 192.168.100.100 �T�{��������2�P��������1���s�u�C<br>






![](https://github.com/percy890713/107-1-ntcu-linux/blob/HW-8/ACS107145/HW8-1.PNG)
![](https://github.com/percy890713/107-1-ntcu-linux/blob/HW-8/ACS107145/HW8-2.PNG)
![](https://github.com/percy890713/107-1-ntcu-linux/blob/HW-8/ACS107145/HW8-3.PNG)