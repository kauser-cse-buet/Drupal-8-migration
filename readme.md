** How to start development in new.uno.edu with drupal **
To start developing on local branch:
- git checkout master 
- git pull
- fin init 
- fin dump 
- fin cim
- fin build_theme

fin dump && fin cim
check: http://newunoedu.docksal


To make changes. 
- git create <new-branch>
- git checkout new branch 
- fin cex
- git add -A
- git commit -m ""
- git push

clear cache
- fin drush cr

disable debug
- go to /Projects/new.uno.edu/docroot/sites/default
- rename settings.local.php to settings.local.php.backup



