# 1.

## �إߤT�ӥΤ�A�b���W�٤��O���G examuser1, examuser2, examuser3 �A�P�ɤT�ӥΤ᪺�K�X���O�y ItIsExam �z�C

> ��useradd �b���W�� �s�W�Τ�

> ��passwd �b���W�� �s�W�Τ�K�X

> �X�{new password�N��J�K�X

> �X�{retype new password�A��J�@���K�X

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/1.PNG?raw=true)

> ��ll /home�T�{�O�_�s�W���\

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/2.PNG?raw=true)

## �ЧR���t�Τ��� examuser3 �o�ӱb���A�P�ɱN�o�ӱb�����a�ؿ��P�l���ɮצP�B�R���C

> ��userdel -r examuser3�R���b��(�[-r���a�ؿ��M�l���ɮצP�B�R��)

> ��ll /home�T�{�O�_�R��

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/3.PNG?raw=true)

## examuser1 ���p�߳Q�޲z���R���F�A���O�o�ӱb�����a�ؿ��P�����l���٦s�b�C�аѦҳo�ӱb���i�઺�a�ؿ��ҫO�d�� UID �P GID�A �ù��եH�ӱb���즳�� UID/GID ��T�ӭ��ظӱb���C�ӳo�ӱb�����K�X�е��� ItIsExam ���˦��C

> ��userdel examuser1�R���b��

> ��ll /home�T�{�O�_�R��

> �o�{�쥻examuser1�ܦ�1001,�i��1001�Oexamuser1��id

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/4.PNG?raw=true)

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/5.PNG?raw=true)

> ��useradd -u 1001 -U examuser1�s�W�b��

> ��ll /home�T�{�O�_�_��

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/6.PNG?raw=true)

# 2.

## �إ�examuser4�ϥΪ̱b���A�K�X���N�C

> ��useradd examuser4�Mpasswd examuser4�s�W�b��

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/7.PNG?raw=true)

## �ϥ� root �N /etc/securetty �ƻs�� examuser4�A�B�o�ӱb���n�������ϥθ��ɮפ~��A(�Y���Ҧ����v��)�C
 
> ��cd /etc/securetty /home/examuser4���ɮ׽ƻs�L�h

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/8.PNG?raw=true)

> ��ll /etc/securetty�Mll /home/examuser4�T�{�O�_�ƻs���\

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/9.PNG?raw=true)

> �]��examuser4���Oroot�]���broot���s�ո�,�ҥHexamuser4�ݩ�other

> ��chmod o=rwx /home/examuser4/securetty�}��other���v��

> ��ll /home/examuser4/securetty�T�{�O�_���\�����v��

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/10.PNG?raw=true)

## �إߤ@�ӦW�� /examdata/change.txt �����ɮסA�o���ɮת��֦��̬� sshd�A�֦��s�լ� users�Asshd �iŪ�i�g�Ausers �s�զ����iŪ�A ��L�H�S�v���C�B�o���ɮת��ק����нվ㦨 2012 �~ 12 �� 21 �� (������T�Y�i�A�ɶ��H�K)

> ��cd /�i�J�ڥؿ�

> ��mkdir examdata�Ыإؿ�

> �Acd examdata�i�Jexamdata�o�ӥؿ�

> touch change.txt�Ы��ɮ�

> ��ll�T�{�O�_���\

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/11.PNG?raw=true)

> ��chown sshd change.txt��o���ɮת��֦��̧אּsshd

> ��chgrp users change.txt��o���ɮת��s�էאּusers

> ��ll���լO�_�令�\

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/12.PNG?raw=true)

> ��chmod u=rw,g=r,o-r change.txt��o���ɮת��v���令rw-r-----

> ��ll�T�{

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/13.PNG?raw=true)

> ��touch -t �ɶ�(ex.201212211715) change.txt���̷ܳs�����

> ��ll�T�{

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/14.PNG?raw=true)

# 3.

## �Шϥ� root �������إߩ��U���ɮ׻P�v���G

