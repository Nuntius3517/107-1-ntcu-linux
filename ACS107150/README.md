### 1. [apache log](https://raw.githubusercontent.com/ogre0403/107-1-ntcu-linux/master/resource/web.log)�Oapache web server����x��

#### �Ьd��`curl`��`wget`���Ϊk��A�Ψ䤤�@�ӫ��O�U������x�ɡC
#### �ϥ�bash��pipe���O�A�Ҧp`grep`�B`cat`...�����A�N����x��error�o�ͪ���]��X�ܿù��A����L��T���ݭn�e�{�C

- ������curl <�n�U�������}> | grep error > <�ɮצW��>
	
- cat <�ɮצW��>

> ![image](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-7/ACS107150/1.PNG?raw=true)

### 2. `tar`�Olinux�U�Ψӥ��]���Y�ؿ����u��A�Цۦ�d��`tar`���Ϊk��A�Τ@��ϥΪ̨������]�����Y`/var`�ؿ��C�b`tar`����L�{���A�������`��X���G�A���ݱN���~�T����X��`tar-err.log`�ɮסC

- ��tar -jcv -f filename.tar.bz2 /var 2> tar-err.log�N���~�T����X��tar-err.log

- cat tar-err.log

- (�]�����~�T���L�h�A�ҥH�u�e�{�������G�C)

> ![image](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-7/ACS107150/2.PNG?raw=true)