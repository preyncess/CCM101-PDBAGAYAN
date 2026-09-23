# Mission Reflection

This laboratory activity helped me understand the importance of object storage for applications that need to handle many photos and other types of files. Compared to block storage, object storage is designed for unstructured data and stores files as individual objects with additional information or metadata. For a photo-sharing application with potentially millions of images, object storage is useful because the files can be managed separately from the main application server.

Docker also made the process of setting up MinIO much easier. Instead of installing and configuring the storage server manually, I was able to deploy it using a single Docker command. The MinIO container provided a separate environment where the storage service could run. I only needed to set the required ports and login credentials before opening the MinIO Web Console.

A bucket is a storage space used to organize and manage objects in an object storage system. In this activity, I created a bucket called `client-photos` for the photo-sharing application. I also uploaded a sample file to the bucket, which helped me confirm that the MinIO storage system was working properly.

For large companies, protecting stored data is very important because hardware can sometimes fail. They can use techniques such as backups, data replication, redundancy, and multiple storage locations to help prevent data loss. These methods allow copies of important data to remain available even if a server or storage device stops working.

This activity also helped improve my confidence with the Linux command line. At first, I was still getting familiar with commands for Docker, folders, and files. After completing the laboratory, I became more comfortable running commands, checking containers, creating directories, and managing files. I also learned that checking the output of each command is important because errors can affect the deployment. Overall, this laboratory gave me useful hands-on experience with Linux, Docker, MinIO, and cloud object storage.
