1.���}�������A�n�Jroot�A��Jvi ~/.bashrc�Ӷi�J�s���ɮת��Ҧ��A�b���Ui�Y�i�}�l�s��
2.�b�ɮפ����@�B��JHOSTS_PATH="/etc/hosts"�A�ӷs�W�o���ܼơA��J������UESC�����}�s��A
�A��J:wq�N�i�H�x�s�M�����}�s��Ҧ��F�C
3.��Jsource ~/.bashrc�AŪ�J���ҳ]�w�ɪ����O�A���L�i�H���έ��s�n�J�A�ܼƤ]��ͮġC
3.���}��A��Jcat $HOSTS_PATH�T�{�O�_�ন�\Ū�����ɮפ��e�C(����1)
------------------------------------------------------------------------------------------------------------------------
1.��Jyum groupinstall "Development Tools"�Ӧw��GCC�A�o�b�̫�@��]�Xcannot find a valid baseurl for repo base/7/x86_64�A
�ҥH��Jnmtui�A�h�ˬd�����O�_���}�ҡA���}�����]�w����A�A��J�@��yum groupinstall "Development Tools"�Y�i�w�˦��\�C
2.�w�˦��\��A��Jcd�^�a�ؿ��A��Jvi cprogram�A�N�{���X��J��cprogram�o���ɮפ�(�ɦW�O�H�K����)�A
��ESC���}�s��Ҧ��A�A��J:wq�x�s�����}�C
3.��Jgcc cprogram.c�Ӷi��{���X���sĶ�A�S���X�{error���ܡA��Jgcc -c cprogram.c�A�A��Jll cprogram*�A
�i�H���s���ؼ���cprogram.o�C
4.��Jgcc -o cprogram cprogram.o�Ӳ��Ͱ����ɡA��Jll cprogram*�A�i�H�ݨ�����ɬ�cprogram�C
5.��J./cprogram�Ӱ��榹�{���X�C(����2)
6.��Jecho $?�A�|�]�X1�C
7.�S��Ū��HOSTS_PATH�A�]�������b�l�{�Ǥ��C
-------------------------------------------------------------------------------------------------------------------------
1.��Jvi ~/bashrc�i��ק��ɮת��ʧ@�A���Ui�}�l�s��A�b�e������ܼƪ��U���Jexport HOSTS_PATH�A
��ESC���}�s��Ҧ��A�b��J:wq�x�s�����}�A�b��Jsource ~/bashrc�A����J�����O�ͮġC
2.�A��J�@��./cprogram����{���A�A��J�@��echo $?�A�|�]�X1�C

