#Smarty 3 template engine
##Distribution repository
Starting with Smarty 3.1.21 Composer has been configured to load the packages from github.
 
**NOTE: Because of this change you must clear your local composer cache with the "composer clearcache" command**

To get the latest stable version use

	"require": {
	   "smarty/smarty": "~3.1"
	}

in your composer.json file.
 
 To get the trunk version use

	"require": {
	   "smarty/smarty": "~3.1@dev"
	}

The "smarty/smarty" package will start at libs/....   subfolder.

To retrieve the development and documentation folders add

     "require-dev": {
         "smarty/smarty-dev": "~3.1@dev"
     }

