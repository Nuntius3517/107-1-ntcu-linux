## 1.�Цb�a�ؿ��U��.bashrc�̷s�W�@��shell�ܼ� HOSTS_PATH=/etc/hosts�A(�`�N���ݥ�export)�A�����p�󤣵n�X��HOSTS_PATH�ܼƥͮġA����cat $HOST_PATH�T�{��Ū�����ɮפ��e�C           
                 
####   vi ~/.bashrc           
####   i �s��         
####   �s�WHOSTS_PATH=/etc/hosts         
####   esc ���}�s��       
####   :w �x�s           
####   :q ���}  
![1](https://github.com/edmundabc/107-1-ntcu-linux/blob/HW-6/ACS107131/1.PNG?raw=true)     
####   source ~/.bashrc ���n�X��HOSTS_PATH�ܼƥͮ�           
####   cat $ HOSTS_PATH �T�{��Ū�����ɮפ��e          
![2](https://github.com/edmundabc/107-1-ntcu-linux/blob/HW-6/ACS107131/2.PNG?raw=true)             
## 2.C�y���{���i�H��getenv()Ū��LINUX�������ܼơA�d�ҵ{���p�U�C�ЦbLinux�̽sĶ���d�ҵ{���ð���A�аݧ_��Ū��HOSTS_PATH�H��$?���Ȭ���?                 
                
####   vi 6.c ��J�{���X    
![3](https://github.com/edmundabc/107-1-ntcu-linux/blob/HW-6/ACS107131/3.PNG?raw=true)              
####   gcc 6.c            
####   ll 6.c a.out          
####   ./a.out            
####   �|��� getenv() return NULL (���~)       
####   echo $?            
####   �|��� 1 (�N��S����)           
           
#### ���T�� �b�e�� vi ~/.bashrc��        
####        HOSTS_PATH=/etc/hosts �e���n�[ export        
####    �o�� ./a.out �~�|��ܥ��T         
####    echo $? �]�|�ܦ� 0         
        