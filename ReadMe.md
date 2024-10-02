##Creating First Pdb 
CREATE PLUGGABLE DATABASE plsql_class2024db 
ADMIN USER la_plsqlauca IDENTIFIED BY 1234 
FILE_NAME_CONVERT = ('C:\Oracle_21c\oradata\ORCL\pdbseed', 'C:\Oracle_21c\oradata\ORCL\orclpdb\plsql_class2024db');
##Connecting To Pdb Using Sql Developer
![Screenshot of connecting to database](images/connection.png)
##Pdb Created Successfully
![Screenshot of PLUGGABLE DATABASE](images/createpdb.png)
![Screenshot of PLUGGABLE DATABASE](images/userpdb.png)
##Creating New Pdb
CREATE PLUGGABLE DATABASE la_to_delete_pdb
   ADMIN USER new_user IDENTIFIED BY 1234
   FILE_NAME_CONVERT = ('C:\Oracle_21c\oradata\ORCL\pdbseed', 'C:\Oracle_21c\oradata\ORCL\orclpdb\la_to_delete_pdb');
##New Pdb Created Successfully
![Screenshot of new PLUGGABLE DATABASE creation ](images/createnewpdb.png)
##Delete New Pdb
DROP PLUGGABLE DATABASE la_to_delete_pdb INCLUDING DATAFILES;
![Screenshot of Deleting New PLUGGABLE DATABASE](images/dropnewpdb.png)
![Screenshot after Deleting New PLUGGABLE DATABASE](images/pdbafterdrop.png) 
##Login to Oracle Enterprise Manager
![Screenshot of Login](images/login.png)  
##Oracle Enterprise Manager Dashboard
![Screenshot of Dashboard](images/dashboard.png)