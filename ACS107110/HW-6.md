��vim .bashrc
��HOSTS_PATH="/etc/hosts"(�إ��ܼ�)
(��6-1)
��vim test.c (�إߤ@���ɮ�)
����i�}�l��J
����J�{��
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
����esc���X
����J:wq�Y�i�s�����}
����Jgcc test.c
����J./a.out
���:getnev() return NULL
����Jecho $?
���:1
(�p��6-2)
���̫�A�i�Jvim .bashrc
��HOSTS_PATH="/etc/hosts"�e���[�Jexport
����Jsource .bashrc
����Jecho $HOSTS_PATH
���:/etc/hosts
����Jcat $HOSTS_PATH
�p�ϩҥ�(6-3)
   	
