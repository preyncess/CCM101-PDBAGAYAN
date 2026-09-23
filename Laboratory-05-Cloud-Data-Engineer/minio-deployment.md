# MinIO Object Storage Deployment

## Docker Deployment

MinIO was set up using Docker with ports 9000 and 9001 configured for its services.

```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server -e "MINIO_ROOT_USER=cloudadmin" -e "MINIO_ROOT_PASSWORD=CloudNova2026!" quay.io/minio/minio server /data --console-address ":9001"

``` 
## Port Configuration

The MinIO Web Console was opened through port 9001.

Port 9000 handles the MinIO API, which is used for communication with the storage server. Port 9001 provides access to the web-based MinIO management console.

Bucket Created

For this activity, I created a bucket named:

``` bash
client-photos
```

The bucket was used as the storage area for the client's photo-sharing application. I also uploaded a sample file to check if the object storage system was functioning properly.

## Environment Variables

The -e options in the Docker command were used to configure the login details of the MinIO server.

``` bash
MINIO_ROOT_USER=cloudadmin
```

This sets the username for the MinIO administrator account.

``` bash 
MINIO_ROOT_PASSWORD=CloudNova2026!
```

This sets the password for the administrator account.

These environment variables provide the login credentials when the MinIO container starts, allowing the administrator to access the MinIO Web Console.
