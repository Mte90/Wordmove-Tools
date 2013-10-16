#Another script? Seriously??
wp-config-wordmove.php it's a simple script that which uses the data of Movefile (config file of [Wordmove](https://github.com/welaika/wordmove)) for generate the wp-config of the other host.  
Uh and can also upload it on ftp on the choosen host!

##Requirements

* PHP-CLI
* YAML (`pecl install yaml`)

##Install

Move this scripts to /usr/local/bin

##Syntax

##Wp Config Generator
With this script you can generate the wp-config with the data of Movefile  

`wordmove-wp-config [local|staging|production|etc] [ftp]`

The first parameter it's needed for generate the wp-config by Movefile.  
With the second parameter upload the file generated via ftp to the host.

##Absolute Path
With this script you insert the absolute_path in the Movefile  

`wordmove-wp-config [local|staging|production|etc]`

The first parameter it's needed for get the absolute path of the host and insert in the Movefile.  

#License
GPL GPL GPL GPL GPL GPL GPL GPL GPL GPL GPL GPL!  
I have already said GPL?

#Thanks

Thanks to weLaika for [Wordmove](https://github.com/welaika/wordmove)!