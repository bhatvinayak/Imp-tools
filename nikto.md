# Nikto

Nikto is an Open Source (GPL) web server scanner which performs comprehensive tests against web servers for multiple items, including over 6700 potentially dangerous files/programs,
checks for outdated versions of over 1250 servers, and version specific problems on over 270 servers.
It also checks for server configuration items such as the presence of multiple index files, HTTP server options, and will attempt to identify installed web servers and software.
Scan items and plugins are frequently updated and can be automatically updated. 


**Options**

* To specify which host to use :

> nikto -h [target_host / url]

* To disables ssl :

> -nossl

* To force ssl :

> -ssl

* To specify authentication(username + pass) :

> -id [id]:[password]

* To select which plugin to use (default: ALL):

> -Plugins
