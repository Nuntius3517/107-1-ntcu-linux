## �Ш̻��������U�C�ާ@��������������������z�L�����ۤ����q�G
### �bVirtalBox���إߤ@�ӷs��Host-only �����d�A���q��192.168.100.1/24

### �إߵ�������-1�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-1��������192.168.100.100/24

```
ip address add 198.168.100.100/24 broadcast + dev enp0s8 (������root)
ip address show enp0s8 (�d��)
```


### �إߵ�������-2�A�ñҥ�host-only�����d�A�z�Lifconfig �� ip���O�A�]�w��������-2��������192.168.100.200/24

```
ip address add 198.168.100.200/24 broadcast + dev enp0s8 (������root)
ip address show enp0s8 (�d��)
```


### �N�G�x���������������]�w�s��/etc/sysconfig/network-scripts/�U�۹�����ifcfg-*�ɮסA���s�Ұʵ��������A�T�{����ip�]�w�L�~

```
vi /etc/sysconfig/network-scripts/ifcfg-enp0s8 (�]�w��ӵ��������������ɮ�)
reboot (���Ҿ���)
ip address show enp0s8 (�d��)
```




### �q��������-1 ping ��������-2�T�{�����O�s�q�A�ñq��������-2 ping ��������-1�A�T�{�����]�O�s�q

```
��������1 ping 192.168.100.200
��������2 ping 192.168.100.100
```


