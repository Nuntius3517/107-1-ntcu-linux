#(1)
�I��i�J"����u��"�A�إ߷s�������d�A��"���e"�NIPv4��}�]�w��"192.168.100.1"�A�äĿ�"�ҥ�"�C
#(2)
�s�W�@�ӷs����������-1�A��"�]�w��"�̪�"����"�A���"�ȭ��D�������d"(�W�ٴN�O���إߪ������d)�A�w�� yum install net-tools�A���ۿ�Jip address add 192.168.100.100/24 broadcast + dev enp0s8�C
#(3)
�s�W�t�@�ӵ�������-2�A�B�J�P�W�A���ۿ�Jip address add 192.168.100.200/24 broadcast + dev enp0s8�C
#(4)
��������-1:��Jvi /etc/sysconfig/network-scripts/ifcfg-*�A���ۧ�ONBOOT=yes�A�÷s�Wip��}IPADDR=192.168.100.100�A��wq�x�s���}�C

��������-2:��Jvi /etc/sysconfig/network-scripts/ifcfg-*�A���ۧ�ONBOOT=yes�A�÷s�Wip��}IPADDR=192.168.100.200�A��wq�x�s���}�C
#(5)
��������-1:��Jping 192.168.100.200 �T�{�����O�s�q

��������-2:��Jping 192.168.100.100 �T�{�����]�O�s�q