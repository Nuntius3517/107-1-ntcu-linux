�@  �Цb�a�ؿ��U��.bashrc�̷s�W�@��shell�ܼ� HOSTS_PATH=/etc/hosts�A(�`�N���ݥ�export)�A�����p�󤣵n�X��HOSTS_PATH�ܼƥͮġA����cat $HOST_PATH�T�{��Ū�����ɮפ��e�C

1.��Jvi ~/.bashrc�ӽs���ɮסA�i�J�s���ɮ׼Ҧ���A���Ui��i�H�i��s��C

2.�b�ɮפ���JHOSTS_PATH="/etc/hosts"�A���۫�ESC��A�A��J:wq�A�~��u�����x�s���}�C

3.��Jsource ~/.bashrc �AŪ�J���ҳ]�w�ɪ����O�A�o�˴N���έ��s�n�J�ܼƤ]��ͮĤF�C

4.�b��Jcat $HOSTS_PATH�ӽT�{���S��Ū�����ɮפ��e(�Ϥ�1)

�G  �bC�y���{���i�H��getenv()Ū��LINUX�������ܼơA�d�ҵ{���p�U�C�ЦbLinux�̽sĶ���d�ҵ{���ð���A�аݧ_��Ū��HOSTS_PATH�H��$?���Ȭ���A�л����C�]�\�ݳz�Lyum groupinstall "Development Tools"�w��gcc�C

1.��Jyum groupinstall "Development Tools" �Ӧw��gcc�A���ڪ��|�@���]�Xcannot find a valid baseurl for repo base/7/x86_64�C

2.�ڤW��google�F�@�U�ѨM��k�A������Jcd /etc/sysconfig/network-scripts�A�A��Jls -a�A���ۿ�Jvi ifcfg-ens33�A�N���Y��ONBOOT=no�令yes�A�N�i�H�w��gcc�F�C

3.��Jvi cprogram.c�A�N�D�ؤW���{���X��J��o���ɮפ��A�b���UESC�ÿ�J:wq�x�s���}�C

4.��Jgcc cprogram.c�sĶ�{���X�A���ۿ�Jgcc -c cprogram.c�A�b��Jll cprogram*�A�N��ݨ�s���ͪ��ؼ���cprogram.o�C

5.��Jgcc -o cprogram cprogram.o�Ӳ��Ͱ����ɡA��Jll cprogram*�A�����ɬ�cprogram�C

6.��J./cprogram�Ӱ��榹�{���X�C(��2)

7.��Jecho $? �A��Ȭ� 1 �C

8.�S��Ū��HOSTS_PATH�A�]�������b�l�{�Ǥ��C

�T  �b.bashrc�̭n�p��ץ��A��C�y���{���i�HŪ�������ܼƨñN�ɮפ��e��ܡC

1.��Jvi ~/.bashrc�ӭק��ɮסA��i�i�J�s��b������ܼƪ��U���Jexport HOSTS_PATH�A���UESC��J:wq�x�s�ðh�X�A�ÿ�Jsource ~/.bashrc������J�����O�ͮ�

2.�A��J�@��./cprogram����{���X�A�A��J�@��echo $?�A���G��(��3)�C


