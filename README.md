# Projeto em construção
# short-url-api
API to short urls with nestjs + mariadb

## Configurar projeto 

- Copiar o .env.exemple
  ```bash
  cp .env.example .env
  ```
## Subir projeto 

- Subir o proxy
```bash
 docker-compose -f proxy.docker-compose.yml up -d 
 ``` 

- Subir o projeto
```bash
 docker-compose up -d 
 ```
