## HW7

1. apache log�Oapache web server����x��

+ �Ьd�� curl �� wget ���Ϊk��A�Ψ䤤�@�ӫ��O�U������x�ɡC
+ �ϥ�bash��pipe���O�A�Ҧpgrep�Bcat...�����A�N����x��error�o�ͪ���]��X�ܿù��A����L��T���ݭn�e�{�C
  + ��curl�U����ơA�A�᭱�A��grep error > error�e�{��ơC
![GITHUB](https://imgur.com/6LHXYsY.jpg"git�ϥ�")

2. tar�Olinux�U�Ψӥ��]���Y�ؿ����u��A�Цۦ�d��tar���Ϊk��A�Τ@��ϥΪ̨������]�����Y/var�ؿ��C�btar����L�{���A�������`��X���G�A���ݱN���~�T����X��tar-err.log�ɮסC

   + ��J���Otar -cvjpf filename.tar.bz2 /var 2> tar-err.log�C
![GITHUB](https://imgur.com/LqxmEnV.jpg"git�ϥ�")
   
    + �A��cat tar-err.log�N���~��ƿ�X�C
![GITHUB](https://imgur.com/7mbfsM0.jpg"git�ϥ�")