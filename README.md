Alexandre Jacquemin

**Get next line - 25 hours**  
Get Next Line. Qu'il s'agisse d'un fichier, de l'entrée standard, ou même plus tard d'une connexion réseau, vous aurez toujours besoin de lire du contenu ligne par ligne. Il est donc temps de vous attaquer à cette fonction, indispensable pour un certain nombre de vos prochains projets.

----

**✅ 42fileChecker**  
Test: OK

**ℹ️ Execution time**  
```openssl rand -out 27.txt -base64 $((2**27 * 3/4))```  
*BUFF_SIZE 10*    ./test_gnl 27.txt  **11.78s** user **10.73s** system 60% cpu 37.073 total  
*BUFF_SIZE 32*    ./test_gnl 27.txt  **7.38s** user **5.73s** system 54% cpu 24.228 total  

----

**✅ Moulinette 125/100**  
test_error: **1/1** correct tests | test_basic: **8/8** correct test | test_medium: **3/3** correct test | test_hard: **1/1** correct test | test_random_buff: **3/3** correct test | test_full_random: **4/4** correct test | test_non_printable: **1/1** correct test | test_bonus_static: **1/1** correct test | test_bonus_fd: **5/5** correct test
