# IT Del Library Management System

We are proud to announce the use of **SLiMS 9 Bulian** (Senayan Library Management System) for the management and development of the **IT Del Library**. This open-source software serves as the backbone of our library management, including the handling of various resources such as books, journals, digital documents, and other library materials. SLiMS facilitates the efficient management of collections, membership, circulation, stocktaking, and many more administrative functions critical to our operations.

We would like to extend our sincere gratitude to the SLiMS development team for their dedication in providing this robust and reliable system. SLiMS has significantly contributed to improving the library management services at IT Del, enabling us to streamline processes, enhance user experiences, and ensure better resource tracking and management.

### System Requirements
- PHP version >= 8.1
- MySQL version 5.7 or MariaDB version 10.3
- PHP GD enabled
- PHP gettext enabled
- PHP mbstring enabled

### Running Docker Development

For a smooth setup, Docker is used to run the system. Ensure Docker Desktop is installed and running on your machine, as it will create the necessary database environment.

1. Before running Docker Compose, copy the `.env.example` file to `.env`. Adjust the settings for the HTTP port and MariaDB (db) port as needed.

2. To start the development environment, run the following command:

   ```shell
   docker compose up -d --build

