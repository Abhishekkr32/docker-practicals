docker run -dit --name myhttpd -p 8080:80 httpd
docker exec -it myhttpd bash
echo "<h1>Hello from Docker Apache</h1>" > /usr/local/apache2/htdocs/index.html
exit
curl http://localhost:8080
docker stop myhttpd
docker rm myhttpd