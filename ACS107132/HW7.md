##�@.

#�Ьd�� curl �� wget ���Ϊk��A�Ψ䤤�@�ӫ��O�U������x�ɡC

#�ϥ�bash��pipe���O�A�Ҧpgrep�Bcat...�����A�N����x��error�o�ͪ���]��X�ܿù��A����L��T���ݭn�e�{�C

* �ϥ�man�i�H�d�ݫ��O�Ϊk

1. (�ڨϥ�curl){{{curl https://raw.githubusercontent.com/ogre0403/107-1-ntcu-linux/master/resource/web.log | grep error}}}
+ �ϥ�{{{crul -s}}}�i�H����ܶi�{

* [����1]�Ϥ���ܨS���ϥ�{-s}�򦳨ϥΪ��t��

##�G.

#�Τ@��ϥΪ̨������]�����Y/var�ؿ��C�btar����L�{���A�������`��X���G�A���ݱN���~�T����X��tar-err.log�ɮסC

1. {{{tar -jvc -f file.tar.bz2 /var 2> tar-err.log}}} [����2]
+ �N/var���ؿ����]���Y�A�ñN���~�T����X��tar-err.log
2. {{{cat tar-err.log}}} [����3]
+ �N���~��ƿ�X
