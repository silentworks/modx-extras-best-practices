---
isChild: true
---

## Windows Setup {#windows_setup_title}

If you are developing on Windows you are most likely using [Wamp][wamp], [XAMPP][xampp] or one of
the other AMP (Apache, MySQL and PHP) bundles around.

If you are using your normal localhost directory as root for you site development, you will need to
install MODX in a subdirectory in order to work with the Extras outside of the MODX root directory.

Here is what your setup might look like (using WAMP in this instance):

    C:\wamp\www - webroot
    C:\wamp\www\modx-2.2.6-pl - MODX webroot
    C:\wamp\www\extra1 - Extra webroot

However some developers like to work in isolated VirtualHost environments, in this instance you 
can have multiple sites setup on your system without worrying about overcrowding your localhost
directory.

[xampp]: http://www.apachefriends.org/en/xampp.html
[wamp]: http://www.wampserver.com/
