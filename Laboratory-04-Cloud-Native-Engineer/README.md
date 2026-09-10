# Container Lifecycle

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


docker ps -a
```
