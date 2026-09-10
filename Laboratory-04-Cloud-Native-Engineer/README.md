# Checkpoint 5 — Container Lifecycle

Now you will practice managing the container.

## 1. List Running Containers

Command:

```bash
docker ps
```

**Explanation:**

This displays the containers that are currently running, including their names, status, and port mappings.

---

## 2. Stop the Running Container

Command:

```bash
docker stop nginx-server
```

**Explanation:**

This stops the running `nginx-server` container without immediately deleting it.

---

## 3. Verify That It Is Stopped

Command:

```bash
docker ps
```

You should no longer see `nginx-server` because `docker ps` only shows running containers.

You can use:

```bash
docker ps -a
```

to see both running and stopped containers.

You should see something similar to:

```text
nginx-server    Exited (...)
```

---

## 4. Remove the Container

Command:

```bash
docker rm nginx-server
```

**Explanation:**

This permanently removes the stopped `nginx-server` container.

---

## 5. Screenshot

For the required evidence, show these commands in your terminal:

```bash
docker ps
docker stop nginx-server
docker ps
docker ps -a
docker rm nginx-server
docker ps -a
```

Save the screenshot as:

```text
container-lifecycle.png
```

Put it inside:

```text
Laboratory-04-Cloud-Native-Engineer/screenshots/
```

---

## 6. Commit and Push to GitHub

After adding the screenshot, run:

```bash
git add .
git commit -m "Document container lifecycle"
git push
```

---

# Important: Docker Command Sequence

For easier copying, your complete Docker demonstration can be:

```bash
docker --version
sudo systemctl status docker

docker pull nginx

docker run -d --name nginx-server -p 8080:80 nginx

docker ps

curl http://localhost:8080

docker stop nginx-server

docker ps

docker ps -a

docker rm nginx-server

docker ps -a
```
