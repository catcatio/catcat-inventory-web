# catcat-inventory-web
CatCat inventory web version

### To develop
1. Up `prisma`, `postgres`, `pgadmin`
    ```
    cd dev
    . up
    ```
1. Prisma server
    ```
    cd server
    yarn dev
    ```
1. Apollo web client
    ```
    cd web
    yarn install
    yarn start
    ```
    - email : `developer@example.com`
    - password : `nooneknows`

1. PostgreSQL admin
    - open `http://localhost:5050`
    - Connection : `postgres`
    - SSL : `Disable`