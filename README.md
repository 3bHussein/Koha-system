# `Koha-system`


# 
1.backup&restore Database <br>
2.scan barcord & create label <br>
3.access my library into international  koha system <br>


## Backup & Restore  
Download mysql workbench 6.3.7 <br>
link : https://downloads.mysql.com/archives/get/p/8/file/mysql-workbench-community-6.3.7-1ubu1604-amd64.deb <br>
site : https://downloads.mysql.com/archives/workbench/ <br>

or manual way :
# backup
    $ mysqldump --opt -u [uname] -p[pass] [dbname] > [backupfile.sql]
 
# Restore
    but frist create databae with the name of original name
    $ mysql -u [uname] -p [pass] 
    $ create database [db_name];
    
    $ mysql -u [uname] -p[pass] [db_to_restore] < [backupfile.sql]

    
