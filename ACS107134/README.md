* ���ϥ�
">" ���ϥ�
![]()
�ť|�Ӧ��t�@�إΪk

### 1.apache log�Oapache web server����x��
### �Ьd�� curl �� wget ���Ϊk��A�Ψ䤤�@�ӫ��O�U������x�ɡC
### �ϥ�bash��pipe���O�A�Ҧpgrep�Bcat...�����A�N����x��error�o�ͪ���]��X�ܿù��A����L��T���ݭn�e�{�C

> * yum -y install wget �U��wget
>* wget �O�b�i��"�������"�����o�A�y�k: wget [-option] [url]

## �ϥ� ` wget https://raw.githubusercontent.com/ogre0403/107-1-ntcu-linux/master/resource/web.log `

�|���ͥX�@��web.log�ɡA�̭����Ҧ������
![1](https://github.com/0905053883/107-1-ntcu-linux/blob/HW-7/ACS107134/1.PNG)
    
�ڭ̳z�L cat web.log | grep error ���L��Xerror����T�C
![2](https://github.com/0905053883/107-1-ntcu-linux/blob/HW-7/ACS107134/2.PNG)

### 2.tar�Olinux�U�Ψӥ��]���Y�ؿ����u��A�Цۦ�d��tar���Ϊk��A�Τ@��ϥΪ̨������]�����Y/var�ؿ��C
### �btar����L�{���A�������`��X���G�A���ݱN���~�T����X��tar-err.log�ɮסC

* tar * �u�ॴ�]�������Y�A�ݭn�g�Ltar�A�g�Lgzip or bzip2���榡���Y�C
tar -cf (���]���ɦW) (�Q�n���]���ɮ�OR�ؿ�)

c��f�@�w�n
�䤤�l�\��* c * �O�إ�tar�ɪ��A�ҥH�@�w�ݭn

�A�Ӥl�\��* f * ���w�ɮסA�p�G�ntar���O���ɮצ��������n�[

�ܩ�p�G�n���Y��bzip�� �h�n�l�\��* j *
 
gzip�� �h�n�l�\��* z *

![4](https://github.com/0905053883/107-1-ntcu-linux/blob/HW-7/ACS107134/4.PNG)
## �ϥ� ` cat tar-err.log` 

�i�H�ݨ�Ǩ�tar-err.log�����~��T
![3](https://github.com/0905053883/107-1-ntcu-linux/blob/HW-7/ACS107134/3.PNG)