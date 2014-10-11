#Useful tools for auto detection or improvement

##Requirements

* PHP5-CLI
* YAML (`pecl install yaml`)
* FTP data

##Install

    cd /tmp
    git clone https://github.com/Mte90/Wordmove-tools
    chmod +x ./Wordmove-tools/*.php
    mv ./Wordmove-tools/*.php /usr/local/bin/
    rm -r ./Wordmove-tools

##Syntax

##WordPress Config Generator
With this script you can generate the wp-config with the data of Movefile  

`wordmove-wp-config [local|staging|production|etc] [ftp]`

The first parameter it's needed for generate the wp-config by Movefile.  
With the second parameter upload the file generated via ftp to the host.

##WordPress Config Paramaters
With this script you can add some parameter in the wp-config.php 

`wordmove-wp-config-par [security|debug|misc]`

The parameter it's needed for choose the type of parameter to add to the wp-config.  

* security:
    * DISALLOW_FILE_EDIT:	true
* misc:
    * WP_POST_REVISIONS:	3
* debug:
    * WP_DEBUG:    true

##Wordmove Exclude Themes and Plugins
With this script in the Movefile are added all the template and plugins that exists in wordpress installation, launch this and remove the lines that you don't need.

`wordmove-exclude [-p|-t]`

-p - plugins  
-t - themes

##Wordmove Absolute Path
With this script you insert the absolute_path in the Movefile  

`wordmove-absolute-path [staging|production|etc]`

The first parameter it's needed for get the absolute path of the host and insert in the Movefile.  

##Wordmove Database
With this script is possible auto insert the remote database data in the Movefile

`wordmove-database [staging|production|etc]`

The first parameter it's needed for get the database data of the host and insert in the Movefile.

##Wordmove Wordpress Path Detection
With this script is possible detect the path of wordpress. 
Detect if httpdocs/publich_html exist in the remote host.

`wordmove-path-detect [staging|production|etc]`

#License
GPL GPL GPL GPL GPL GPL GPL GPL GPL GPL GPL GPL!  
I have already said GPL?

#Thanks

Thanks to weLaika for [Wordmove](https://github.com/welaika/wordmove)!