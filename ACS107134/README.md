### �Цb�a�ؿ��U��.bashrc�̷s�W�@��shell�ܼ� HOSTS_PATH=/etc/hosts�A(�`�N���ݥ�export)�A

### �����p�󤣵n�X��HOSTS_PATH�ܼƥͮġA����cat $HOST_PATH�T�{��Ū�����ɮפ��e�C
    �ϥ� vi �s��i�J .bashrc ��
    ����ϥ�source filename �Ӥ��n�X�����ͮ�
![1](https://github.com/0905053883/107-1-ntcu-linux/blob/HW-6/ACS107134/1.PNG)

### �bC�y���{���i�H��getenv()Ū��LINUX�������ܼơA�d�ҵ{���p�U�C

### �ЦbLinux�̽sĶ���d�ҵ{���ð���A�аݬO�_��Ū��HOSTS_PATH�H��$?���Ȭ���A�л����C

### �]�\�ݳz�Lyum groupinstall "Development Tools"�w��gcc�C


    #include <stdio.h>
    #include <stdlib.h>
    int main()
    {
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

### �b.bashrc�̭n�p��ץ��A��C�y���{���i�HŪ�������ܼƨñN�ɮפ��e��ܡC

#### (1).
##### �sĶ     : gcc file.c  �@�w�n.c
##### ����     : ./�ɮ�
> Ans : �L�k�z�L ` getenv() `Ū���ܼ� *HOSTS_PATH*���ȡC
> ���M�S��Ū��Ǧ^�Ȧ���{���ӻ��P�_ *s* �� NULL �����ߡA�ҥH *$?* ���Ǧ^�� 1�C

#### (2).
    �ڤ��|