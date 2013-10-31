#Another scripts? Seriously??

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

##Wp Config Par
With this script you can add some parameter in the wp-config.php 

`wordmove-wp-config-par [security|debug|misc]`

The parameter it's needed for choose the type of parameter to add to the wp-config.  

  security: 
	  DISALLOW_FILE_EDIT:	true
  misc: 
	  WP_POST_REVISIONS:	3
  debug: 
	  WP_DEBUG:    true

#License
GPL GPL GPL GPL GPL GPL GPL GPL GPL GPL GPL GPL!  
I have already said GPL?

#Thanks

Thanks to weLaika for [Wordmove](https://github.com/welaika/wordmove)!