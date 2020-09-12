# LEMP Installation, Nginix,Mysql and apache2 shell script fot ubuntu OS's.


  Installation script for LEMP current versions of Nginx, mysql and php for linux ubuntu.


* Download the script.

* Run the script with sudo.  
  
    ` ` ` sudo ./lemp.sh  ` ` `


* change the file permission with 777 
  
     ` ` ` sudo chmod 777 lemp.sh ` ` `  
     
  ## Prerequiste:
  
     * Ubuntu OS.
 ## Note:
 
   * You can provide your own mysql root password by changing the default password "password" provided in this shell script lemp.sh-line no:104
 
        ` ` ` ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'your-password'; ` ` `
