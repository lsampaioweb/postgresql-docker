# Instructions for Configuring PostgreSQL and pgAdmin

1. **Start the Containers:**
    ```bash
    docker-compose up -d
    ```

1. **Check Logs:**
    ```bash
    docker-compose logs -f postgres
    docker-compose logs -f pgadmin
    ```

1. **Access the Container:**
    ```bash
    docker exec -it postgres bash
    docker exec -it pgadmin bash
    ```

1. **Stop the Containers:**
    ```bash
    docker-compose down
    ```

1. **Configure PGAdmin:**
    - [pgAdmin Configuration Guide](pgadmin.md)

1. **Access the Website:**
    - [https://edge-pgadmin.lan.homelab](https://edge-pgadmin.lan.homelab)

[MIT License](LICENSE "MIT License")

### Created by:

1. Luciano Sampaio.
