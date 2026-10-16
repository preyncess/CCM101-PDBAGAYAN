# Firewall Configuration

## 1. Allow SSH

```bash
sudo ufw allow ssh
```

This command allows SSH access so the server can be managed remotely.

## 2. Set the Default Policies

```bash
sudo ufw default deny incoming
sudo ufw default allow outgoing
```

These settings block incoming connections by default while still allowing the server to make outgoing connections.

## 3. Enable the Firewall

```bash
sudo ufw enable
sudo ufw status verbose
```

These commands turn on the firewall and show its current status and settings.

## 4. Allow the Web Application Port

```bash
sudo ufw allow 8080/tcp
sudo ufw status numbered
```

This allows TCP connections through port 8080 so users can access the web application.

## 5. Importance of Allowing SSH First

SS.H should be allowed before turning on UFW because the firewall could block the SSH connection. If this happens, I may lose remote access to the server and be unable to manage it remotely

SS.H should be allowed before turning on UFW because the firewall could block the SSH connection. If this happens, I may lose remote access to the server and be unable to manage it remotely
