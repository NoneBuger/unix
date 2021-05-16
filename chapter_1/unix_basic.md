# unix basic
1.2 kernel + shell + commonlib + application
1.3 login: cat /etc/passwd
1.4 myls run : 
gcc -o myls myls.c -lapue

libapue.a install:
step1. download src.3e.tar.gz from http://www.apuebook.com/src.3e.tar.gz
step2. tar -zxvf src.3e.tar.gz
step3. sudo apt-get install libbsd-dev
step4. cd apue.3e && make
step5. cp ./include/apue.h /usr/include/
step6. cp ./lib/libapue.a /usr/local/lib/
step7. compile your own pragmma use static link -lapue,such as:
	gcc -o xx xx.c -lapue


