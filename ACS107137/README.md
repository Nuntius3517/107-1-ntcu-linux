## �̤U�C�y�z�����û����U�����D�G<br>
### 1.�Цb�a�ؿ��U��.bashrc�̷s�W�@��shell�ܼ� HOSTS_PATH=/etc/hosts�A(�`�N���ݥ�export)�A�����p�󤣵n�X��HOSTS_PATH�ܼƥͮġA����cat $HOST_PATH�T�{��Ū�����ɮפ��e�C<br>

```
vi ~/.bsahrc
**i**�s��A�NHOSTS_PATH=/etc/hosts���i�ɮ�
**esc**���}�s��Ҧ��A**:wq**���}���x�s
sourse ~/.bashrc
cat $HOSTS_PATH
```


### 2.�bC�y���{���i�H��getenv()Ū��LINUX�������ܼơA�d�ҵ{���p�U�C�ЦbLinux�̽sĶ���d�ҵ{���ð���A�аݧ_��Ū��HOSTS_PATH�H��$?���Ȭ���A�л����C<br>


```
gcc test.c
./a.out(���getenv() return NULL (���~))
echo $?(���1 (���~))
```


### 3.�b.bashrc�̭n�p��ץ��A��C�y���{���i�HŪ�������ܼƨñN�ɮפ��e��ܡC<br>

```
vi ~/.bashrc
�N**export**���bHOSTS_PATH=/etc/hosts�e��
gcc test.c
./a.out
echo $?(���0 (���T))
```

