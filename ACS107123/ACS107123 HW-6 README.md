(�@)
1.��J" vi ~/.bashrc ": �s���ɮסA���U i �i��s��C
2.�ɮפ���J" HOSTS_PATH="/etc/hosts" "
3. ��ESC��A��J" wq " !!!
4. ��J" source ~/.bashrc "�AŪ�J���ҳ]�w�ɪ����O
5. ��J" cat $HOSTS_PATH "�T�{
(�G)
*����
1.��" vi/vim �ɦW.c "�s�W�@���ɮסA�ÿ�J�{���X
2.����" gcc �ɦW.c "(�Υ�yum groupinstall "Development Tools"�w��gcc)
3.��J" ll �ɦW.c a.out "
4.����" a.out " Ū����" HOSTS_PATH "�A�]�����b�l�{��
5.��J" echo $? "�A�|���" 1 "�A�N��L�k���\����
*���\ 
1. �s�W" export HOSTS_PATH "
2. �A��J�@��" source ~/.bashrc "
(�U�������N�O�e�����A���@��)
3. ��" vi/vim �ɦW.c "�s�W�@���ɮסA�ÿ�J�{���X
4. ����" gcc �ɦW.c "(�Υ�yum groupinstall "Development Tools"�w��gcc)
5. ��J" ll �ɦW.c a.out "
6. ����" a.out "�A�i�HŪ��" HOSTS_PATH "
7. ��J" echo $? "�A�|���" 0 " �A�N���\����
(�T)
1. ��J" vi ~/.bashrc "�A�i�J .bashrc �s��
2. ��J" export HOSTS_PATH=/etc/hosts "
3. �b��J���ܼƫe����J" export "
4. ��J" source .bashrc "Ū���ק鷺�e
5. ��J" gcc test.c "�sĶ test.c
6. ��J" ./a.out "
7. ��X" test.c "�����G
8. ��J" echo $ "�ҦL�X���e�C