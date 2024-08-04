Yes I know you are a newbie in this cybersecurity field like me...well doesn't matter you are newbie or not but you have come at right place to get a solution. Well I have been into the situation where you are at right now.....searching for SQLi lab to be successfully install on Windows in 2024 or future. ======================================================================================================================================================

I know after watching thousands of repositories and youtube videos on How to install sqli labs in windows you are familiar with the below mentioned error.

Fatal error: Uncaught Error: Call to undefined function mysql_connect() in C:\xampp\htdocs\sqli-labs-master\sql-connections\setup-db.php:29 Stack trace: #0 {main} thrown in C:\xampp\htdocs\sqli-labs-master\sql-connections\setup-db.php on line 29. ======================================================================================================================================================

Well for the new ones out there installing this lab for the first time at the end, I have provided the steps to install, you can skip this chat & further jump onto the installation steps. This chat is just for the ones who faced the above mentioned error. So guys want to know what was the problem? Well it was just the version of the PHP used in Xampp. We downloaded the latest xampp application and it had latest version of PHP. There was a conflict in the PHP versison of lastest Xampp and  php version used in this sqli lab. I have provided which xampp version you need to download in the below installtion steps. Quickly go, install it & enjoy your sqli dumbs series labs. ======================================================================================================================================================

Steps to install Sqli labs in Windows
1) Download & Install the given version only of Xampp (xampp-win32-5.6.30-1-VC11-installer) or else  will face the above mentioned error. Link to download https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/5.6.30/
2) Download and extract the sqli-lab-master which is provided in my repo.
3) copy the sqli-lab-master folder to C drive/xampp/htdocs/
4) Run xampp start Apache and Mysql
5) Open Browser in the URL type http://localhost/sqli-labs-master/
6) click on setup/reset database for lab
7) And you are good to go. Enjoy.
