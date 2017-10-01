# Docker LEMP (Linux, Nginx, MariaDB, PHP)
A minimal LEMP stack for local development

### Requirements
  - Docker & Docker Compose installed

    1. Install Docker

      ```
      $ curl -fsSL get.docker.com -o get-docker.sh && \
        sh get-docker.sh
      ```

    2. Run this command to download the latest version of Docker Compose:
      ```
      $ sudo curl -L https://github.com/docker/compose/releases/download/1.16.1/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
      ```

    3. Apply executable permissions to the binary:
      ```
      $ sudo chmod +x /usr/local/bin/docker-compose
      ```

    4. Test the installation.
      ```
      $ docker-compose --version
      ```

    5. Adjust the permissions
      ```
      sudo usermod -aG docker $(whoami)
      ```

### Usage

`docker-compose up -d`
