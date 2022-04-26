# hackupc

## Create the dataset

### If you have docker
Pull the image
>docker pull mundimoto/postgres-hackupc

Run the image
>docker run -e POSTGRES_DB=mundimoto -e POSTGRES_PASSWORD=not_secure_pass -e POSTGRES_USER=hackupc --name postgres-hackupc -p 5432:5432 -i mundimoto/postgres-hackupc:latest

### If you don't have docker
Download and install Docker
>https://www.docker.com/products/docker-desktop/

Pull the image
>docker pull mundimoto/postgres-hackupc

Run the image
>docker run -e POSTGRES_DB=mundimoto -e POSTGRES_PASSWORD=not_secure_pass -e POSTGRES_USER=hackupc --name postgres-hackupc -p 5432:5432 -i mundimoto/postgres-hackupc:latest		

### If you don't want to use or can't have Docker
Download and install PostgreSql (If you don't have it)
>https://www.postgresql.org/download/

Download the [init.sql](https://github.com/Mundimoto/hackupc/blob/main/init.sql) file

Execute the init.sql file
