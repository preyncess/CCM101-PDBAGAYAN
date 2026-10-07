# Laboratory 07 - Cloud Operations Engineer

## Mission Overview

This laboratory activity focuses on monitoring a Linux server and observing a containerized web application. I used the KillerCoda environment to check the host's resources, deploy an Nginx container, generate HTTP requests, and inspect application logs and container metrics.

## Objectives

* Check the host's RAM and available disk storage.
* Observe running processes and CPU activity using Linux tools.
* Deploy an Nginx container using Docker.
* Generate successful HTTP requests and an intentional HTTP 404 error.
* Inspect application logs and real-time container resource usage.
* Document the results using Markdown and screenshots.

## Monitoring Commands Executed

| Command                      | Purpose                                    |
| ---------------------------- | ------------------------------------------ |
| `free -h`                    | Check RAM usage                            |
| `df -h /`                    | Check root filesystem storage              |
| `top`                        | Observe CPU activity and running processes |
| `docker ps`                  | Check running containers                   |
| `curl http://localhost:8080` | Send a request to the web server           |
| `docker logs client-website` | View application logs                      |
| `docker stats`               | Monitor container resource usage           |

## Skills Learned

Through this activity, I practiced using Linux commands to inspect system resources and Docker commands to deploy and monitor a web application. I also learned how HTTP status codes, application logs, and container metrics can help an engineer investigate problems and observe application behavior.

## Evidence

Screenshots and monitoring results are stored in the `screenshots/` folder and the related laboratory reports.

