Simple docker container that can be used as a Data Volume. 
To run the container and expose the volume run a command similar to this:

# based on run data container from Tutum
docker run -d -v /var/lib/mysql --name sql_data -p 22:22 granthbr/data
