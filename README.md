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

    
# barcord creating 

  
   
# 1.label Template :

    Tools >Label creator > New  label template 
    
    ##create label template :
    in 
    Template code: Barcode - Avery 5160
    Template descrip :Barcode
    units :US inches
    Page hight :11
    page width:8.5
    label width :2.625
    label hight:1
    Top page marg :0.5
    Left page marg :0.187
    Top text marg :0.4
    Left text marg :0.25
    Number of columns:3
    Number of Row :10
    Gap between columns:0.125
    Gap between row 0
    
     
    this video for label template:
    
     https://www.youtube.com/watch?v=Ay3MSLq0fjc&t=357s
     
# 2.create label Layout
    Tools >Label creator > New  label layout 
    
    ##create layout :
    in
    Choose layout type : Barcode/Biblio
    lis Fields :
        Data Fields :title
     Draw guide boxes :checked
     Text justification:center
     Font Size :10


#  3.Create label 
    
     Tools >Label creator > New label batch  
     
     ISBN 10 that a number in Top of barcod
     ISBN 13 that Down barcode  
     
      ISSN INTERNATIONAL STANDARD SERIAL NUMBER
      ISBN INTERNATIONAL STANDARD BOOK NUMBER
    
    
[label_batch_6 (4).pdf](https://github.com/3bHussein/Koha-system/files/4838761/label_batch_6.4.pdf)

[label_batch_6 (3).pdf](https://github.com/3bHussein/Koha-system/files/4838762/label_batch_6.3.pdf)
    
# Access To library
    
    https://www.youtube.com/watch?v=aaLHrX1fdL8&t=330s
    
    https://www.youtube.com/watch?v=d0GkoT897BY
    
    
    
    
    
    
    
    
 # appendix smart Tools
    Change Panal : Advanced Menu
    Create Shrotcut
    Share Between PC
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
        BARCODE LABELS STICKERS
        
        https://egypt.souq.com/eg-en/barcode-labels-stickers-9944898/i/
        
        https://egypt.souq.com/eg-en/roll-barcode-thermal-sticker-size-25x38-full-1800-sticker-number-5-rollers-28379725/i/
