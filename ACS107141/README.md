# HW8

## �bVirtalBox���إߤ@�ӷs��Host-only �����d�A���q��```192.168.100.1/24```

- �I���u����u��v&gt;�u�D�������޲z���v
![](https://i.imgur.com/sQgC2dq.png)

- �I���u�إߡv&gt;�u���e�v
- �NIPv4��}�令`192.168.100.1`�A�M�Ϋ�ҥ�
![](https://i.imgur.com/wdgBZX6.png)
***

## <p>�إߵ�������-1�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-1��������`192.168.100.100/24`</p><p>�إߵ�������-2�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-2��������`192.168.100.200/24`</p>

- �إߦW��`CentOS TEST-1`�M`CentOS TEST-2`�����������A������Hroot�n�J
- ��J`yum install net-tools`
- ���O��J�H�U���O�ק�IP<p>`ifconfig enp0s8 192.168.100.100/24`</p><p>`ifconfig enp0s8 192.168.100.200/24`</p>
![](https://i.imgur.com/hFCv8pM.png)

- ��J`ifconfig enp0s8`�ˬd�O�_�ק令�\
![](https://i.imgur.com/VHNVVCY.png)
***

## �N�G�x���������������]�w�s��`/etc/sysconfig/network-scripts/`�U�۹�����`ifcfg-*`�ɮסA���s�Ұʵ��������A�T�{����IP�]�w�L�~

- ��J`vi /etc/sysconfig/network-scripts/ifcfg-enp0s8`
    > ��Ja�Bi�Bo�}�ҽs��
- �N`ONBOOT=no`�令`ONBOOT=yes`<p>�N`dhcp`�令`static`</p>
- CentOS TEST-1 ��J `IPADDR=192.168.100.100`<p>CentOS TEST-2 ��J `IPADDR=192.168.100.200`</p>
![](https://i.imgur.com/IjbGyTQ.png)
    > ���U`ESC`�ÿ�J:wq�x�s
***

## �q��������-1 ping ��������-2�T�{�����O�s�q�A�ñq��������-2 ping ��������-1�A�T�{�����]�O�s�q�C

- ���Ҩ�x������
- CentOS TEST-1��J`ping 192.168.100.200`<p>CentOS TEST-2��J`ping 192.168.100.100`</p>
![](https://i.imgur.com/qEQYUnP.png)
![](https://i.imgur.com/3S0pD9U.png)

    # �T�{�s�q!



