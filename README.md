<p align="center">
<img src="https://development.lintra.nighttimedev.com/assets/media/img/ntd_black.svg" data-canonical-src="https://development.lintra.nighttimedev.com/assets/media/img/ntd_black.svg" height="80" />  
</p>

# LA.MA
<p align="center">
<img src="https://i.imgur.com/g3xXGSP.png" data-canonical-src="https://i.imgur.com/g3xXGSP.png" height="20" />  
</p>
*A PHP based CSGO-Server management Interface for LAN Tournaments.*  

!!! This project is NOT working currently! Everything is WIP !!!  

![Badge_License](https://img.shields.io/github/license/nighttimedev/lama.svg)
![Badege_Size](https://img.shields.io/github/repo-size/nighttimedev/lama.svg)
![Badge_Language](https://img.shields.io/github/languages/top/nighttimedev/lama.svg)
![Badge_LastCommit](https://img.shields.io/github/last-commit/nighttimedev/lama.svg)  
![Badge_ClosedIssues](https://img.shields.io/github/issues-closed/nighttimedev/lama.svg)
![Badge_OpenIssues](https://img.shields.io/github/issues/nighttimedev/lama.svg)  
![Badge_Stars](https://img.shields.io/github/stars/nighttimedev/lama.svg?style=social)


I've developed this to manage our CS:GO torunament @ DIE-LAN 2019. You can vsit us at https://die-lan.party  
The whole Code is filled with comments from my side, so everyone can understand what was going on in my head. I think this makes my project suitable for education / learning processes.  
Unfortunately, my SourcePawn knowledge is very limited. Thats also due to the lack of documentations about this language...  
I can't fix major Bugs if they come from xPaw's Query. But so far I haven't seen any.  

I've used xPaw's Source Server Query to make this work: https://github.com/xPaw/PHP-Source-Query  
Check him out too!  
## Developing-Process
All my test-runs, as well as troubleshooting, take(s) / took place on either my Laptop (Acer Helios 300), or one of my Dell Poweredge R710's at home.  
Both systems use VMs, which are running on Debian 9, 64 bit with Apache2 and PHP 7.3.  
I used an external SQL Database, hosted by Manitu.de, for all of my tests.  
You can check out https://www.manitu.de if you need Webhosting for your project(s), I recommend them!  
## What it needs
In order to set-up the LAMA interface, you need:  
- A Webserver (I tested on Apache2)  
- A valid PHP installation (I tested on 7.3)  
- A SQL Database  
- The LAMA-SP Plugin installed on your CS:GO Server  
## Install
- Go to your Webservers Filepath (Apache default /var/www/html)  
```sh
cd /var/www/html
git clone https://github.com/nighttimedev/lama
```  
- If you need to install apache2  
```sh
sudo apt-get install apache2
```
- If you need to install PHP  
```sh
sudo apt-update && apt-upgrade 
sudo apt install php7.3 php7.3-cli php7.3-common
```
- To check your PHP Installation
```sh
php -v
```
  
## Bugs, Issues, ...
If you get any errors, which are definitely not caused by yourself, I'd love to get your error report.  
Write me an E-Mail to: git@nighttimedev.com, with 'Error: git/lama' as Subject.
<br>
<br>
<br>  
Developed with :heart: from <img src="https://upload.wikimedia.org/wikipedia/en/thumb/b/ba/Flag_of_Germany.svg/1280px-Flag_of_Germany.svg.png" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="25" height="15" />
