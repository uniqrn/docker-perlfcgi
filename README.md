# docker-perlfcgi
perl FastCGI server docker-image

* requests for .fcgi are handled by FastCGI(mod_fcgid)
* requests for .cgi are handled by CGI(mod_cgid)

## perl PATH
`#!/usr/bin/perl`
Derived from original httpd docker image

## DocumentRoot
`/usr/local/apache2/htdocs`
