�����Q��**vi** �s��@**.bashrc**�@�ɮ�

![image](https://github.com/freshdiefish/107-1-ntcu-linux/blob/HW-6/ACS107125/1.jpg)

���ɡA�ڭ̨ϥΫ��O**source** �N�i�H�b���n�X�����p�U���ܼƥͮ�

![image](https://github.com/freshdiefish/107-1-ntcu-linux/blob/HW-6/ACS107125/2.jpg)

�ϥ�**cat $HOST_PATH** �T�{�ܼƤ��e

![image](https://github.com/freshdiefish/107-1-ntcu-linux/blob/HW-6/ACS107125/3.jpg)

�p�G�t�θ̨S��gcc�A�i������**yum groupinstall "Development Tools"** �w�˥�

�Q��**vi**�Ы��ɮרöK�W�H�U�{���X

    #include <stdio.h>
    #include <stdlib.h>

    int main(){
        const char* s = getenv("HOSTS_PATH");
        if(s == NULL){
            printf("getenv() return NULL\n");
            return 1;
            }
    
    printf("HOSTS_PATH :%s\n",(s!=NULL)? s : "getenv returned NULL");
    printf("\n %s content is: \n", s);

    int c;
    FILE *file;
    file = fopen(s, "r");
    if (file) {
        while ((c = getc(file)) != EOF)
                putchar(c);
        fclose(file);
    }
    }


����**gcc _(�ɦW)_.c**�sĶ����� **./a.out**

�o�{**getenv() return NULL**

�A��**echo $?** �d�ݤW�ӫ��O���^�ǭ�(�]�N�O�ڭ�code���^�ǭ�)��ruturn 1

![image](https://github.com/freshdiefish/107-1-ntcu-linux/blob/HW-6/ACS107125/4.jpg)

�i�H�o���{��Ū������ڭ��s�W���ܼ�

why?�]�� **$HOSTS_PATH**���ϰ��ܼƦӫD�����ܼơA�L�k����L���{���i��ϥ�

�ڭ̦^��Ĥ@�B�s��@**.bashrc**�@�ɮ�

�b�ڭ̪��ܼƫŧi���Y�[�W**export**�ŧi���������ܼ�

�A�ϥ�**source**���]�w�ͮ�

���� **./a.out**�i�H�T�{**getenv()**���F�ڭ̳]�w���ܼ�

�̫�**echo $?** �ѵ{���X�i�����\���槹���ɮסA�^�ǭȬ�0

![image](https://github.com/freshdiefish/107-1-ntcu-linux/blob/HW-6/ACS107125/5.jpg)