drwxrwxr-x  root root /dev/shm/unit05/
drwxr-xr--  root root /dev/shm/unit05/dir1/
-rw-r--r--  root root /dev/shm/unit05/dir1/file1 (�ƻs�Ӧ� /etc/hosts)
drwxr-x--x  root root /dev/shm/unit05/dir2/
-rw-r--r--  root root /dev/shm/unit05/dir2/file2 (�ƻs�Ӧ� /etc/hosts)
drwxr-xr-x  root root /dev/shm/unit05/dir3/
-rw-rw-rw-  root root /dev/shm/unit05/dir3/file3 (�ƻs�Ӧ� /etc/hosts)
drwxrwxrwx  root root /dev/shm/unit05/dir4/
-rw-------  root root /dev/shm/unit05/dir4/file4 (�ƻs�Ӧ� /etc/hosts)

> ��cd /�i�J�ڥؿ�

> ��cd shm�i�Jshm

> ��mkdir unit05�Ыإؿ�

> ��cd unit05�i�Junit05

> ��mkdir dir[1-4]�Ыإؿ�dir[1-4]

> ��chmod �Ʀr dir[1-4]����dir[1-4]���v��

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/15.PNG?raw=true)

> ��touch /dev/shm/unit05/dir1/file1�зs�ɮ�

> file[2-4]�]�O�ۦP�@�k

> ��cp /etc/hosts /dev/shm/unit05/dir1/file1�ƻs�ɮר�file1

> file[2-4]�]�O�ۦP�@�k

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/16.PNG?raw=true)

> ��cd dir1�i�Jdir1

> ��chmod �Ʀr file1�����v��

> ��cd -�h�^�W�@�ӥؿ�

> file[2-4]�]�O�ۦP�@�k

> ��ll �ɮצ�} �T�{�v���O�_���ܦ��\

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/17.PNG?raw=true)

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/18.PNG?raw=true)

## �ϥΤ@��ϥΪ� �������i��U���u�@�G

> ��su examuser4��n�J�b��令examuser4

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/19.PNG?raw=true)

## �Шϥ� ls -l /dev/shm/unit05/dir[1-4] �̾ڿ�X�����G��������|���ͳo�ǰ��D�H

> ��dir[1-4]�ӻ�examuser4�Oother

> dir1�u��Ū�������,�ҥH����ܥX�Ӧ��|�X�{�@��ݸ�

> dir2����Ū,�ҥH�������

> dir3�Mdir4��Ū�]�����,�ҥH�i�H����e�{��T

> ���浲�G�p�U��

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/20.PNG?raw=true)

## �Шϥ� ls -l /dev/shm/unit05/dir1/file1 �A�̧ǱN�W�z���ɦW�� dir1/file1 ~ dir4/file4 ����A�̾ڲ��ͪ����G��������|�p���H

> ��dir[1-4]�ӻ�examuser4�Oother

> ��file[1-4]����T�ݭn��dir[1-4]����(x)���v��

> �u��dir1�S��other���檺�v��,�ҥH�S��k���;dir[2-4]�h���������v��,�ҥH��ݨ�

> ���浲�G�p�U��

![github](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-3/ACS107150/21.PNG?raw=true)

## �Шϥ� vim /dev/shm/unit05/dir1/file1 ~ vim /dev/shm/unit05/dir4/file4�A�����x�s (�αj���x�s)�A��������i�H/���i�H�x�s�H

> �s�ɻݭndir������(x)�v��,�٦�file���ק�(w)�v��

> ��dir1�S����other�����v��,�ҥH�S��k����

> dir[2-4]�h���������v��,�ҥH�����

> ��file[2-4],examuser4�Oother,file2�u��r���v��,�G�uŪ,�����x�s(�ק�)

> file3��other���v���Orw-,�ҥH��Ū�]���x�s(�ק�)

> file4��other���v���O---,�ҥH�ण��Ū�]�����x�s(�ק�)
