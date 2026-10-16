# Laboratory 08 - Cloud Security Engineer

## Mission Overview

This laboratory is about improving the security of an Ubuntu server by using UFW, controlling network access, and securing a web application.

## Objectives

- Learn the Principle of Least Privilege.
- Understand the possible attack surface of a server.
- Set up a firewall using a Default Deny policy.
- Allow SSH access and web application traffic through port 8080.
- Record the security configurations using Markdown.

## Commands Executed

```bash
docker --version
docker run -d --name secure-web-app -p 8080:80 nginx
docker ps
curl http://localhost:8080
sudo ufw status verbose
sudo ufw allow ssh
sudo ufw default deny incoming
sudo ufw default allow outgoing
sudo ufw enable
sudo ufw allow 8080/tcp
sudo ufw status numbered
```

## Skills Learned

In this laboratory, I learned how to run an Nginx container, check if the web application is working, and configure firewall rules using UFW. I also learned how to control network access and document basic security settings for a cloud server.
