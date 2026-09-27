# Mission Reflection

This laboratory helped me understand how Docker Compose can make cloud deployment easier and more organized. Instead of manually typing many Docker commands for each container, I can place the needed configuration inside a `docker-compose.yml` file. Once the file is prepared, Docker Compose can create and start the different services using one command. This makes the deployment process faster and easier to repeat.

I also learned that YAML is very sensitive to indentation. Spaces are important because they show the relationship between different parts of the configuration. If I accidentally use a Tab or place the spaces incorrectly, Docker Compose may not understand the file correctly and can return an error. Because of this, I realized that checking the format of the YAML file is an important part of deployment.

Environment variables such as `MYSQL_PASSWORD`, `MYSQL_DATABASE`, and `MYSQL_USER` were also important in this activity. They provide the configuration needed by the containers without placing those settings directly inside the application commands. They also make it easier to change configuration values when needed.

Deploying Nextcloud in only a few minutes was a good experience for me because I was able to see how different cloud components can work together. Seeing the Nextcloud setup page made the deployment feel more real and practical.

Since Mission 1, my understanding of Cloud Computing has improved. At first, I mainly understood cloud computing as accessing resources over the internet. Now, I have a better understanding of infrastructure, containers, storage, databases, networking, and deployment. This laboratory showed me that cloud computing also involves planning and managing different services so they can work together as one system.
