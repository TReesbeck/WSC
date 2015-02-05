# WSC
Wolverine Strength &amp; Conditioning

You'll need Apache, MySql, and PHP to run this application.

Clone the project on your computer
git clone https://github.com/TReesbeck/WSC.git

Navigate to the public directory and install Composer
curl -sS https://getcomposer.org/installer | php

Then, use Composer to install dependencies
php composer.phar install

If you know what you're doing wp-config.php's database settings, by all means tweak it so that it works for you. Otherwise, the default settings are for a database named 'a2xfit' hosted on localhost with a username of 'root' and password of ''.