![alt text]([https://github.com/[username]/[reponame]/blob/[branch]/image.jpg](https://github.com/Deadlineem/Multi-Stat/blob/main/images/logo.png])?raw=true)
Multi-Stat is a Free to use server status checker coded in php/html/css
it is designed for use with MineStat's Powershell module


To install MineStat, open Windows Powershell as Administrator
Once powershell is opened type Install-Module -Name MineStat


If you get an error run set-executionpolicy remotesigned in powershell
and then run Install-Module -Name MineStat

After installing minestat, you can test it using 
MineStat -Address <host> -Port <port> -Protocol <protocol> -Timeout 1

If you are planning to host MineStat on a shared webhost, make sure 
that the provider allows outbound sockets.		     


To use Multi-Stat after installing MineStat, simply download it and
add it into your IIS/Wamp/Xampp website folder then edit the 
settings.php file.

Inside the settings.php you will find the site title and header
values, you can change these to accommodate your site.

Below that you will see "berockIP = array("localhost");
You can add or edit this accordingly, separating each
host with a comma.

Below that you will see "javaIP = array("localhost");
You can add or edit this accordingly, separating each
host with a comma.

After you are done setting it up, visit the page by typing
localhost in your browser


For more information about MineStat, visit https://github.com/FragLand/minestat/tree/master
