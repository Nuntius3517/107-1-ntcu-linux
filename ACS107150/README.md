﻿### 請在家目錄下的.bashrc裡新增一個shell變數 HOSTS_PATH=/etc/hosts，(注意不需用export)，說明如何不登出讓HOSTS_PATH變數生效，執行cat $HOST_PATH確認有讀取到檔案內容。

- vi ~/.bashrc
- 在# User specific aliases and functions下打HOSTS_PATH="/etc/hosts"
- 打esc和:wq退出並儲存
- source ~/.bashrc不登出儲存
- cat $HOST_PATH檢查

> ![image](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-6/123456/1.PNG?raw=true)

> ![image](https://github.com/JackyBigNose/107-1-ntcu-linux/blob/HW-6/123456/2.PNG?raw=true)

### 在C語言程式可以用getenv()讀取LINUX的環境變數，範例程式如下。請在Linux裡編譯此範例程式並執行，請問否有讀到HOSTS_PATH以及$?的值為何，請說明。也許需透過yum groupinstall "Development Tools"安裝gcc。

- touch hw.c
- vi hw.c並把程式碼打入此
- gcc hw.c
- echo $?顯示非0(錯誤)
- /a.out
- echo $?顯示非0(錯誤)

### 在.bashrc裡要如何修正，讓C語言程式可以讀到環境變數並將檔案內容顯示。

- vi ~/.bashrc
- 在# User specific aliases and functions下打export HOSTS_PATH
- 打esc和:wq退出並儲存
- source ~/.bashrc不登出儲存
- gcc hw.c
- echo $?顯示為0(正確)
- /a.out 
- echo $?顯示為0(正確)