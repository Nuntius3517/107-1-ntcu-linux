�Ĥ@�D

-��Jwget https://raw.githubusercontent.com/ogre0403/107-1-ntcu-linux/master/resource/web.log���J���
-cat web.log | grep error
-���G�p�ϩҥ�

�ĤG�D

--c  �G�إߥ��]�ɮסA�i�f�t -v �ӹ�ݹL�{���Q���]���ɦW(filename)
--j  �G�z�L bzip2 ���䴩�i�����Y/�����Y�G�����ɦW�̦n�� *.tar.bz2
--v  �G�b���Y/�����Y���L�{���A�N���b�B�z���ɦW��ܥX�ӡI
�ϥΤ覡:
���@�Y�Gtar -jcv -f filename.tar.bz2 �n�Q���Y���ɮשΥؿ��W��

--��Jtar -jcv -f filename.tar.bz2 /var 2> tar-err.log
--cat tar-err.log