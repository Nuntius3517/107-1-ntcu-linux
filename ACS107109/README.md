# HW6
-----------------------------------------
## �Цb�a�ؿ��U��` .bashrc `�̷s�W�@��shell�ܼ�` HOSTS_PATH=/etc/hosts `�A(�`�N���ݥ�export)�A�����p�󤣵n�X��` HOSTS_PATH `�ܼƥͮġA����` cat $HOST_PATH `�T�{��Ū�����ɮפ��e�C
* �b�a�ؿ��U��` .bashrc `�̷s�W�@��shell�ܼ�` HOSTS_PATH=/etc/hosts `
  * ` vim .bashrc `�C
   > �i�J��ϥνs��Ҧ��C
  * �b�̥���s�Wshell�ܼ�` HOSTS_PATH=/etc/hosts `�C
   > �x�s�����}�C


![image](1)


* �p�󤣵n�X��` HOST_PATH `�K�J�ͮ�?
  * ��J` source .bashrc `�i���εn�X�Y�iŪ�즹�s���]�w�C
   > �ϥ�` echo $HOSTS_PATH `�T�{�C
  * ����` cat $HOSTS_PATH `�T�{��Ū�����ɮפ��e�C


![image](2)


-----------------------------------------
## �bC�y���{���i�H��getenv()Ū��LINUX�������ܼơA�d�ҵ{���p�U�C�ЦbLinux�̽sĶ���d�ҵ{���ð���A�аݧ_��Ū��HOSTS_PATH�H��$?���Ȭ���A�л����C�]�\�ݳz
�Lyum groupinstall "Development Tools"�w��gcc�C
* �w��gcc�C
  > ` yum groupinstall "Development Tools" `�C


![image](3)


* �sĶ�d�ҵ{���C
  > ` vim test.c `�C
  > >�i�J��ϥνsĶ�Ҧ��C

  > �x�s�����}�C


![image](4)


* ����d�ҵ{���C
  > ` gcc test.c `�C

  > ` ./a.out `�C
  

* ���LŪ��` HOSTS_PATH ` �� ` $? `���Ȭ���?
  * �S��Ū��` HOSTS_PATH `���ȡC
   > getenv() return NULL�C

  * ` $? `���Ȭ�1�C(**���~**)
    > ` echo $? `�C


![image](5)

----------------------------------------
## �b.bashrc�̭n�p��ץ��A��C�y���{���i�HŪ�������ܼƨñN�ɮפ��e��ܡC


* �i�J` .bashrc `���ץ��C
  > ` vim .bashrc `�C

* �b�쥻��` HOSTS_PATH `�[�W**export**�C
  > `export HOSTS_PATH `�C

  > �x�s�����}�C


![image](6)


* **�O�o�n�ϥ� `source HOSTS_PATH `���ܼƥͮġC**
* ����test.c�C
  > ` gcc test.c `�C

  > ` ./a.out�C

* �Y�iŪ�������ܼƨñN�ɮפ��e��ܡC
  > �p�ϡC

* $?���Ȭ�0�C(**�L�~**)
  > ` echo $? `�C
  

![image](7)