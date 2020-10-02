# nginx
NGINX configuration for Docker

This is a basic NGINX configuration for WordPress sites and Magento sites that will be running in customer docker environments. 

There are three branches in this project. They are as follows: 

:preventdirectaccess - This is a special nginx build for usin  the wordpress plugin 'prevent direct access'. This is only to be used on sites that use that plugin (Builds on Docker Hub) 

:development - This is where changes are made, tested and eventually merged to master. (Builds on Docker Hub) 

:master - this is for general usage with most websites. (Builds on Docker Hub) 
