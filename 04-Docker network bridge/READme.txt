Docker Networking and Volume Practical

Overview --

This practical demonstrates the use of **Docker Network** and **Docker Volume** to run multiple containers that communicate with each other.

Docker Network --

A custom bridge network app_bridge is created so containers can communicate internally using container names.

Docker Volume--

A volume mysql_data is created to store MySQL database data persistently so the data remains safe even if the container stops or is removed.

MySQL Container---

A container mysql_db is created to act as the database service and is connected to the custom network.

Backend Container --

A backend container backend_app using a Node.js Alpine image is created. It connects to the same network and uses the MySQL container as its database host.

Container Communication--

Since both containers are in the same network, the backend container can communicate with the MySQL container using its container name.

Frontend Container--

A frontend container using Nginx is created and exposed on port **8080** so the application can be accessed from a browser.

Conclusion--

This practical shows how Docker networking enables communication between containers and how Docker volumes provide persistent storage for applications.
