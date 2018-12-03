# HW7
----------------------------------------
## apache log�Oapache web server����x��
### �Ьd��` curl `��` wget `���Ϊk��A�Ψ䤤�@�ӫ��O�U������x�ɡC
#### �ڨϥΪ���` wget `���O�C
* ���U���w��` wget `�C
  > ` yum -y install wget `

![image](1)


##### **�A�ӰO�o�������@��ϥΪ̨��� �èϥΤ@��ϥΪ̨����ާ@**
* �U����x�ɡC
  > ` wget https://raw.githubusercontent.com/ogre0403/107-1-ntcu-linux/master/resource/web.log `

![image](2)


### �ϥ�bash��pipe���O�A�Ҧp` grep ` �B ` cat `...�����A�N����x��error�o�ͪ���]��X�ܿù��A����L��T���ݭn�e�{�C
* **�ѩ�U�b��x�ɪ���m�x�s��` web.log `�A�ҥH�n�q` web.log `�����T�C**
* �Q��` cat web.log | grep error `��Xerror�A�ñN�o�ͤ���]��X�ܿù�(��L��T���|�X�{)�C

![image](3)


----------------------------------------
## ` tar `�Olinux�U�Ψӥ��]���Y�ؿ����u��A�Цۦ�d��` tar `���Ϊk��A��` �@��ϥΪ� `�������]�����Y` /var `�ؿ��C�b` tar `����L�{���A�������`��X���G�A���ݱN���~�T����X��` tar-err.log `�ɮסC
* ��J���O` tar -jcv -f filename.tar.bz2 /var 2> tar-err.log `�A�N` /var `���ؿ����]�����Y��A�ñN�зǿ��~��X�ɤJ` tar-err.log `���ɮפ��C
  > -j:�z�L bzip2 ���䴩�i�����Y/�����Y�A���ɦW��` .tar.bz2 `�C

  > -c:�إߥ��]�ɮסA�i�f�t` -v `�ӹ�ݹL�{���Q���]���ɦW(filename)�C

  > -v:�b���Y/�����Y���L�{���A�N���b�B�z���ɦW��ܥX�ӡC

  > -f filename:-f �᭱�n�ߨ豵�n�Q�B�z���ɦW�C

![image](4)


* �Q��` cat tar-err.log `�Ntar-err.log�ɮפ��e��X�ܿù��C

![image](5)

![image](6)


-----------------------------------------
##### �ɥR
* curl�Mwget���O��ΨӤU�������ɮת����O�A���L�̪��t�O���Z�n�_���A�ҥH�N�d�F�@�Uı�o�٤������ѻ����b�ɥR�������C
* curl�Mwget��̶��̤j���t�O:


   curl �� Library �������A�ҥH�A�i�H��K�{���Q�� curl �ӷ� HTTP Client �ΡA�� Wget �N�O�ӳ�ª��R�O�C�{���A�S���{���w�����A�������~�A�A�ӡA�j���N�O curl �䴩��h����s��������w (Protocol)�A �]���Acurl �i�H�U�������������N�� Wget�Ӫ��h�A�٦��Acurl �x��䴩���@�~�t�Τ�Wget�h�ܦh�C


   ���L�A�o�ä����Wget�S��curl�n��!Wget���@�ӳ̧Q�`�M�̤�K���A�ӴN�O�i�H���j�����U���ɡA�N�OWget�i�H�۰ʥh����Ӹ�Ƨ����ɮסA�M��A�⥦�̭����l��Ƨ��M�l�l��Ƨ����ɮ׳����U���U�ӡA�ҥH�A�� Wget�ӧ�FTP��HTTP���W���Y�Ӹ�Ƨ����Ҧ��ɮ׬O�ܤ�K����!


* �ӷ�: <https://www.arthurtoday.com/2015/01/what-is-the-different-between-curl-and-wget.html>
 