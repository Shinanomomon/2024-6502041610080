# How to setup application with `Strapi4` via `Docker`

## CLI
```bash
docker run --name my_db \
-p 8080:1337 \
-e POSTGRES_PASSWORD=shinakami \
-e POSTGRES_USER=naphaphon \

```
## UI
### Name
  Container Name = my_db
### Ports
  - 8080:1337
### Environment Variable
  - DATABASE_CLIENT = postgres
  - DATABASE_NAME = ..
  - DATABASE_HOST = .ipconfig. //change' => 192.168.x.x//
  - DATABASE_PORT = ..
  - POSTGRES_PASSWORD = ..
  - POSTGRES_USER = ..

