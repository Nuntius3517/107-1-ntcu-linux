1.�I��k�W�誺����u��A�i�J����إߺ��d�A�bIPV4��}��J192.168.100.100�A�Y�i�����C

2.�إߤ@�ӵ�������abc�A�b�]�w�ȤW��ܱҥ�host-only�����d
  �w�˧�������A��Jifconfig enp0s8 192.168.100.100�A�A��Jifconfig�A�p�ϩҥ�
  �A�إߤ@�ӵ�������def�A�b�]�w�ȤW��ܱҥ�host-only�����d
  �w�˧�������A��Jifconfig enp0s8 192.168.100.200�A�A��Jifconfig,�Y�i����
##ifconfig�ݨƥ��U��yum install net-tools

3. (abc��������)vi /etc/sysconfig/network-scripts/ifcfg-*
   ��ONBOOT=yes(no��yes)�A�s�Wip��}IPADDR=192.168.100.100
   (def��������)vi /etc/sysconfig/network-scripts/ifcfg-*
   ��ONBOOT=yes(no��yes)�A�s�Wip��}IPADDR=192.168.100.200

4.***�q��������-1 ping ��������-2�T�{�����O�s�q�A�ñq��������-2 ping ��������-1�A�T�{�����]�O�s�q�C
�babc���������W��J
ping 192.168.100.200
�bdef���������W��J
ping 192.168.100.100
�T�{�����O�_���q
