# OWASP-Bricks-fixed
OWASP Bricks but with fixed version for servers running the latest PHP and mySQL. Fixed errors are mostly sql errors such as `Uncaught Error: Call to undefined function mysql_connect()`


Original files: [OWASP Bricks Download](https://sechow.com/bricks/download.html)

Dependency: [github/rubo77](https://github.com/rubo77/php-mysql-fix)


### Installation Guide ###
1. Clone this repo on server www/ directory.
2. Create a dedicated database for the OWASP bricks using phpmyadmin or other mysql console.
3. Direct to the webpage. eg: http://localhost/bricks 
4. Go through the installation process by filling in db details. Submit and save the `LocalSettings.php` file in the bricks folder
5. Once succeed, go to Setup page and click 'setup/reset database' button.
6. Done and dusted.



<u>OWASP Bricks details</u>
Code name: Tuwai
Version: 2.2 
Date of release: 30 November 2013
