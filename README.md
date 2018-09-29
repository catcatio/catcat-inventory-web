# catcat-inventory-web
CatCat inventory web version

### To develop
1. Up `prisma`, `postgres`, `pgadmin`
![image](https://user-images.githubusercontent.com/97060/46247676-2a7fd200-c439-11e8-9998-5a192bf1856d.png)
    ```
    cd dev
    . up
    ```
1. Prisma server
![image](https://user-images.githubusercontent.com/97060/46247693-5e5af780-c439-11e8-8b69-a866d1a3504e.png)
    ```
    cd web/server
    yarn dev
    ```
1. Apollo web client
    ![image](https://user-images.githubusercontent.com/97060/46247638-8ac24400-c438-11e8-9b19-880b92cf0e41.png)
    ```
    cd web
    yarn install
    yarn start
    ```
    - email : `developer@example.com`
    - password : `nooneknows`
1. PostgreSQL admin
![image](https://user-images.githubusercontent.com/97060/46247600-e8a25c00-c437-11e8-9fc0-43bf77b13d18.png)
    - open `http://localhost:5050`
    - Connection : `postgres`
    - SSL : `Disable`
    
