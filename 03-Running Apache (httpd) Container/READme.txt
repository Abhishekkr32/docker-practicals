Objective
To run the official Apache (httpd) Docker image, expose it on port 8080, modify the HTML page, verify the output, and properly remove the container.

Description
In this practical, we:
Pulled and ran the official httpd Docker image.
Exposed the container on port 8080 of the host machine.
Modified the default index.html file inside the container.
Verified the output using a command-line tool.
Stopped and removed the container after testing.

Port Mapping
Port mapping was done to make the container accessible:
Host Port → 8080
Container Port → 80

This allowed access to the web server at:
http://localhost:8080

Verification
The output was verified using a command-line tool (curl) and confirmed that the updated HTML content was displayed successfully.

Concepts Covered
Docker run with port mapping
Official Docker images
Container file modification
Web server testing using curl
Container stop and removal

✅ Conclusion

This practical demonstrated how to deploy and test a web server using Docker. It also showed how port mapping works and how to modify files inside a running container.