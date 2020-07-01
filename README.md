# MsqlDocker

- Create a Docker Compose YAML file for a MySQL Docker container.
- Connect to the MySQL database, running on a container, using various methods.
- Create and run multiple versions of MySQL in Docker containers.


`
docker-compose up
`

By using MySQL Workbench  we can connect MYSQL.

- If we want to connect to containerized MySQL, without mapping ports, i.e. from another application running on the same Docker network, we have to use tools like Adminer, which is our other method.

- Adminer is a PHP-based web application for accessing databases.

- Add another service for Adminer in our docker-compose.yml.

- In Browser Go to localhost:8080 for Adminer

We can also use the MySQL command-line interface with the following command:
`
docker-compose exec  mysql-development mysql -u<username> -p<password> <database>
`
Enter the details.
![Image of Yaktocat](https://github.com/HarshaVardhanAcharyAthaluri/MsqlDocker/blob/master/login.PNG)
Login Success.
![Image of Yaktocat](https://github.com/HarshaVardhanAcharyAthaluri/MsqlDocker/blob/master/success.PNG)