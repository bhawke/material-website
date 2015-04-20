Blackhawk Website
==============

Get the source
--------------
    git clone https://github.com/bhawke/website.git

Building and Running
---------------
```
    cd website
    npm install
    bower install
    gulp serve
```


To Build for production (minify, uglify, etc...)
---------------
    gulp

To Deploy to production
----------------
*You only have to do this once*
```
    git remote add appengine https://code.google.com/id/89AMhpErMqz/
    git push appengine master
```

Continuous Integration
----------------
https://travis-ci.org/

URL
----------------
http://www.blackhawkenterprise.com
