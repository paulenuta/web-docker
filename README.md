# web-docker
Simple nginx web server with local index.html volume mounted.

`docker run --name web-docker -v ~/web-docker:/usr/share/nginx/html:rw -p 8080:80 -d nginx`
