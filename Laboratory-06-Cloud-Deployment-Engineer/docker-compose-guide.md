# Multi-Tier Architecture

## What is a Two-Tier Architecture?

A two-tier architecture is a system that separates an application into two main parts: the web/application tier and the database tier. The web/application tier handles the requests from users, while the database tier stores and manages the application's data.

## The Web/Application Tier

The web/application tier is responsible for providing the user interface and handling HTTP requests from users. In this laboratory, the Nextcloud container serves as the application that users access through a web browser. It allows users to interact with the private cloud storage system.

## The Database Tier

The database tier is responsible for storing persistent information used by the application. In this laboratory, MariaDB is used as the database container. It stores information such as Nextcloud user accounts and other data needed by the application.

## Why Separate Them?

Separating the web application and database into different containers makes the system easier to manage and maintain. Each container has its own responsibility, so the database can be managed separately from the Nextcloud application and the system can be expanded more easily in the future.
