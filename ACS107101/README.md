####HW7
# �Ĥ@�D
+
+ 1.
+(1)apache log�Oapache web server����x��
+
+#�Ьd�� curl �� wget ���Ϊk��A�Ψ䤤�@�ӫ��O�U������x��
+apache log ���s�� https://raw.githubusercontent.com/ogre0403/107-1-ntcu-linux/master/resource/web.log
+
+��curl�U����ơA�A�᭱�A��grep error > error�e�{��ơC
+
+��Jcurl https://raw.githubusercontent.com/ogre0403/107-1-ntcu-linux/master/resource/web.log | grep error > out
+
+(2)
+�A��Jcat web.log | grep error
+
+�u���x��error�o�ͪ���]��X�ܿù�
+
#�ĤG�D
+
+ #tar�Olinux�U�Ψӥ��]���Y�ؿ����u��A�Цۦ�d��tar���Ϊk��A�Τ@��ϥΪ̨������]�����Y/var�ؿ��C�btar����L�{���A�������`��X���G�A���ݱN���~�T����X��tar-err.log�ɮסC
+��Jtar -jcv -f filename.tar.bz2 /var 2> tar-err.log
+
+>tar -jcv -f filename.tar.bz2�Ψ����Y�A/var�ɮצW�١A2> tar-err.log����~�T����X��tar-err.log��
+
+*��Jcat tar-err.log