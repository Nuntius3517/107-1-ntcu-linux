### HW6

# apache log�Oapache web server����x��
# �Ьd�� curl �� wget ���Ϊk��A�Ψ䤤�@�ӫ��O�U������x�ɡC
# �ϥ�bash��pipe���O�A�Ҧpgrep�Bcat...�����A�N����x��error�o�ͪ���]��X�ܿù��A����L��T���ݭn�e�{�C

 * ��J```curl https://raw.githubusercontent.com/ogre0403/107-1-ntcu-linux/master/resource/web.log | grep error > out```
![](https://i.imgur.com/7XnSu2Y.png)

# tar�Olinux�U�Ψӥ��]���Y�ؿ����u��A�Цۦ�d��tar���Ϊk��A�Τ@��ϥΪ̨������]�����Y/var�ؿ��C�btar����L�{���A�������`��X���G�A���ݱN���~�T����X��tar-err.log�ɮסC

 * ��J```tar -jcv -f filename.tar.bz2 /var 2> tar-err.log```
 * ��J```cat tar-err.log```�H�d�� tar-err.log �����e 

