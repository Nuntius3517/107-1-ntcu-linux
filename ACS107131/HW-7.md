## 1.apache log�Oapache web server����x��           
## �Ьd�� curl �� wget ���Ϊk��A�Ψ䤤�@�ӫ��O�U������x�ɡC       
## �ϥ�bash��pipe���O�A�Ҧpgrep�Bcat...�����A�N����x��error�o�ͪ���]��X�ܿù��A����L��T���ݭn�e�{�C  
               
#### curl �U�������} | grep error > �ɦW        
![1](https://github.com/edmundabc/107-1-ntcu-linux/blob/HW-7/ACS107131/01.PNG?raw=true)     
## 2.tar�Olinux�U�Ψӥ��]���Y�ؿ����u��A�Цۦ�d��tar���Ϊk��A�Τ@��ϥΪ̨������]�����Y/var�ؿ��C�btar����L�{���A�������`��X���G�A���ݱN���~�T����X��tar-err.log�ɮסC     
     
#### tar -cvjpf filename.tar.bz2 /var 2> tar-err.log    
![2](https://github.com/edmundabc/107-1-ntcu-linux/blob/HW-7/ACS107131/02.PNG?raw=true)    
#### cat tar-err.log    
![3](https://github.com/edmundabc/107-1-ntcu-linux/blob/HW-7/ACS107131/03.PNG?raw=true)     