docker-postgres
============

Docker container for postgres that accepts remote connections from any local IPs.

In addition, now sets up database according to environment variables:
DB_NAME database  
DB_USER admin  
DB_PASS password  

To use:
-----
`docker run -d -e DB_NAME=db -e DB_USER=admin -e DB_PASS=password primebit/docker-postgres`
