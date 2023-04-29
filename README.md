# web-server-using-official-NGINX-image
In this repo we walked through running the NGINX official image, adding our custom html file, building a custom image and the mount local index.html to the running container. 
By default, Nginx looks in the /usr/share/nginx/html directory inside of the container for files to serve. We need to get our html files into this directory.
A fairly simple way to do this is use a mounted volume. With mounted volumes, we are able to link a directory on our local machine and map that directory into our running container.
