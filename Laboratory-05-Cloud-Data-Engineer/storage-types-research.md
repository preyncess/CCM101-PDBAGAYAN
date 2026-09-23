# Cloud Storage Types Research

## Comparison of Cloud Storage Types

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Divides data into blocks and provides storage that can be connected to a virtual machine like a regular disk. | Commonly used for operating systems, databases, and applications that require fast storage access. | AWS EBS |
| File Storage | Organizes data into files and folders that can be accessed and shared by different systems. | Useful for shared documents, files, and applications that need a shared file system. | AWS EFS |
| Object Storage | Saves data as individual objects along with information or metadata that describes each object. | Suitable for storing large amounts of files such as photos, videos, backups, and other unstructured data. | AWS S3 |

## Why Object Storage is Suitable for the Client

Object Storage is suitable for the client's photo-sharing application because it is designed to handle large amounts of unstructured files, including user-uploaded photos. It can store a large number of images and allows them to be accessed when needed, making it useful for an application that may eventually contain millions of photos.
