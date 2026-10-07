# Mission Reflection

In this laboratory activity, I learned that monitoring is an important part of managing a cloud environment. Before deploying an application, it is necessary to check the host server's resources, such as RAM, disk storage, and CPU usage. Even if a container is running properly, the host may not have enough resources to handle more users. If memory or disk space becomes insufficient, the application may become slow or experience errors.

The `docker logs` command is useful when a user reports that they cannot log in to a web application. By checking the logs, an engineer can look for error messages, failed requests, and other events that may help identify the problem. Logs do not always reveal the complete cause, but they provide useful information for further investigation.

I also learned the difference between logs and metrics. Logs record individual events, requests, and errors, while metrics show numerical measurements such as CPU usage, memory consumption, and network activity. Both are important because logs help explain what happened, while metrics help show how the system is performing.

For large companies that manage thousands of containers, monitoring tools such as Prometheus and Grafana can help collect, organize, and visualize performance information. Prometheus can collect time-series metrics, while Grafana can display dashboards that make it easier to identify unusual resource usage and performance problems.

This activity also helped improve my Linux troubleshooting skills. I practiced checking system resources, deploying an Nginx container, generating HTTP requests, and examining Docker logs and metrics. I learned that troubleshooting should be based on actual evidence instead of guessing. In the future, I can use these commands and monitoring concepts to investigate problems more carefully and help maintain reliable cloud applications.

