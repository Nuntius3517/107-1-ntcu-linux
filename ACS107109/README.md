# HW8
-----------------------------------------
## �Ш̻��������U�C�ާ@��������������������z�L�����ۤ����q�G


### �bVirtalBox���إߤ@�ӷs��Host-only �����d�A���q��` 192.168.100.1/24 `
* �I��k�W����**�v��u��**�i�J�]�w


![image](1)


* �إߤγ]�w�s�������d
  * **1**���U���W����**�إ�**
   > VirtualBox Host-Only Ethernet Adapter #3

  * **2**�I�鷺�e
  * **3**�]�wIPv4��}��:` 192.168.100.1 `
   > �]�w����U**�M��**

  *  ���ɤW���e�{��IPv4��}�B�n��` 192.168.100.1/24 `�A**�O�o��ҥΥ���**!!


![image](2)


-----------------------------------------
### �إߵ�������-1�A�ñҥ�host-only�����d�A�z�L` ifconfig ` �� ` ip `���O�A�]�w��������-1��������` 192.168.100.100/24 `
* �إߵ�������**test1**
  > �إߤ�k:< https://github.com/YANGshujun1110/107-1-ntcu-linux/blob/HW-2/ACS107109/HW2.md >

* �}��**�]�w��**��**����**�ҥέ��s�]�w��host-only�����d


![image](3)


* **�ѩ�O���s�s�W�����������A�ҥH�n�}�Һ����d�A�æw��ifconfig�C**
  > �}�Һ����d:nmtui

  > �w��ifconfig:` yum install net-tools `
  > > ifconfig:�i�H�ΨӬd�ߡB�]�w�����d�P IP ���쵥�����ѼơC

*  �]�w��������**test1**��������` 192.168.100.100/24 `
  > ` ip address add  192.168.156.100/24 broadcast + dev enp0s3 `


![image](4)



-----------------------------------------
### �إߵ�������-2�A�ñҥ�host-only�����d�A�z�L` ifconfig ` �� ` ip `���O�A�]�w��������-2��������` 192.168.100.200/24 `
* �إߵ�������**test2**
  > �إߤ�k:< https://github.com/YANGshujun1110/107-1-ntcu-linux/blob/HW-2/ACS107109/HW2.md >

* �}��**�]�w��**��**����**�ҥέ��s�]�w��host-only�����d


![image](5)


* **�ѩ�O���s�s�W�����������A�ҥH�n�}�Һ����d�A�æw��ifconfig�C**
  > �}�Һ����d:nmtui

  > �w��ifconfig:` yum install net-tools `
  > > ifconfig:�i�H�ΨӬd�ߡB�]�w�����d�P IP ���쵥�����ѼơC

* �]�w��������**test2**��������` 192.168.100.200/24 `
  > ` ip address add  192.168.156.200/24 broadcast + dev enp0s3 `


![image](6)


-----------------------------------------
### �N�G�x���������������]�w�s��` /etc/sysconfig/network-scripts/ `�U�۹�����` ifcfg-* `�ɮסA���s�Ұʵ��������A�T�{����ip�]�w�L�~�C
* ��J` vi /etc/sysconfig/network-scripts/ifcfg-* `
  > �N�G�x���������������]�w�s��` /etc/sysconfig/network-scripts/ `�U�۹�����` ifcfg-* `�ɮ�

  * ������1:test1
![image](7)
    * ONBOOT�n�}�ҭ�!�o�˶}�򪺮ɭԴN�|�۰ʶ}�ҤF
      > ONBOOT=yes

    * �s�W����IP��}
      > IPADDR=192.168.100.100

    * �x�s���}


![image](8)


  * ������2:test2
![image](9)
    * ONBOOT�n�}�ҭ�!�o�˶}�򪺮ɭԴN�|�۰ʶ}�ҤF
      > ONBOOT=yes

    * �s�W����IP��}
      > IPADDR=192.168.100.200

    * �x�s���}


![image](10)


-----------------------------------------
### �q��������-1 ping ��������-2�T�{�����O�s�q�A�ñq��������-2 ping ��������-1�A�T�{�����]�O�s�q�C
* ������1:test1
  * ` ping 192.168.100.200 `
* ������2:test2
  * ` ping 192.168.100.100 `

![image](11)


* �P�ɰ���A�T�{�����O���q��


![image](12)