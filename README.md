# Multiuser-Online-Auction-System


Instructions to run the project


Task 1 : Download and Setup XAMPP

Step 1: Download and Install XAMPP

To download and install XAMPP, go to apachefriends downloads page, the official link to download XAMPP from. You will see XAMPP ready to download for cross-platform like Windows, Linux, Mac OS X. Since we are discussing How to install XAMPP on Windows 10, therefore, we will choose the Windows option as shown below.

 


Step 2: Run the Installer to Install XAMPP

XAMPP Setup Wizard

During the installation process, you may come across warning pop-ups. But you would probably click ‘Yes’ to start the installation process. Soon after you click on the downloaded file, the XAMPP setup wizard will open. Now click on the ‘Next’ Button to proceed.
 

Step 3: Select Components

Next, you need to check the components which you want to install and can uncheck or leave as it is which you don’t want to install. You can see there are a few options which are light grey in color. These are the options which are necessary to run the software and will automatically be installed. Now click on the ‘Next’ button to continue.

 

Step 4 : Select Installation Folder

Now you need to choose the folder where you want to install the XAMPP. You can choose the default location or you can choose any location of your choice and choose the ‘Next’ button to move ahead.

 

Bitnami for XAMPP

Now will see a window showing you information about Bitnami. Simply click on the ‘Next’ button to move further. However, if you wish to learn more about the Bitnami, then you may check the box sa
ying ‘Learn more about Bitnami for XAMPP.’
Basically Bitnami is for installing open source applications i.e. WordPress, Joomla etc on your newly installed XAMPP.


Ready to Install XAMPP

Now you’ll see another window with a message “Setup is now ready to begin installing XAMPP on your computer” like shown below. You just have to hit the ‘Next’ button to proceed.


 

Welcome to XAMPP Wizard

Now just be patient and wait for the installation to complete.

 

XAMPP Installation Complete

Once the installation is completed, you will be asked whether you would like to start the control panel now or not, displaying the message “Do you want to start the control panel now?” Check the box and click on the ‘Finish’ button and see if the XAMPP is working fine.

 

You may need to select language and then you are good to go.


















Task 2 : Take control of XAMPP 

If the entire process of XAMPP installation went correctly, then the control panel would open smoothly. Now click on the ‘Start’ button corresponding to Apache and MySQL.

 



 

That’s it. You have successfully installed XAMPP on Windows 10. Or say you have successfully installed XAMPP locally. Once you start the modules, you should see their status turn to green. Whereas, on the right side, you can see the process ID number and port numbers every module is using. You’re good to go now.

Note :
If you see error mentioning problem with port 3306 (default port) then it means that port number 3306 is already taken by some other process (mostly by MySQL Workbench). Then go to services and then select service MySQL and stop it.
Then again restart XAMPP control panel. It should resolve the issue.




Task 3 : How to run Multiuser-Online-Auction-System

Step 1 : Add source code folder in htdocs folder

Open xampp folder and open htdocs folder

 










Add source code folder in htdocs folder

 


Step 2 : Create DataBase

Open PhpMyAdmin or paste this link http://localhost/phpmyadmin/

Click on new, enter name of database as ‘online-auction-master’ and click on create as shown in image

 




Step 3 : Import database

Select new created database and go to ‘import’ section and choose the .sql file as shown in the image

 

Click on ‘Go’ button at the bottom.
Now the database is added.
You can study, edit database at http://localhost/phpmyadmin/

Step 3 : Run the project

Go to the browser and paste http://localhost/Online-Auction-master/
or http://localhost/your-project-name/

 

Note : 

You can enter into the system as admin by clicking ‘Admin Login’ and entering required credentials :

Username : admin   or   Username : admin2
Password : admin           Password : admin2

Username : admin3   or   Username : admin4
Password : admin3          Password : admin4
 
In order to bid or sell a product you need to sign up/register first by entering the required details.
Once you have registered yourself you are ready to take part in selling and bidding.

Note :  All fields are mandatory, so you need to fill all credentials.








Happy Bidding :)











