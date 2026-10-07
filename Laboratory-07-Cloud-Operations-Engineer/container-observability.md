# Container Observability Report

## Application Logs

Command executed:

`docker logs client-website`

### HTTP 404 Error Log

### Failed HTTP Request (HTTP 404)

```text
172.17.0.1 - - [07/Oct/2026:02:37:53 +0000] "GET /hidden-admin-page HTTP/1.1" 404 153 "-" "curl/8.5.0" "-"
```

### Why Application Logs Are Important

Application logs help engineers identify requests that fail and understand what happened before an error occurred. They are useful for troubleshooting because they provide details that can help narrow down the cause of an application problem.

### Evidence

* `screenshots/docker-logs.png`
