## �̤U�C�y�z�����û����U�����D�G<br>
### 1.�Цb�a�ؿ��U��.bashrc�̷s�W�@��shell�ܼ� HOSTS_PATH=/etc/hosts�A(�`�N���ݥ�export)�A�����p�󤣵n�X��HOSTS_PATH�ܼƥͮġA����cat $HOST_PATH�T�{��Ū�����ɮפ��e�C<br>

```
vi ~/.bsahrc
�NHOSTS_PATH=/etc/hosts���i�ɮ�
esc���}�s��Ҧ�
:wq���}���x�s
sourse ~/.bashrc 
cat $HOSTS_PATH
```
![image](https://github.com/percy890713/107-1-ntcu-linux/blob/HW-6/ACS107145/img/HW6-1.PNG)<br>
![image](https://github.com/percy890713/107-1-ntcu-linux/blob/HW-6/ACS107145/img/HW6-2.PNG)<br><br>
### 2.�bC�y���{���i�H��getenv()Ū��LINUX�������ܼơA�d�ҵ{���p�U�C�ЦbLinux�̽sĶ���d�ҵ{���ð���A�аݧ_��Ū��HOSTS_PATH�H��$?���Ȭ���A�л����C<br>
![image](https://github.com/percy890713/107-1-ntcu-linux/blob/HW-6/ACS107145/img/HW6-3.PNG)<br><br>
```
gcc test.c
./a.out (getenv() return NULL�ֿ֡��~)
echo $? (1�ֿ֡��~)
```
![image](https://github.com/percy890713/107-1-ntcu-linux/blob/HW-6/ACS107145/img/HW6-4.PNG)<br><br>
### 3.�b.bashrc�̭n�p��ץ��A��C�y���{���i�HŪ�������ܼƨñN�ɮפ��e��ܡC<br>

```
vi ~/.bashrc
��export���bHOSTS_PATH=/etc/hosts�e��
gcc test.c
./a.out
echo $?
```
![image](https://github.com/percy890713/107-1-ntcu-linux/blob/HW-6/ACS107145/img/HW6-5.PNG)<br>
![image](https://github.com/percy890713/107-1-ntcu-linux/blob/HW-6/ACS107145/img/HW6-6.PNG)<b