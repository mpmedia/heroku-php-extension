heroku-cedar-php
================

Compiled a few library for Heroku's PHP extension - imagick.so, apc.so, gd.so

available extension : mongo.so , curl.so , gd.so
-----------------------------
Instruction for 'imagick.so':
----------------------------

1.  create folder "ext" in project folder

2.  put "imagick.so" in "ext" folder

3.  create file "php.ini" in main folder of project

4.  Add these lines to "php.ini" 
<PRE>extension dir = "/app/www/ext/"
  extension=imagick.so
</PRE>
5.  Run:  git add php.ini ext/imagick.so 

6.  Run: git commit -m "PHP's imagemagick library"

7.  Run:  git push heroku master 

Google it for these extensions: zlib.so, mbstring.so, mongodb.so
