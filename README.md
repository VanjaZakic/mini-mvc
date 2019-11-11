![MINI - A naked barebone PHP application](_install/mini-logo.png)

# MINI

MINI is an extremely simple and easy to understand skeleton PHP application, reduced to the max.
MINI is NOT a professional framework and it does not come with all the stuff real frameworks have.
If you just want to show some pages, do a few database calls and a little-bit of AJAX here and there, without
reading in massive documentations of highly complex professional frameworks, then MINI might be very useful for you.
MINI is easy to install, runs nearly everywhere and doesn't make things more complicated than necessary.

## Features

- extremely simple, easy to understand
- simple but clean structure
- makes "beautiful" clean URLs
- demo CRUD actions: Create, Read, Update and Delete database entries easily
- demo AJAX call
- tries to follow PSR 1/2 coding guidelines
- uses PDO for any database requests, comes with an additional PDO debug tool to emulate your SQL statements
- commented code
- uses only native PHP code, so people don't have to learn a framework


## Auto-Installation on Ubuntu 14.04 LTS (in 30 seconds)

You can install MINI including Apache, MySQL, PHP and PHPMyAdmin, mod_rewrite, Composer, all necessary settings and 
even the passwords inside the configs file by simply downloading one file and executing it, the entire installation 
will run 100% automatically. Find the tutorial in this blog article: 
[Install MINI in 30 seconds inside Ubuntu 14.04 LTS](http://www.dev-metal.com/install-mini-30-seconds-inside-ubuntu-14-04-lts/)

## Installation

1. Edit the database credentials in `application/config/config.php`
2. Execute the .sql statements in the `_install/`-folder (with PHPMyAdmin for example).
3. Make sure you have mod_rewrite activated on your server / in your environment. Some guidelines:
   [Ubuntu 14.04 LTS](http://www.dev-metal.com/enable-mod_rewrite-ubuntu-14-04-lts/),
   [Ubuntu 12.04 LTS](http://www.dev-metal.com/enable-mod_rewrite-ubuntu-12-04-lts/),
   [EasyPHP on Windows](http://stackoverflow.com/questions/8158770/easyphp-and-htaccess),
   [AMPPS on Windows/Mac OS](http://www.softaculous.com/board/index.php?tid=3634&title=AMPPS_rewrite_enable/disable_option%3F_please%3F),
   [XAMPP for Windows](http://www.leonardaustin.com/blog/technical/enable-mod_rewrite-in-xampp/),
   [MAMP on Mac OS](http://stackoverflow.com/questions/7670561/how-to-get-htaccess-to-work-on-mamp)
