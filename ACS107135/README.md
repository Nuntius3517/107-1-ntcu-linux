### 1.apache log�Oapache web server����x��<br>

#### �Ьd�� curl �� wget ���Ϊk��A�Ψ䤤�@�ӫ��O�U������x�ɡC<br>

#### �ϥ�bash��pipe���O�A�Ҧpgrep�Bcat...�����A�N����x��error�o�ͪ���]��X�ܿù��A����L��T���ݭn�e�{<br>
##### ��curl -o [�ɦW] [URL] �U������x�ɡC<br>
##### cat [�ɦW] | grep error �u��Xerror�o�ͪ���]�C<br>
![image](https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-7/ACS107135/photo/1.PNG)<br>
### 2.tar�Olinux�U�Ψӥ��]���Y�ؿ����u��A�Цۦ�d��tar���Ϊk��A�Τ@��ϥΪ̨������]�����Y/var�ؿ��C�btar����L�{���A�������`��X���G�A���ݱN���~�T����X��tar-err.log�ɮסC<br>
##### tar -c -f [�ɦW.tar] [�ؼи�Ƨ�] 2> tar-err.log<br>
�Ѽ�[-c]���إߥ��]�ɮ�<br>
[2>]���H�л\���覡�N�u���~���T���v��X����w���ɮשθ˸m�W<br>
##### cat tar-err.log <br>
![image](https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-7/ACS107135/photo/2.PNG)<br>
![image](https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-7/ACS107135/photo/3.PNG)<br>
