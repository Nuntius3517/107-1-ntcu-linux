## �̤U�C�y�z�����û����U�����D�G<br>
### 1.�Ьd�� curl �� wget ���Ϊk��A�Ψ䤤�@�ӫ��O�U��(apache web server)����x��(apache log)�C<br>

```
wegt https://raw.githubusercontent.com/ogre0403/107-1-ntcu-linux/master/resource/web.log
```
�U�����᪺�ɮ׬� web.log<br>

### 2.�ϥ�bash��pipe���O�A�Ҧpgrep�Bcat...�����A�N����x��error�o�ͪ���]��X�ܿù��A����L��T���ݭn�e�{�C<br>

```
cat web.log |grep error
```

### 3.tar�Olinux�U�Ψӥ��]���Y�ؿ����u��A�Цۦ�d��tar���Ϊk��A�Τ@��ϥΪ̨������]�����Y/var�ؿ��C�btar����L�{���A�������`��X���G�A���ݱN���~�T����X��tar-err.log�ɮסC<br>

```
tar -c -f homework.tar /var 2> rat.err.log
```