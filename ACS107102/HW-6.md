###  Shell ��¦�{��
## shell �ܼ�
1. �b�a�ؿ��U�� `.bashrc` �̷s�W�@��shell�ܼ� `HOSTS_PATH=/etc/hosts`
  *  `HOST_PATH=/etc/hosts`
2. ���n�X�ܼƧY�ͮ� 
  *  `source ~/.bashrc`
3. �˵�
  *  `cat $HOST_PATH`

## Linux�U��c�y��
1. �d�ҵ{�� `test.c`

  ```
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

  ```

  *  `gcc -o test test.c`
  *  `./test`
       `getenv() return NULL`
    -  ���d��HOSTS_PATH
  *  `$?`
    -  `bash: 127:command not found`
  *  `echo $?`
    -  `1`

## Ū�������ܼƨñN�ɮפ��e���
1. `export HOST_PATH="/etc/hosts"`
   `source ~/.bashrc`
   `cat $HOST_PATH`
   `gcc -o test test.c`
   `./test`

   ```
   HOSTS_PATH :/etc/hosts
   
   /etc/hosts contest is:
   127.0.0.1  localhost localhost.localdomain localhost4 localhost4.localdomain4
   ::1        localhost localhost.localdomain localhost6 localhost6.localdomain6
   ```

   *  �]�����ܼƦb��L���l�{�Ǥ��U�A���Hexport�Ө��ܼ��ܦ������ܼ