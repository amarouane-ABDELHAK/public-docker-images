#About this image
It is a small sized docker image to get apache running using alpine

#How to use it
`git pull amarouane/alpine-apache2:latest`
`docker run -d -p 8080:80 -v webDir:/var/www/localhost/htdocs amarouane/alpine-apache2`

where webDir is the directory you want to serve using apache2
