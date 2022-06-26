# Simple PHP, Apache, MySQL Environment :whale:

This project is a simple set up for PHP, Apache, and MySQL based environment. 

This project contains a customized dockerfile to connect the MySQL environment to the PHP code. Uses Adminer to manage the database.

Project has also setup a volume/bind mount to allow editing our code on our local machine to take effect within the Docker container.

Finally added MySQL, and add in a persistant data storage by setting up a volume for MySQL. Later, testing it out using Adminer.

> For step-by-step instructions checkout `docker_commands.txt` file.