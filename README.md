# Dockerized Infrastructure

## How to run

This command will run all services
`docker-compose up --build -d`

For specific service 
`docker-compose up --build -d service_name`

## 1. Mysql v8.0 Database

|Name|Value|
|----|------|
|Port|3306|
|Username|root|
|Password|eucRvgVdaJMfY4G9R5KPwZ3V5g6pm8DP|
|DSN|mysql://root:eucRvgVdaJMfY4G9R5KPwZ3V5g6pm8DP@localhost:3306/`your_db`|

## 2. Postgres v12.4 Database

|Name|Value|
|----|------|
|Port|5432|
|Username|postgres|
|Password|BZHnDem5mcbtJkk9YbZee787SyAFGy7x|
|DSN|postgres://postgres:BZHnDem5mcbtJkk9YbZee787SyAFGy7x@localhost:5432/`your_db`|
|Create user query|CREATE USER username WITH ENCRYPTED PASSWORD 'user_password';|
|Grant access query|GRANT ALL PRIVILEGES ON DATABASE db_name TO username;|

## 3. Minio Object Storage

|Name|Value|
|----|------|
|API Port|9000|
|Console Port|9001|
|Admin Username|AKIAIOSFODNN7EXAMPLE|
|Admin Password|wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY|

## 4. Redis

|Name|Value|
|----|------|
|Port|6379|
|Password|wXU7z2HQtBP6mWjHbPsfK96rmnqweawg|
|DSN|redis://:wXU7z2HQtBP6mWjHbPsfK96rmnqweawg@localhost:6379/|
