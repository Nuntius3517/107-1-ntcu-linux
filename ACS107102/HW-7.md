#### ���O�s��U�F�M��ƭ��y�ɦV
### ���O
## `apache log`�O`apache web server`����x��
1.  `apache log` ���s�� `https://raw.githubusercontent.com/ogre0403/107-1-ntcu-linux/master/resource/web.log`
    `curl https://raw.githubusercontent.com/ogre0403/107-1-ntcu-linux/master/resource/web.log | grep error > out`
2.  `cat out`

    ```
    [Sun Mar 7 21:16:17 2004] [error] [client 24.70.56.49] File does not exist: /home/httpd/twiki/view/Main/WebHome
    ```

### ��ƭ��y�ɦV
1. `tar`�Olinux�U�Ψӥ��]���Y�ؿ����u��A�Цۦ�d��`tar`���Ϊk��A�Τ@��ϥΪ̨������]�����Y`/var`�ؿ��C�b`tar`����L�{���A�������`��X���G�A���ݱN���~�T����X��`tar-err.log`�ɮסC
   `tar -jcv -f filename.tar.bz2 /var 2> tar-err.log`
   `cat tar-err.log`�C�L���~���