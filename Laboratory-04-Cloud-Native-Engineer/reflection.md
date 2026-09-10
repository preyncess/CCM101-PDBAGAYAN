# Mission Reflection

During this laboratory activity, I learned how containerization can make application deployment faster and more efficient compared to using traditional Virtual Machines. When using a Virtual Machine, an entire operating system needs to be installed and started before an application can run. This can take several minutes and requires more RAM and storage. In comparison, a Docker container uses the existing host operating system kernel, so it can start within seconds. This makes containers useful when applications need to be deployed quickly.

I also learned why port mapping is important when running a web server inside a container. The Nginx server runs on port 80 inside the container, but the container is isolated from the host system. By using `-p 8080:80`, requests sent to port 8080 on the host are forwarded to port 80 inside the container. This allowed me to access the Nginx web server using `curl http://localhost:8080`.

Another important lesson was understanding what happens when using `docker rm`. When a container is removed, the container itself and the data stored inside its writable layer are deleted. This means important data should not be stored only inside a temporary container. Persistent data should instead use Docker volumes or another appropriate storage solution.

Containerization also changes how developers and IT operations teams work together. Developers can package an application and its dependencies into a container, while operations teams can deploy the same container in different environments. This supports DevOps because it creates a more consistent and efficient deployment process.

My GitHub portfolio is becoming more organized and useful as I add each laboratory activity. It now shows not only written reports but also practical cloud computing skills, technical commands, documentation, and screenshots as evidence of my work.
