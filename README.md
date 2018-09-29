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

![image](https://user-images.githubusercontent.com/97060/46247600-e8a25c00-c437-11e8-9fc0-43bf77b13d18.png)
