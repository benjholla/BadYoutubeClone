# CompletelyDigitalClips
A bad clone of YouTube in PHP for learning to hack

This is an intentionally insecure web app!  It goes without saying that this should never be used in any sort of production environment.

# Setup Application Servers

Run `sudo apt-get update`

Run `sudo apt-get install git`

Run `sudo apt-get install apache2`

Run `sudo apt-get install php5 libapache2-mod-php5 php5-mcrypt php5-mysql libapache2-mod-auth-mysql`

Edit `/etc/php5/apache2/php.ini`

Set `file_uploads = On`

Set `upload_max_filesize = 100M`

Set `post_max_size = 100M`

Checkout application source

`git clone https://github.com/benjholla/BadYoutubeClone.git`

# Setup Database Server

Run `sudo apt-get update`

Run `sudo apt-get install mysql-server`

Optionally [install phpMyAdmin](https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-phpmyadmin-on-ubuntu-12-04)

Run `sudo apt-get install apache2`

Run `sudo apt-get install php5 libapache2-mod-php5 php5-mcrypt php5-mysql libapache2-mod-auth-mysql`

Run `sudo apt-get install phpmyadmin apache2-utils`
