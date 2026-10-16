# Mission Reflection

Completing Mission 8 helped me understand the importance of cloud security when managing servers and web applications. I learned that a host-based firewall can protect a server by controlling which network connections are allowed or blocked. Even if someone gets past the main network security, the firewall can still prevent unauthorized connections. This gives the server an additional layer of protection.

I also learned that managing open ports is important because exposed services can become possible targets for attackers. Only the ports that are needed should be allowed to reduce the server's attack surface. In this activity, I allowed SSH for remote server management and TCP port 8080 for the Nginx web application. These firewall rules showed me how access can be limited to only the services that are required.

Opening a database port like MySQL port 3306 to the public internet can create security risks. Attackers could try different passwords, take advantage of software weaknesses, or gain access to important data. In a real enterprise environment, database connections should only be allowed from trusted application servers or authorized networks. Using strong passwords, keeping software updated, and setting proper permissions are also important security practices.

This mission changed the way I think about server security. I realized that simply running an application is not enough because network access and firewall settings also need to be checked. I learned how important it is to configure firewall rules correctly and test them to make sure they are working. I also learned that allowing SSH before enabling the firewall can help prevent losing remote access to the server.

My GitHub portfolio now shows my progress through eight cloud computing missions. Each laboratory has given me hands-on experience in server management, application deployment, monitoring, and security. Keeping my documentation and screenshots organized also makes it easier to show the work I completed. Moving forward, I want to learn more about network security and use these practices when working with cloud applications.
